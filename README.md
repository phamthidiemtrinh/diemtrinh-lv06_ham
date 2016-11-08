# Báo cáo học hàm
## 1. Định nghĩa hàm:
- Định nghĩa: hàm là một đoạn chương trình đọc lập thực hiện một công việc và trả về kết quả cho chương trình gọi nó.
- Đặt điểm:
  * là một đơn vị độc lập của chương trình
  * không xây dựng hai hay nhiều hàm lồng nhau
  
## 2.Cú pháp:
Mẫu chung của các hàm như sau:

``````
Kieu_tra_ve Ten_ham(Danh_sach_tham_so)

{ khai báo biến cục bộ;
    lệnh;
    return[biểu thức];
 }
 ```````````
                 
Trong đó:
- Kieu_tra_ve : kiểu dữ liệu sẽ trả về cho hàm
- ten_ham : tên của hàm, khi gọi tên này thì sẽ gọi đến hàm và thực hieẹn công việc được hàm định nghĩa
- Danh_sach_tham_so: là khai báo các tham số hình thức để truyền tham trị.
- khai báo biến cục bộ: ( tùy chương trình có thể có hoặc không) các biến này được sử dụng trong nội bộ hàm
- lệnh: các llệnh thực hiện công việc của hàm
- return: gán giá trị trả về cho hàm.
- biểu thức: là giá trị trả về cho hàm.

**Ví dụ:** tìm max của hai số a,b:

````````
int max(int a,int b)
{
  if (a>b) return a;
  else return b;
}
```````````


***Lưu ý:***
- hàm có thể có giá trị trả về hoặc không, hàm không có giá trị trả về thì khai báo từ khóa void đứng trước 
 
**Ví dụ:** in n lần tên

```````
void Inten(int n)
{ 
    int i;
    for (i=0;i<n;i++)
      pritnf("%d. ten ",i);
}
``````````

## 3. Hàm có đối con trỏ (tham chiểu)

- đối của hàm kiểu dữ liệu nào thì tham soó thực tương ứng phải là địa chỉ của biến kiểu tương ứng.
- sử dụng khi muốn bảo lưu kết quả tính toán của các đối số trong hàm.



 

# Website Trung Tam Tieng Anh (TTA)

Dự án **website đăng ký khoá học** của trung tâm tiếng Anh TTA, làm trong môn *Nhập môn Công nghệ thông tin*

## Cấu trúc thư mục

| Thư mục | Nội dung |
|---------|----------|
| archive | bản sao lưu logo và ảnh lớp học|
| data | Danh sách học viên khoá 3 và bảng học phí tháng 10 |
| docs | Lịch học các lớp |
| logs | Log truy cập website, log thanh toán và các file báo cáo |
| media | logo và ảnh lớp học |

## Quy trình đăng ký học tại TTA
Bước 1: Học viên xem lịch học trong thư mục `docs` để chọn khoá phù hợp.

Bước 2: Đăng ký khoá và nhận mã đăng ký theo mẫu có trên web trường

Bước 3: .Thanh toán học phí qua cổng thanh toán của trung tâm.

Bước 4: Nhận thông báo đăng ký khóa học thành công qua email à chờ ngày nhập học chính thức

## Lệnh hay dùng

```shell
dir -a , ls -a
```
## Việc cần làm

- [x] Tổ chức lại thư mục dự án
- [x] Lọc log và tạo báo cáo lỗi, cảnh báo
- [ ] Hoàn thiện bảng học phí tháng 10
- [ ] Chạy chính thức website

> Lưu ý: file `.env` chứa dữ liệu bí mật của dự án, tuyệt đối không upload lên 

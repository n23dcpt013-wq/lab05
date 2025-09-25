# lab05
 Tích hợp, quản lý và báo cáo

 
Thông tin sinh viên Họ tên: Đường Xuân Đô MSSV: N23DCPT013 Lớp: D23CQPT01-N Môn học: Nhập môn công phần mềm
 Qui trình làm việc:

 Thu thập yêu cầu: hệ thông cần có chức năng đăng nhập cơ bản
 Tác nhân 

Người dùng (User)

Hệ thống (System)

Chức năng chính (Functional requirements)

Người dùng nhập Tên đăng nhập và Mật khẩu.

Hệ thống kiểm tra thông tin nhập.

Nếu đúng → cho đăng nhập thành công.

Nếu sai → báo lỗi (ví dụ: “Sai thông tin, vui lòng thử lại”).

Điều kiện / Ràng buộc (Constraints)

Username và password không được để trống.

Password phải được nhập ở dạng ẩn (••••).

Hệ thống chưa cần kết nối CSDL thật (mock rule: user = student, pass = 123456).

Phi chức năng (Non-functional requirements)

Giao diện thân thiện, dễ sử dụng.

Có thông báo rõ ràng khi đăng nhập sai/đúng.

Bảo mật cơ bản: không hiển thị password.

Phân tích và thiết kế:
![Use Case Diagram](https://github.com/n23dcpt013-wq/lab05/blob/main/usecase.png)
![Use Case Diagram](https://github.com/n23dcpt013-wq/lab05/blob/main/SQ.png)


Triển khai form 

![file code]()

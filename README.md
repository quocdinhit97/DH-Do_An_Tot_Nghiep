# Xây dựng hệ thống tư vấn cải thiện môn học cho sinh viên Đại học Trà Vinh
<code>SVTH: Phùng Quốc Định </code>
<code>GVHD: Nguyễn Ngọc Đan Thanh </code>
_____________________________________________________________

* Tất cả source code được public tại github: 

**Một số thông tin

	► URL User: http://localhost:15648/Login

	► URL admin: http://localhost:15648/admin/AdminLogin
	username: 110115012@sv.tvu.edu.vn
	password: adminqd

## Yêu cầu các phần mềm có trên máy
	► Visual studio 2017 trở lên
	► SQL Server 2014 trở lên


## Restore CSDL:
	Trong thư mục bạn tải về có 2 file backup: 1 file script và 1 file dùng restore trực tiếp.
	Có 2 cách để restore csdl: 
		► Mở file script có đuôi .sql và chạy trên SQL Server
		► Trong SQL Server vào Database -> restore database ... và chọn đến file backup còn lại
	Chi tiết bạn có thể xem video tại đường dẫn: https://youtu.be/ZMl6_67NcEA 	(7p50)


## Thay đổi đường dẫn đến csdl trong visual studio:
	Mở file Web.config tìm đến dòng connectionString thay thế chuổi connectionString bằng chuổi connectionString trỏ đến csdl vừa restore

	Chi tiết bạn có thể xem video tại đường dẫn: https://youtu.be/ZMl6_67NcEA 		(10p)

** Sau khi hoàn thành các bước trên bạn có thể chạy chương trình
_____________________________________________________________

Facebook: https://www.facebook.com/PhungQuocDinh
Youtube: https://www.youtube.com/channel/UCwXIeWhUBsUDkSMzUW_sazA

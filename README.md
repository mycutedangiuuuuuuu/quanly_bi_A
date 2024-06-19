# quanly_bi_A

# Sinh viên thực hiện :
- Họ và tên : Nguyễn Thị Chà My
- Lớp : K57KMT
- Mssv :k215480106110
- Tên đề tài : quản lý quán bi_a
# Mô tả hệ thống :
-	Bảng ‘Dangkyban’: Bảng này lưu trữ thông tin về các lần khách hàng đăng ký bàn tại quán bi-a
-	Bảng ‘Khachhang’: Bảng này lưu trữ thông tin chi tiết về các khách hàng.
-	Bảng ‘Lichban’: Bảng này lưu trữ thông tin về lịch làm việc của nhân viên liên quan đến việc phục vụ khách hàng.
-	Bảng ‘Nhanvien’: Bảng này lưu trữ thông tin chi tiết về các nhân viên làm việc tại quán.
-	Bảng ‘Ban’: Bảng này lưu trữ thông tin chi tiết về các bàn trong quán bi-a.

Thông tin cụ thể từng bảng :
-	Thông tin cụ thể các bảng như sau :
-	‘Dangkyban’ : Id  🔑 , Makhachhang, Tenkhachhang, Maban, Ngay, Thoigianbatdau, Thoigianketthuc.
-	‘Dangkyban’ : Id 🔑 , Makhachhang, HoTen, Ngaysinh, Goitinh, Sodienthoai.
-	‘Lichban’ : Id🔑 ,Manhanvien, Makhachhang, Maban, Ngay, Giobatdau, Gioketthuc.
-	‘Nhanvien’ : Id🔑 ,Manhanvien, Hoten, Ngaysinh, Gioitinh, Sodienthoai , Diachi , soccd.
-	‘Ban’ : Id🔑 , Maban, Tenban, Tinhtrangban,Gia_gio.
Để xây dựng một hệ thống :
	Để xây dựng một hệ thống quản lý nhà hàng hiệu quả, chúng ta cần giải quyết một số vấn đề cơ bản sau:
1.	Quản lý thông tin khách hàng:
-	Lưu trữ thông tin chi tiết về khách hàng, bao gồm mã khách hàng, họ tên, ngày sinh, giới tính, số điện thoại, địa chỉ, và số căn cước công dân.
-	Đảm bảo rằng mỗi khách hàng được xác định duy nhất bởi mã khách hàng.
2.	Quản lý thông tin nhân viên:
-	Lưu trữ thông tin chi tiết về nhân viên, bao gồm mã nhân viên, họ tên, ngày sinh, giới tính, số điện thoại, địa chỉ, và số căn cước công dân.
-	Đảm bảo rằng mỗi nhân viên được xác định duy nhất bởi mã nhân viên.
3.	Quản lý bàn trong nhà hàng:
-	Lưu trữ thông tin về các bàn, bao gồm mã bàn, tên bàn, tình trạng bàn, và giá thuê bàn theo giờ.
-	Đảm bảo rằng mỗi bàn được xác định duy nhất bởi mã bàn.
4.	Quản lý đăng ký bàn của khách hàng:
-	Lưu trữ thông tin về các lần đăng ký bàn của khách hàng, bao gồm mã khách hàng, tên khách hàng, mã bàn, ngày, thời gian bắt đầu và thời gian kết thúc đăng ký.
-	Đảm bảo rằng mỗi lần đăng ký bàn được xác định duy nhất bởi một mã đăng ký.
5.	Quản lý lịch làm việc của nhân viên:
-	Lưu trữ thông tin về lịch làm việc của nhân viên, bao gồm mã nhân viên, mã khách hàng, mã bàn, ngày, giờ bắt đầu và giờ kết thúc.
-	Đảm bảo rằng mỗi lịch làm việc được xác định duy nhất bởi một mã lịch.




![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/66955842-7a41-4f78-b1f5-c4788cb89a84)
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/8cd9bf90-d8e6-424c-9daf-64b0149feeac)
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/5494bfde-da59-48df-96ad-ff22c8da499d)

kiểm tra lịch đặt bàn :

![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/9e9d91ae-cf11-4d65-beca-4b94a1f90503)

Test ví dụ :

![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/b37b4ddc-ee29-4053-9901-48ede59ab634)

chức năng đặt lịch bàn :

![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/080e0a8c-a081-4b80-9812-c3c71b5d005c)

chức năng kiểm tra số lần đặt lịch trong tuần:
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/5bbfcb6b-23bb-40fe-8556-55ccd4b2b956)

![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/96bf02fe-9edb-457f-b0d7-e1105e9fbc0c)

chức tính tiền bàn 
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/8e2868e0-760a-465a-ad8c-f832291fe215)

![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/d6d25fd1-ced9-444b-ad1e-3322c83581e5)
Funtion tính tiền bàn trong ngày 
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/f5c907a5-334a-4e16-9055-6dc86f2b56db)
![image](https://github.com/mycutedangiuuuuuuu/quanly_bi_A/assets/168768223/a83dfe28-ca8b-487f-8618-0d6b7c45111b)











### Báo cáo phân tích IPO: Quy trình sử dụng Backup Codes khi mất điện thoại

1. Input

-   Mã Backup Codes đã được tạo và lưu trữ an toàn từ trước.
    
-   Điện thoại chứa Google Authenticator bị mất.
    
-   Tài khoản AWS không thể đăng nhập bằng mã OTP thông thường.
    

2. Process 

1.  Em sử dụng thiết bị đáng tin cậy để truy cập trang đăng nhập AWS chính thức.
    
2.  Nhập tài khoản, mật khẩu và sử dụng một mã Backup Codes để xác minh danh tính.
    
3.  Sau khi đăng nhập thành công, em thu hồi hoặc hủy thiết bị xác thực cũ và kiểm tra các phiên đăng nhập đáng ngờ.
    
4.  Thiết lập lại Google Authenticator trên điện thoại mới.
    
5.  Tạo bộ Backup Codes mới và lưu ở nơi an toàn. Không tiếp tục sử dụng bộ mã cũ.
    

3. Output

-   Em lấy lại được quyền truy cập tài khoản AWS.
    
-   Điện thoại bị mất không còn được sử dụng để xác thực tài khoản.
    
-   Bộ mã dự phòng mới được bảo vệ an toàn.
    
-   Hệ thống giảm nguy cơ bị kẻ khác chiếm đoạt.
    

### 4. Tại sao không được lưu Backup Codes dưới dạng ảnh trong thư viện điện thoại?

-   Ảnh có thể tự động đồng bộ lên Google Photos hoặc iCloud.
    
-   Nếu tài khoản lưu trữ đám mây bị hack, kẻ xấu có thể lấy được mã dự phòng.
    
-   Người nhặt được điện thoại có thể xem ảnh nếu thiết bị không được bảo vệ tốt.
    
-   Backup Codes có thể bị sử dụng để vượt qua bước xác thực hai yếu tố

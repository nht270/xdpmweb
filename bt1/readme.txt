- Đầu tiên chúng ta sẽ tạo API bằng mockAPI.io
- Sau đó chúng ta dùng ajax để tạo yêu cầu gửi đến server và nhận về một dữ liệu từ URL_API
- Các dữ liệu sẽ được trả về được Jquery chuyển thành định dạng array/object
- Các product sẽ xuất ra tên và giá
- Function deleteProduct sẽ xóa product theo id của chúng 
- Khi click vào product chúng ta sẽ lấy được id của sản phẩm và gọi lại hàm deleteProduct để xóa product chúng ta vừa chọn.
* Để chạy được file index.html:
+ Mở file bằng trình duyệt web
+ Giao diện sẽ là các product(thông tin tên và giá product) lấy dựa trên URL_API
+ Để xóa product chúng ta chỉ cần click vào product cần xóa.

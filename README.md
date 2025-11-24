# Dự án Spring Boot - Cửa hàng Hoa quả Online

* Đây là dự án backend được xây dựng bằng Spring Boot cho một website thương mại điện tử chuyên bán hoa quả được host trên fruitshop.tech
* Dự án được fork từ dự án https://github.com/hieunhangia/swp-project nhưng có sự điều chỉnh theo tên miền fruitshop.tech.
## Mô tả

Dự án này mô phỏng một hệ thống cửa hàng trực tuyến, cho phép người dùng xem danh sách sản phẩm, quản lý giỏ hàng và đặt hàng. 
## Thành viên
* Hiệu: https://github.com/hieunhangia
* Bình: https://github.com/tk20042901
* Nghĩa: https://github.com/nghianguyentin99
* Trường: https://github.com/Liu2k5
## Tính năng chính

### Guest (Khách vãng lai)

* **Xem:**
    * Danh sách sản phẩm (Product List)
* **Tương tác:**
    * Đặt câu hỏi cho AI (Question To AI)
    * Nhận câu trả lời từ AI (AI-Generated Response)

### Customer (Khách hàng)

* **Tài khoản & Xác thực:**
    * Thực hiện Xác thực (Authentication) (Đăng nhập, Đăng ký)
* **Mua sắm:**
    * Quản lý giỏ hàng (Shopping Cart Management)
    * Tạo đơn hàng (Order Creation)
    * Cung cấp thông tin giao hàng (Delivery Info)
* **Theo dõi:**
    * Xem trạng thái đơn hàng (Order Status)
    * Xem lịch sử đơn hàng (Order History)
    * Nhận xác nhận thanh toán (Payment Confirmation)

### Admin (Quản trị viên)

* **Quản lý tài khoản:**
    * Quản lý tài khoản Manager (Manager Account Management)
    * Quản lý tài khoản nhân viên (Staff Account Management)

### Manager (Người quản lý)

* **Báo cáo:**
    * Xem báo cáo thống kê (Statistic Reports)
* **Theo dõi:**
    * Xem danh sách các yêu cầu từ Seller (Seller Requests List)
* **Quản lý Seller:**
    * Duyệt/Từ chối các yêu cầu từ Seller (Seller Requests Approval Decisions)
* **Báo cáo:**
    * Xem báo cáo thống kê (Statistic Report)

### Seller (Người bán)

* **Quản lý Đơn hàng:**
    * Nhận danh sách đơn hàng cần xử lý (Order Lists for Processing)
    * Cập nhật trạng thái đơn hàng (Order Status Updates)
* **Quản lý Sản phẩm:**
    * Gửi yêu cầu chỉnh sửa sản phẩm (Product Modification Requests)

### Shipper (Người giao hàng)

* **Quản lý Vận đơn:**
    * Nhận đơn hàng được gán để giao (Assigned Order for delivery)
    * Xem chi tiết đơn hàng (Delivery Order Details)
    * Cập nhật trạng thái giao hàng (Update Shipping Status)

## Công nghệ sử dụng

* **Backend:**
    * Java 17
    * Spring Boot [Phiên bản, ví dụ: 3.5.5]
    * Spring Web MVC
    * Spring Data JPA 
    * Spring Security 
    * Lombok
    * OAuth2
    * PayOS
* **Database:**
    * PostgreSQL 
* **Frontend:**
    * Thymeleaf
* **Build Tool:**
    * Maven

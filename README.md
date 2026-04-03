# ⚙️ Building a Team Data Platform with SharePoint  

---
## 📖 Tổng quan
Dự án này ghi lại quá trình chuyển đổi từ hệ thống lưu trữ dữ liệu rời rạc, mang tính cá nhân (OneDrive) sang một môi trường làm việc cộng tác tập trung bằng SharePoint.

Dự án được triển khai trong team Merchandise với mục tiêu cải thiện khả năng truy cập dữ liệu, tăng hiệu quả làm việc nhóm và tối ưu workflow nội bộ.

---
## 🚨 Vấn đề

Trước khi triển khai:

- Dữ liệu bị **phân tán ở từng cá nhân**
- Việc chia sẻ file phụ thuộc vào:
    - Zalo
    - Email

Có một giải pháp tạm thời:

- Một người (leader) tạo folder OneDrive chung và share cho team

Tuy nhiên phát sinh nhiều vấn đề:

- Chạm giới hạn dung lượng (~1TB trên 1 tài khoản)
- Lưu trữ bị trùng lặp:
    - Máy cá nhân + OneDrive
- Thiếu minh bạch:
    - Không có hệ thống tracking task
    - Không theo dõi được tiến độ tổng thể
- Phụ thuộc vào việc nhắn tin thủ công để cập nhật công việc

---

## 🎯 Mục tiêu
- Chuyển từ **làm việc cá nhân → làm việc theo team**
- Xây dựng hệ thống **lưu trữ dữ liệu tập trung**
- Giảm phụ thuộc vào lưu trữ cá nhân (OneDrive)
- Cải thiện:
    - Khả năng cộng tác
    - Độ minh bạch công việc
    - Hiệu quả workflow

---

## 🧩 Giải pháp thực hiện
### 1. Quản lý dữ liệu tập trung

- Di chuyển toàn bộ dữ liệu sang **SharePoint Site**
- Thiết lập phân quyền truy cập:
    - Theo vai trò / thành viên
- Loại bỏ phụ thuộc vào storage cá nhân
### 2. Hệ thống tracking công việc

- Sử dụng **SharePoint Lists**:
    - Theo dõi task theo từng thành viên
    - Tracking tiến độ xử lý issue
- Giúp leader nắm tiến độ mà không cần hỏi thủ công
### 3. Workflow phê duyệt

- Xây dựng **quy trình approval**:
    - Nhân viên upload file / task trực tiếp lên hệ thống
    - Leader vào review và approve
- Thay thế:
    - Gửi email qua lại
    - Phản hồi thủ công
### 4. Thiết kế trang homepage

- Xây dựng **homepage riêng cho team**:
    - Hiển thị nhanh:
        - Folder thường dùng
        - File quan trọng
        - List chính
- Giảm thời gian tìm kiếm tài nguyên
### 5. Tài liệu & hướng dẫn

- Tạo các page nội bộ:
    - Hướng dẫn sử dụng SharePoint
    - Quy chuẩn cấu trúc folder
    - Cập nhật thông tin nội bộ

---

## 📊 Kết quả đạt được
- Cải thiện hiệu quả **làm việc nhóm**
- Giảm:
    - Email không cần thiết
    - Trao đổi thủ công
- Workflow nội bộ rõ ràng và mượt hơn
- Dữ liệu:
    - Được lưu tập trung
    - Dễ truy cập và quản lý
- Giảm tải dung lượng máy cá nhân

---
## 🧠 Bài học rút ra

- Công cụ không giải quyết vấn đề — **cách thiết kế hệ thống mới là yếu tố quyết định**
- Một hệ thống dữ liệu tốt cần:
    - Khả năng mở rộng
    - Tính minh bạch
    - Dễ sử dụng
- Minh bạch workflow quan trọng không kém dữ liệu
---

## 🛠️ Công cụ & Kỹ thuật sử dụng
- SharePoint (Site, Lists, Pages, Document Library)

---
## 👤 Vai trò của tôi

- Dẫn dắt toàn bộ quá trình chuyển đổi
- Thiết kế:
    - Cấu trúc dữ liệu
    - Workflow vận hành
- Triển khai:
    - SharePoint Lists
    - Approval workflow
- Xây dựng homepage & tài liệu hướng dẫn
- Hỗ trợ team adopt hệ thống mới

---

## 📸 Kết quả
### Hình ảnh
<p align="center">
  <img src="./images/homepage.PNG" alt="Preview kết quả" width="650">
</p>

---

## ✉️ Tác giả
**Tram Dang Tai**  
📍 Merchandise Data Analyst  
📧 [Liên hệ qua LinkedIn](https://www.linkedin.com/in/tramdangtai)

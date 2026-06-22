_Claude là llm, văn bản và hình anh làm đầu vào: dự đoán từ tiếp theo hợp lý nhất trong một câu, thông qua phương pháp học không giám sát, tinh chỉnh bằng học tăng cường
 + Cửa sổ ngữ cảnh lớn (200.000 token)
 + Xử lý nội dung dài và chuyên sâu
 + Viết mã và hỗ trợ học thuật hiệu quả

_PortgreSQL là một hệ quản trị csdl quan hệ và đối tượng, mã nguồn mở
 + Cung cấp nhiều kiểu dữ liệu: nguyên hàm, cấu trúc, hình học,...
 + Toàn vẹn dữ liệu: ràng buộc loại từ, Primary Keys, Foreign Keys
 + Khả năng mở rộng 

_Microservice: kiến trúc phần mềm chia hệ thống thành các dịch vụ nhỏ => chức năng riêng, giao tiếp qua API
 + Dễ mở rộng quy mô
 + Khả năng chịu lỗi cao: Khi một dịch vụ gặp sự cố, các dịch vụ khác vẫn hoạt động bình thường
 + Dễ hiểu và quản lý codebase
 + Triển khai độc lập: Các microservice có thể được cập nhật hoặc thay thế mà không cần ảnh hưởng đến các phần còn lại
 + Dễ kiểm thử

Người dùng -> FE -> BE (Microservice) -> PostgreSQL -> DL -> Model AI -> (Claude)x
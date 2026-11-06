# Agent Phiên âm Âm thanh & Video

Website giới thiệu công khai cho Agent phiên âm, tóm tắt và trích xuất tri thức từ âm thanh/video.

## Xem website

Sau khi bật GitHub Pages và workflow chạy thành công, trang có địa chỉ:

`https://<tên-tài-khoản>.github.io/<tên-repository>/`

## Nội dung và quyền riêng tư

- Đây là website tĩnh chỉ để xem và tương tác với dữ liệu mẫu viết sẵn.
- Không có backend, API key, kết nối Hermes/Feishu/Lark, chức năng gửi tệp hoặc gọi Agent.
- Nội dung mẫu được ghi nhãn mô phỏng, không phải kết quả xử lý thực tế.
- Kho này chỉ dành cho website trưng bày; không đưa tài liệu nguồn, bản chép riêng tư, log, bí mật hoặc thông tin xác thực vào đây.

## Triển khai

GitHub Actions trong `.github/workflows/deploy.yml` xuất bản nội dung gốc của kho lên GitHub Pages mỗi khi có cập nhật vào nhánh `main`. Trong repository, vào **Settings → Pages**, chọn **GitHub Actions** ở mục **Build and deployment**.

Workflow chỉ có quyền đọc nội dung kho và xuất bản GitHub Pages.


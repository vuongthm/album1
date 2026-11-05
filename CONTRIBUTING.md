# Đóng góp album ảnh/video

Mỗi bộ sưu tập có file `vi/<album-id>.md`, media ở `media/`. Chỉ góp nội dung bạn có quyền chia sẻ và đã được đồng ý xuất bản.

```markdown
---
id: album1-new-album
title: Tên bộ sưu tập
description: Một lời giới thiệu.
status: draft
items:
  - src: ../media/photo.jpg
    title: Chú thích ảnh
---

Giới thiệu bộ sưu tập.
```

ID album cần duy nhất. Caption không tự gán tên người, địa điểm hoặc sự kiện chưa được xác nhận. Để góp video, tham chiếu file MP4/WebM thích hợp thay cho ảnh; không đưa media quá lớn không liên quan vào PR.

## Gửi thay đổi

1. Tạo nhánh hoặc fork, sửa đúng nội dung và ngôn ngữ liên quan.
2. Giữ ID/slug cũ khi sửa bài; giữ chung ID hoặc `translationKey` giữa các bản dịch.
3. Kiểm tra cú pháp, code/ví dụ và nguồn tham khảo. Chỉ dùng media có quyền sử dụng.
4. Giữ bài mới ở trạng thái draft để review. Ghi rõ nội dung và cách kiểm tra trong PR.

Không đưa credential, nội dung cá nhân chưa được phép công khai, dependencies hoặc cache vào PR. Các thiết lập vận hành do maintainer quản lý; không cần yêu cầu khóa cá nhân để gửi đóng góp.

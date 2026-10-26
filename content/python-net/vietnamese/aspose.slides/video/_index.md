---
title: Video class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/video/
---
## Video lớp

Biểu diễn một hình ảnh được nhúng vào bản thuyết trình.

Kiểu Video cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`content_type`](/slides/python-net/vi/aspose.slides/video/content_type/) | Trả về loại MIME của video, được mã hoá trong [`Video.binary_data`](/slides/python-net/vi/aspose.slides/video/binary_data).<br/>            Chỉ đọc **str**. |
| [`binary_data`](/slides/python-net/vi/aspose.slides/video/binary_data/) | Trả về bản sao dữ liệu âm thanh. Trong trường hợp dữ liệu lớn, hãy cân nhắc sử dụng <br/>            [`Video.get_stream`](/slides/python-net/vi/aspose.slides/video/get_stream) để ngăn việc tải dữ liệu video không cần thiết vào bộ nhớ <br/>            hoặc thậm chí gây ra OutOfMemoryException.<br/>            Chỉ đọc **int**[]. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/vi/aspose.slides/video/get_stream/#) | Trả về Stream stream để đọc.<br/>            Sử dụng 'using' hoặc đóng stream sau khi sử dụng. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
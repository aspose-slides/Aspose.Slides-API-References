---
title: Audio class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/audio/
---
## Lớp Audio

Đại diện cho một tệp âm thanh được nhúng.

Kiểu Audio cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`content_type`](/slides/python-net/vi/aspose.slides/audio/content_type/) | Trả về loại MIME của một âm thanh, được mã hoá bằng [`Audio.binary_data`](/slides/python-net/vi/aspose.slides/audio/binary_data).<br/>            Chỉ-đọc **str**. |
| [`binary_data`](/slides/python-net/vi/aspose.slides/audio/binary_data/) | Trả về bản sao của dữ liệu âm thanh. Trong trường hợp dữ liệu lớn, hãy cân nhắc <br/>            việc sử dụng phương thức [`Audio.get_stream`](/slides/python-net/vi/aspose.slides/audio/get_stream) để ngăn chặn việc tải dữ liệu âm thanh<br/>            không cần thiết vào bộ nhớ hoặc thậm chí OutOfMemoryException.<br/>            Chỉ-đọc **int**[]. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/vi/aspose.slides/audio/get_stream/#) | Trả về Stream stream để đọc.<br/>            Sử dụng 'using' hoặc đóng stream sau khi dùng. |

### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
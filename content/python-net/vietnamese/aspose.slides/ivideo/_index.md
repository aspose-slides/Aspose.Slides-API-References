---
title: IVideo class
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/ivideo/
---
## Lớp IVideo

Biểu diễn một video được nhúng vào bản trình bày.

Kiểu IVideo mở ra các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`content_type`](/slides/python-net/vi/aspose.slides/ivideo/content_type/) | Trả về kiểu MIME của video, được mã hoá trong [`IVideo.binary_data`](/slides/python-net/vi/aspose.slides/ivideo/binary_data).<br/>            Chỉ đọc **str**. |
| [`binary_data`](/slides/python-net/vi/aspose.slides/ivideo/binary_data/) | Trả về bản sao dữ liệu âm thanh. Trong trường hợp lượng dữ liệu lớn, hãy cân nhắc sử dụng phương pháp [`IVideo.get_stream`](/slides/python-net/vi/aspose.slides/ivideo/get_stream) để ngăn việc tải dữ liệu video không cần thiết vào bộ nhớ hoặc thậm chí gây ra OutOfMemoryException.<br/>            Chỉ đọc **int**[]. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/vi/aspose.slides/ivideo/get_stream/#) | Trả về luồng Stream để đọc.<br/>            Sử dụng 'using' hoặc đóng luồng sau khi sử dụng. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
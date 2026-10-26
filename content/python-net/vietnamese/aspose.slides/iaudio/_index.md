---
title: IAudio class
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides/iaudio/
---
## IAudio lớp

Đại diện cho một tệp âm thanh được nhúng.

Kiểu IAudio cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`content_type`](/slides/python-net/vi/aspose.slides/iaudio/content_type/) | Trả về loại MIME của âm thanh, được mã hoá trong [`IAudio.binary_data`](/slides/python-net/vi/aspose.slides/iaudio/binary_data).<br/>            Chỉ đọc **str**. |
| [`binary_data`](/slides/python-net/vi/aspose.slides/iaudio/binary_data/) | Trả về bản sao dữ liệu của âm thanh. Trong trường hợp lượng dữ liệu lớn, hãy cân nhắc <br/>            sử dụng phương thức [`IAudio.get_stream`](/slides/python-net/vi/aspose.slides/iaudio/get_stream) để ngăn việc tải dữ liệu âm thanh không cần thiết vào bộ nhớ hoặc thậm chí gây ra OutOfMemoryException.<br/>            Chỉ đọc **int**[]. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/vi/aspose.slides/iaudio/get_stream/#) | Trả về Stream để đọc.<br/>            Sử dụng 'using' hoặc đóng stream sau khi sử dụng. |


### Xem thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
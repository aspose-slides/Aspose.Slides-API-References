---
title: PresentationInfo class
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentationinfo/
---
## PresentationInfo lớp

Thông tin về tệp trình chiếu

Kiểu PresentationInfo cung cấp các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`is_encrypted`](/slides/python-net/vi/aspose.slides/presentationinfo/is_encrypted/) | Trả về True nếu bản trình chiếu đã gắn kết được mã hoá, nếu không trả về False.<br/>            Chỉ đọc **bool**. |
| [`is_password_protected`](/slides/python-net/vi/aspose.slides/presentationinfo/is_password_protected/) | Trả về một giá trị cho biết liệu bản trình chiếu đã gắn kết có được bảo vệ bằng mật khẩu để mở hay không. |
| [`is_write_protected`](/slides/python-net/vi/aspose.slides/presentationinfo/is_write_protected/) | Trả về một giá trị cho biết liệu bản trình chiếu đã gắn kết có được bảo vệ chống ghi hay không. |
| [`load_format`](/slides/python-net/vi/aspose.slides/presentationinfo/load_format/) | Trả về định dạng của bản trình chiếu đã gắn kết.<br/>            Chỉ đọc [`LoadFormat`](/slides/python-net/vi/aspose.slides/loadformat). |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/vi/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Ghi bản trình chiếu đã gắn kết vào luồng. |
| [`write_binded_presentation(self, file)`](/slides/python-net/vi/aspose.slides/presentationinfo/write_binded_presentation/#str) | Ghi bản trình chiếu đã gắn kết vào tệp. |
| [`check_password(self, password)`](/slides/python-net/vi/aspose.slides/presentationinfo/check_password/#str) | Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở hay không. |
| [`check_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/presentationinfo/check_write_protection/#str) | Kiểm tra xem mật khẩu để sửa có đúng cho bản trình chiếu được bảo vệ chống ghi hay không. |
| [`read_document_properties(self)`](/slides/python-net/vi/aspose.slides/presentationinfo/read_document_properties/#) | Trả về các thuộc tính tài liệu của bản trình chiếu đã gắn kết. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/vi/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Cập nhật các thuộc tính của bản trình chiếu đã gắn kết. |

### Xem Thêm
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: IPresentationInfo class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/ipresentationinfo/
---
## IPresentationInfo lớp

Thông tin về tệp trình chiếu

Kiểu IPresentationInfo cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/vi/aspose.slides/ipresentationinfo/is_encrypted/) | Trả về True nếu bản trình chiếu đã liên kết được mã hóa, nếu không trả về False.<br/>            Chỉ đọc **bool**. |
| [`is_password_protected`](/slides/python-net/vi/aspose.slides/ipresentationinfo/is_password_protected/) | Trả về một giá trị cho biết bản trình chiếu đã liên kết có được bảo vệ bằng mật khẩu để mở hay không. |
| [`is_write_protected`](/slides/python-net/vi/aspose.slides/ipresentationinfo/is_write_protected/) | Trả về một giá trị cho biết bản trình chiếu đã liên kết có được bảo vệ ghi hay không. |
| [`load_format`](/slides/python-net/vi/aspose.slides/ipresentationinfo/load_format/) | Trả về định dạng của bản trình chiếu đã liên kết.<br/>            Chỉ đọc [`LoadFormat`](/slides/python-net/vi/aspose.slides/loadformat). |

## Phương thức

| Method | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/write_binded_presentation/#iorawiobase) | Ghi bản trình chiếu đã liên kết vào luồng. |
| [`write_binded_presentation(self, file)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/write_binded_presentation/#str) | Ghi bản trình chiếu đã liên kết vào tệp. |
| [`check_password(self, password)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/check_password/#str) | Kiểm tra xem mật khẩu có đúng cho bản trình chiếu được bảo vệ bằng mật khẩu mở hay không. |
| [`check_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/check_write_protection/#str) | Kiểm tra xem mật khẩu để sửa đổi có đúng cho bản trình chiếu được bảo vệ ghi không. |
| [`read_document_properties(self)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/read_document_properties/#) | Trả về các thuộc tính tài liệu của bản trình chiếu đã liên kết. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/vi/aspose.slides/ipresentationinfo/update_document_properties/#idocumentproperties) | Cập nhật các thuộc tính của bản trình chiếu đã liên kết. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: ProtectionManager class
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/protectionmanager/
---
## ProtectionManager lớp

Quản lý bảo vệ mật khẩu cho Presentation.

Kiểu ProtectionManager hiển thị các thành viên sau:

## Thuộc tính

| Thuộc tính | Mô tả |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/vi/aspose.slides/protectionmanager/encrypt_document_properties/) | Thuộc tính này có ý nghĩa nếu presentation được bảo vệ bằng mật khẩu.<br/>            Nếu true thì document properties được mã hóa trong tệp presentation.<br/>            Nếu false thì document properties là công khai trong khi presentation được mã hóa.<br/>            Đọc/ghi **bool**. |
| [`is_encrypted`](/slides/python-net/vi/aspose.slides/protectionmanager/is_encrypted/) | Lấy giá trị cho biết liệu thể hiện này có được mã hóa hay không.<br/>            Chỉ đọc **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/vi/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Thuộc tính này có ý nghĩa nếu tệp presentation được bảo vệ bằng mật khẩu và document <br/>            properties của tệp này là công khai.<br/>            Giá trị true có nghĩa là chỉ document properties được tải từ một tệp presentation đã mã hóa mà không dùng mật khẩu.<br/>            Giá trị false có nghĩa là toàn bộ presentation đã mã hóa được tải bằng mật khẩu đúng, không chỉ document properties được tải.<br/>            Nếu presentation không được mã hóa thì giá trị thuộc tính luôn là false.<br/>            Nếu document properties của một tệp đã mã hóa không phải là công khai thì giá trị thuộc tính luôn là false.<br/>            Nếu Presentation.EncryptDocumentProperties là true thì IsOnlyDocumentPropertiesLoaded <br/>            luôn là false.<br/>            Chỉ đọc **bool**. |
| [`is_write_protected`](/slides/python-net/vi/aspose.slides/protectionmanager/is_write_protected/) | Lấy giá trị cho biết liệu presentation này có được bảo vệ ghi hay không.<br/>            Chỉ đọc **bool**. |
| [`encryption_password`](/slides/python-net/vi/aspose.slides/protectionmanager/encryption_password/) | Lấy mật khẩu được sử dụng để mã hóa presentation.<br/>            Chỉ đọc **str**. |
| [`read_only_recommended`](/slides/python-net/vi/aspose.slides/protectionmanager/read_only_recommended/) | Lấy hoặc đặt khuyến nghị chỉ đọc.<br/>            Đọc/ghi **bool**. |

## Phương thức

| Phương thức | Mô tả |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/vi/aspose.slides/protectionmanager/encrypt/#str) | Mã hóa Presentation bằng mật khẩu đã chỉ định. |
| [`remove_encryption(self)`](/slides/python-net/vi/aspose.slides/protectionmanager/remove_encryption/#) | Xóa bỏ việc mã hóa. |
| [`set_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/protectionmanager/set_write_protection/#str) | Đặt bảo vệ ghi cho presentation này bằng mật khẩu đã chỉ định. |
| [`remove_write_protection(self)`](/slides/python-net/vi/aspose.slides/protectionmanager/remove_write_protection/#) | Xóa bỏ bảo vệ ghi cho presentation này. |
| [`check_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/protectionmanager/check_write_protection/#str) | Xác định liệu một presentation có được bảo vệ mật khẩu để sửa đổi hay không. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
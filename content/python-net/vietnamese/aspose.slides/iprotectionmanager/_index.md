---
title: IProtectionManager class
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides/iprotectionmanager/
---
## IProtectionManager lớp

Quản lý bảo vệ mật khẩu cho bài thuyết trình.

Kiểu IProtectionManager cung cấp các thành viên sau:

## Thuộc tính

| Property | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/vi/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Thuộc tính này có ý nghĩa nếu bài thuyết trình được bảo vệ bằng mật khẩu.<br/>Nếu đúng thì các thuộc tính tài liệu được mã hóa trong tệp bài thuyết trình.<br/>Nếu sai thì các thuộc tính tài liệu là công khai trong khi bài thuyết trình được mã hóa.<br/>Đọc/ghi **bool**. |
| [`is_encrypted`](/slides/python-net/vi/aspose.slides/iprotectionmanager/is_encrypted/) | Lấy giá trị cho biết liệu đối tượng này có được mã hóa hay không.<br/>Chỉ đọc **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/vi/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Thuộc tính này có ý nghĩa nếu tệp bài thuyết trình được bảo vệ bằng mật khẩu và các thuộc tính tài liệu của tệp này là công khai.<br/>Giá trị true có nghĩa là chỉ các thuộc tính tài liệu được tải từ tệp bài thuyết trình đã được mã hóa mà không cần mật khẩu.<br/>Giá trị false có nghĩa là toàn bộ bài thuyết trình được mã hóa được tải với việc sử dụng mật khẩu đúng, không chỉ các thuộc tính tài liệu được tải.<br/>Nếu bài thuyết trình không được mã hóa thì giá trị thuộc tính luôn là false.<br/>Nếu các thuộc tính tài liệu của tệp đã mã hóa không phải là công khai thì giá trị thuộc tính luôn là false.<br/>Nếu PresentationEx.EncryptDocumentProperties là true thì giá trị thuộc tính IsOnlyDocumentPropertiesLoaded luôn là false.<br/>Chỉ đọc **bool**. |
| [`is_write_protected`](/slides/python-net/vi/aspose.slides/iprotectionmanager/is_write_protected/) | Lấy giá trị cho biết liệu bài thuyết trình này có được bảo vệ ghi không.<br/>Chỉ đọc **bool**. |
| [`encryption_password`](/slides/python-net/vi/aspose.slides/iprotectionmanager/encryption_password/) | Trả về mật khẩu mã hóa.<br/>Chỉ đọc **str**. |
| [`read_only_recommended`](/slides/python-net/vi/aspose.slides/iprotectionmanager/read_only_recommended/) | Lấy hoặc đặt khuyến nghị chỉ đọc.<br/>Đọc/ghi **bool**. |

## Phương thức

| Method | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/vi/aspose.slides/iprotectionmanager/encrypt/#str) | Mã hóa bài thuyết trình bằng mật khẩu đã chỉ định. |
| [`remove_encryption(self)`](/slides/python-net/vi/aspose.slides/iprotectionmanager/remove_encryption/#) | Xóa bỏ việc mã hóa. |
| [`set_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/iprotectionmanager/set_write_protection/#str) | Đặt bảo vệ ghi cho bài thuyết trình này bằng mật khẩu đã chỉ định. |
| [`remove_write_protection(self)`](/slides/python-net/vi/aspose.slides/iprotectionmanager/remove_write_protection/#) | Xóa bảo vệ ghi cho bài thuyết trình này. |
| [`check_write_protection(self, password)`](/slides/python-net/vi/aspose.slides/iprotectionmanager/check_write_protection/#str) | Xác định xem một bài thuyết trình có được bảo vệ bằng mật khẩu để sửa đổi hay không. |

### Xem thêm
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
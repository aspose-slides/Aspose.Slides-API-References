---
title: check_write_protection method
second_title: Aspose.Slides cho Python qua Tham chiếu API .NET
description: 
type: docs
url: /vi/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Xác định liệu một bài thuyết trình có được bảo vệ bằng mật khẩu để sửa đổi hay không.

### Trả về

True nếu mật khẩu hợp lệ; nếu không, false.



```python
def check_write_protection(self, password):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| password | **str** | Mật khẩu để kiểm tra. |

### Ghi chú

1. Bạn nên kiểm tra thuộc tính [`ProtectionManager.is_write_protected`](/slides/python-net/vi/aspose.slides/protectionmanager/is_write_protected) trước khi gọi phương thức này.
2. Khi mật khẩu là None hoặc rỗng, phương thức này trả về false.



### Xem thêm
* lớp [`ProtectionManager`](/slides/python-net/vi/aspose.slides/protectionmanager)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
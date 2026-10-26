---
title: check_write_protection method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Xác định liệu bản trình chiếu có được bảo vệ bằng mật khẩu để sửa đổi hay không.

### Trả về

True nếu mật khẩu hợp lệ; ngược lại, false.



```python
def check_write_protection(self, password):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| password | **str** | Mật khẩu để kiểm tra. |

### Ghi chú

1. Bạn nên kiểm tra thuộc tính [`IProtectionManager.is_write_protected`](/slides/python-net/vi/aspose.slides/iprotectionmanager/is_write_protected) trước khi gọi phương thức này.
2. Khi mật khẩu là None hoặc rỗng, phương thức này trả về false.



### Xem thêm
* lớp [`IProtectionManager`](/slides/python-net/vi/aspose.slides/iprotectionmanager)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
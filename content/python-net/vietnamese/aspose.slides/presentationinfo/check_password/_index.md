---
title: check_password method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/presentationinfo/check_password/
weight: 10
---
## check_password(self, password) {#str}
Kiểm tra xem mật khẩu có đúng cho một bản trình chiếu được bảo vệ bằng mật khẩu mở hay không.

### Giải pháp trả về

True nếu bản trình chiếu được bảo vệ bằng mật khẩu mở và mật khẩu đúng, ngược lại là false.



```python
def check_password(self, password):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| password | **str** | Mật khẩu cần kiểm tra. |

### Ghi chú

Khi mật khẩu là None hoặc rỗng, phương thức này trả về false.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |
| **RuntimeError(Proxy error(NotSupportedException))** |  |



### Xem thêm
* lớp [`PresentationInfo`](/slides/python-net/vi/aspose.slides/presentationinfo)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: check_write_protection method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Kiểm tra xem mật khẩu để chỉnh sửa có đúng cho bản trình chiếu được bảo vệ ghi lại hay không.

### Trả về

True nếu bản trình chiếu được bảo vệ ghi lại và mật khẩu đúng. False nếu không.



```python
def check_write_protection(self, password):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| password | **str** | Mật khẩu để kiểm tra. |

### Ghi chú

1. Bạn nên kiểm tra thuộc tính [`IPresentationInfo.is_write_protected`](/slides/python-net/vi/aspose.slides/ipresentationinfo/is_write_protected) trước khi gọi phương thức này.
2. Khi password là None hoặc rỗng, phương thức này trả về false.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Xem thêm
* lớp [`IPresentationInfo`](/slides/python-net/vi/aspose.slides/ipresentationinfo)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
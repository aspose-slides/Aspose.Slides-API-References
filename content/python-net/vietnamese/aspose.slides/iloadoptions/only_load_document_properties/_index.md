---
title: only_load_document_properties property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties thuộc tính
            Thuộc tính này có ý nghĩa nếu tệp bản trình bày được bảo vệ bằng mật khẩu.
            Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ một tệp bản trình bày được mã hóa 
            và mật khẩu phải bị bỏ qua.
            Giá trị false có nghĩa là toàn bộ bản trình bày được mã hóa phải được tải bằng cách sử dụng mật khẩu đúng 
            mật khẩu.
            Nếu bản trình bày không được mã hóa thì giá trị thuộc tính luôn bị bỏ qua.
            Nếu các thuộc tính tài liệu của tệp được mã hóa không công khai và giá trị thuộc tính là true thì
            các thuộc tính tài liệu không thể được tải và sẽ ném ra ngoại lệ.
            Đọc-ghi **bool**.

### Định nghĩa:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Xem thêm
* lớp [`ILoadOptions`](/slides/python-net/vi/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
---
title: only_load_document_properties property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties thuộc tính
This property makes sense, if presentation file is password protected.
            Giá trị true có nghĩa là chỉ các thuộc tính tài liệu phải được tải từ một tệp bản trình chiếu được mã hóa và mật khẩu sẽ bị bỏ qua.
            Giá trị false có nghĩa là toàn bộ bản trình chiếu được mã hóa phải được tải bằng cách sử dụng mật khẩu đúng.
            Nếu bản trình chiếu không được mã hóa thì giá trị thuộc tính luôn bị bỏ qua.
            Nếu các thuộc tính tài liệu của tệp được mã hóa không công khai và giá trị thuộc tính là true thì các thuộc tính tài liệu không thể được tải và ngoại lệ sẽ được ném.
            Đọc/ghi **bool**.

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
* lớp [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
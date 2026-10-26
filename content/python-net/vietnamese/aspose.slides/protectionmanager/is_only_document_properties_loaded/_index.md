---
title: is_only_document_properties_loaded property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded thuộc tính
Thuộc tính này có ý nghĩa nếu tệp bản trình chiếu được bảo vệ bằng mật khẩu và các thuộc tính tài liệu của tệp này công khai.  
Giá trị true có nghĩa là chỉ các thuộc tính tài liệu được tải từ tệp bản trình chiếu đã được mã hoá mà không cần mật khẩu.  
Giá trị false có nghĩa là toàn bộ bản trình chiếu đã được mã hoá được tải với việc sử dụng mật khẩu đúng, không chỉ các thuộc tính tài liệu được tải.  
Nếu bản trình chiếu không được mã hoá thì giá trị thuộc tính luôn là false.  
Nếu các thuộc tính tài liệu của tệp đã mã hoá không công khai thì giá trị thuộc tính luôn là false.  
Nếu Presentation.EncryptDocumentProperties là true thì IsOnlyDocumentPropertiesLoaded thuộc tính luôn là false.  
Chỉ đọc **bool**.

### Định nghĩa:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Xem thêm
* lớp [`ProtectionManager`](/slides/python-net/vi/aspose.slides/protectionmanager)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
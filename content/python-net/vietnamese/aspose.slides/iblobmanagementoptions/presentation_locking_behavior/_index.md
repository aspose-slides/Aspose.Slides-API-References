---
title: presentation_locking_behavior property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior thuộc tính
Thuộc tính này xác định liệu một thể hiện của lớp Presentation có thể là chủ sở hữu của nguồn - tệp hoặc luồng trong suốt thời gian sống của thể hiện hay không. Nếu thể hiện là chủ sở hữu, nó sẽ khóa nguồn. Điều này giúp cải thiện việc tiêu thụ bộ nhớ và hiệu năng khi làm việc với BLOBs, nhưng nguồn (luồng hoặc tệp) không thể được thay đổi trong suốt thời gian sống của thể hiện Presentation. Đây là một ví dụ:

### Định nghĩa:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```

### Xem thêm
* lớp [`IBlobManagementOptions`](/slides/python-net/vi/aspose.slides/iblobmanagementoptions)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
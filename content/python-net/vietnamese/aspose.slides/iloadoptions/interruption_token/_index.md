---
title: interruption_token property
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token thuộc tính
Token để giám sát các yêu cầu ngắt.

            Token này quản lý toàn bộ vòng đời của đối tượng [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). Bất kỳ hoạt động chạy lâu nào, chẳng hạn như tải hoặc lưu bản trình bày, sẽ bị ngắt bằng cách gọi phương thức [`IInterruptionTokenSource.interrupt`](/slides/python-net/vi/aspose.slides/iinterruptiontokensource/interrupt) của [`IInterruptionTokenSource`](/slides/python-net/vi/aspose.slides/iinterruptiontokensource).

### Định nghĩa:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Xem thêm
* lớp [`IInterruptionTokenSource`](/slides/python-net/vi/aspose.slides/iinterruptiontokensource)
* lớp [`ILoadOptions`](/slides/python-net/vi/aspose.slides/iloadoptions)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
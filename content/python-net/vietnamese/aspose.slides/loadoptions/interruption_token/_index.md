---
title: interruption_token property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## thuộc tính interruption_token
Mã thông báo để giám sát các yêu cầu ngắt.
            
            Mã thông báo này quản lý toàn bộ vòng đời của đối tượng [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation). Bất kỳ hoạt động dài nào, chẳng hạn như tải hoặc lưu bản trình chiếu, sẽ bị ngắt bằng cách gọi phương thức [`InterruptionTokenSource.interrupt`](/slides/python-net/vi/aspose.slides/interruptiontokensource/interrupt) của [`InterruptionTokenSource`](/slides/python-net/vi/aspose.slides/interruptiontokensource).

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
* lớp [`InterruptionTokenSource`](/slides/python-net/vi/aspose.slides/interruptiontokensource)
* lớp [`IPresentation`](/slides/python-net/vi/aspose.slides/ipresentation)
* lớp [`LoadOptions`](/slides/python-net/vi/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)
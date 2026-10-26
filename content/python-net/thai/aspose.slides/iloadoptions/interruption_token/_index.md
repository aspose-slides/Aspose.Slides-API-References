---
title: interruption_token property
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET อ้างอิง API
description: 
type: docs
url: /th/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token คุณสมบัติ
The token to monitor for interruption requests.

This token manages the whole [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation) instance lifetime. Any long-running operation, such as presentation loading or saving, will be interrupted via calling of the [`IInterruptionTokenSource.interrupt`](/slides/python-net/th/aspose.slides/iinterruptiontokensource/interrupt) method of the [`IInterruptionTokenSource`](/slides/python-net/th/aspose.slides/iinterruptiontokensource).

### คำนิยาม:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### ดูเพิ่มเติม
* คลาส [`IInterruptionTokenSource`](/slides/python-net/th/aspose.slides/iinterruptiontokensource)
* คลาส [`ILoadOptions`](/slides/python-net/th/aspose.slides/iloadoptions)
* คลาส [`IPresentation`](/slides/python-net/th/aspose.slides/ipresentation)
* โมดูล [`aspose.slides`](/slides/python-net/th/aspose.slides)
* ไลบรารี [`Aspose.Slides`](/slides/python-net)
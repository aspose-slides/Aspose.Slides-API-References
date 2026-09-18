---
title: interruption_token property
second_title: Aspose.Slides Python için .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token özelliği
Kesinti isteklerini izlemek için token.

Bu token tüm [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örneğinin ömrünü yönetir. Sunumun yüklenmesi ya da kaydedilmesi gibi uzun süren bir işlem, [`InterruptionTokenSource`](/slides/python-net/tr/aspose.slides/interruptiontokensource)'nin [`InterruptionTokenSource.interrupt`](/slides/python-net/tr/aspose.slides/interruptiontokensource/interrupt) metodunun çağrılmasıyla kesintiye uğrar.

### Tanım:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Ayrıca Bakınız
* class [`InterruptionTokenSource`](/slides/python-net/tr/aspose.slides/interruptiontokensource)
* class [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* class [`LoadOptions`](/slides/python-net/tr/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
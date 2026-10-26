---
title: interruption_token property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token özelliği
Kesinti isteklerini izlemek için kullanılan token.
            
            Bu token, tüm [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation) örnek ömrünü yönetir. Sunum yükleme veya kaydetme gibi uzun süren herhangi bir işlem, [`IInterruptionTokenSource.interrupt`](/slides/python-net/tr/aspose.slides/iinterruptiontokensource/interrupt) metodunun [`IInterruptionTokenSource`](/slides/python-net/tr/aspose.slides/iinterruptiontokensource) üzerinden çağrılmasıyla kesintiye uğratılacaktır.

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
* sınıf [`IInterruptionTokenSource`](/slides/python-net/tr/aspose.slides/iinterruptiontokensource)
* sınıf [`ILoadOptions`](/slides/python-net/tr/aspose.slides/iloadoptions)
* sınıf [`IPresentation`](/slides/python-net/tr/aspose.slides/ipresentation)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)
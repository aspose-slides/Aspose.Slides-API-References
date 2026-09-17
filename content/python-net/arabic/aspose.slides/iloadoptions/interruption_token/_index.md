---
title: interruption_token property
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## خاصية interruption_token
الرمز لمراقبة طلبات الإيقاف.

            يدير هذا الرمز كامل عمر كائن [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation). أي عملية طويلة الأمد، مثل تحميل أو حفظ العرض التقديمي، سيتم إيقافها عن طريق استدعاء طريقة [`IInterruptionTokenSource.interrupt`](/slides/python-net/ar/aspose.slides/iinterruptiontokensource/interrupt) للـ [`IInterruptionTokenSource`](/slides/python-net/ar/aspose.slides/iinterruptiontokensource).

### التعريف:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```


### انظر أيضًا
* فئة [`IInterruptionTokenSource`](/slides/python-net/ar/aspose.slides/iinterruptiontokensource)
* فئة [`ILoadOptions`](/slides/python-net/ar/aspose.slides/iloadoptions)
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
---
title: add_from_html method
second_title: مرجع API لـ Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/paragraphcollection/add_from_html/
weight: 20
---
## add_from_html(self, text) {#str}
يضيف النص من سلسلة HTML المحددة إلى المجموعة.

```python
def add_from_html(self, text):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| text | **str** | نص HTML. |

## add_from_html(self, text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
يضيف النص من سلسلة HTML المحددة إلى المجموعة.

```python
def add_from_html(self, text, resolver, uri):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| text | **str** | نص HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء المُحَلِّل الذي يحل عناوين URI ويجلب الكائنات المشار إليها. |
| uri | **str** | URI لإضافة مستند HTML. يُستخدم لحل الروابط النسبية. |

### ملاحظات

قد يتسبب تحديد المُحَلِّل في إدخال ثغرة محتملة. استخدمه بحذر.

### انظر أيضًا
* فئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* فئة [`ParagraphCollection`](/slides/python-net/ar/aspose.slides/paragraphcollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
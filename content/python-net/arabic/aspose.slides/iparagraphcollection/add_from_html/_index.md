---
title: add_from_html method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/iparagraphcollection/add_from_html/
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
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد اتصال للـ Resolver الذي يحل عناوين URI ويجلب الكائنات المرجعية. |
| uri | **str** | URI لإضافة مستند HTML. يُستخدم لحل الروابط النسبية. |

### ملاحظات

قد يؤدي تحديد الـ resolver إلى إحداث ثغرة محتملة. استخدمه بحذر.



### انظر أيضًا
* فئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* فئة [`IParagraphCollection`](/slides/python-net/ar/aspose.slides/iparagraphcollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
---
title: add_from_html method
second_title: Aspose.Slides للبايثون عبر .NET – مرجع API
description: 
type: docs
url: /ar/aspose.slides/slidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### الإرجاع

الشرائح المضافة



```python
def add_from_html(self, html_text):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| html_text | **str** | Html لإضافته. |


## add_from_html(self, html_stream) {#iorawiobase}
ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### الإرجاع

الشرائح المضافة



```python
def add_from_html(self, html_stream):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | كائن Stream سيُستخدم كمصدر لملف HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### الإرجاع

الشرائح المضافة.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| html_text | **str** | Html لإضافته. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن استدعاء عكسي يستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### الإرجاع

الشرائح المضافة.



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| معامل | نوع | الوصف |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن استدعاء عكسي يستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |



### انظر أيضًا
* فئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* فئة [`SlideCollection`](/slides/python-net/ar/aspose.slides/slidecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
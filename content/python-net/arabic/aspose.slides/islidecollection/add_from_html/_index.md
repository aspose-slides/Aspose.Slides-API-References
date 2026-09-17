---
title: add_from_html method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/islidecollection/add_from_html/
weight: 30
---
## add_from_html(self, html_text) {#str}
يقوم بإنشاء شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### Returns
الشرائح المضافة



```python
def add_from_html(self, html_text):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | HTML للإضافة. |


## add_from_html(self, html_stream) {#iorawiobase}
يقوم بإنشاء شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### Returns
الشرائح المضافة



```python
def add_from_html(self, html_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | كائن Stream سيُستخدم كمصدر لملف HTML. |


## add_from_html(self, html_text, resolver, uri) {#str-asposeslidesimportingiexternalresourceresolver-str}
يقوم بإنشاء شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### Returns
الشرائح المضافة.



```python
def add_from_html(self, html_text, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_text | **str** | HTML للإضافة. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None سيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | مسار URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## add_from_html(self, html_stream, resolver, uri) {#iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
يقوم بإنشاء شرائح من نص HTML ويضيفها إلى نهاية المجموعة.

### Returns
الشرائح المضافة



```python
def add_from_html(self, html_stream, resolver, uri):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| html_stream | **io.RawIOBase** | كائن Stream سيُستخدم كمصدر لملف HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None سيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | مسار URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |



### See Also
* فئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* فئة [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
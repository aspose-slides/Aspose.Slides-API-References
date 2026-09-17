---
title: insert_from_html method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/slidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة



```python
def insert_from_html(self, index, html_text):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_text | **str** | HTML للإضافة. |


## insert_from_html(self, index, html_stream) {#int-iorawiobase}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة



```python
def insert_from_html(self, index, html_stream):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_stream | **io.RawIOBase** | كائن Stream سيتم استخدامه كمصدر لملف HTML. |


## insert_from_html(self, index, html_text, use_slide_with_index_as_start) {#int-str-bool}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة



```python
def insert_from_html(self, index, html_text, use_slide_with_index_as_start):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_text | **str** | HTML للإضافة. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **true** ، فسيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **false** ، فسيتم إضافة البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة



```python
def insert_from_html(self, index, html_stream, use_slide_with_index_as_start):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_stream | **io.RawIOBase** | كائن Stream سيتم استخدامه كمصدر لملف HTML. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **true** ، فسيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **false** ، فسيتم إضافة البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة.



```python
def insert_from_html(self, index, html_text, resolver, uri):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_text | **str** | HTML للإضافة. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد اتصال يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فستُتجاهل جميع الكائنات الخارجية. |
| uri | **str** | معرف URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة.



```python
def insert_from_html(self, index, html_stream, resolver, uri):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_stream | **io.RawIOBase** | كائن Stream سيتم استخدامه كمصدر لملف HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد اتصال يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فستُتجاهل جميع الكائنات الخارجية. |
| uri | **str** | معرف URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة.



```python
def insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_text | **str** | HTML للإضافة. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد اتصال يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فستُتجاهل جميع الكائنات الخارجية. |
| uri | **str** | معرف URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **true** ، فسيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **false** ، فسيتم إضافة البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
ينشئ شرائح من نص HTML ويُدرجها في المجموعة في الموضع المحدد.

### الإرجاع

الشرائح المضافة.



```python
def insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الموضع للإدراج. |
| html_stream | **io.RawIOBase** | كائن Stream سيتم استخدامه كمصدر لملف HTML. |
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد اتصال يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فستُتجاهل جميع الكائنات الخارجية. |
| uri | **str** | معرف URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة كيفية بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **true** ، فسيبدأ إدخال البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا كان **false** ، فسيتم إضافة البيانات إلى الشرائح التي تم إنشاؤها. |



### انظر أيضًا
* فئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* فئة [`SlideCollection`](/slides/python-net/ar/aspose.slides/slidecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
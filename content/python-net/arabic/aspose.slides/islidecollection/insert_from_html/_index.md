---
title: insert_from_html method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/islidecollection/insert_from_html/
weight: 80
---
## insert_from_html(self, index, html_text) {#int-str}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **true** ، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **false** ، فستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_stream, use_slide_with_index_as_start) {#int-iorawiobase-bool}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **true** ، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **false** ، فستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_text, resolver, uri) {#int-str-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## insert_from_html(self, index, html_stream, resolver, uri) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |


## insert_from_html(self, index, html_text, resolver, uri, use_slide_with_index_as_start) {#int-str-asposeslidesimportingiexternalresourceresolver-str-bool}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **true** ، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **false** ، فستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |


## insert_from_html(self, index, html_stream, resolver, uri, use_slide_with_index_as_start) {#int-iorawiobase-asposeslidesimportingiexternalresourceresolver-str-bool}
ينشئ شرائح من نص HTML ويضيفها إلى المجموعة في الموضع المحدد.

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
| resolver | [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver) | كائن رد نداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل None فسيتم تجاهل جميع الكائنات الخارجية. |
| uri | **str** | URI للـ HTML المحدد. يُستخدم لحل الروابط النسبية. |
| use_slide_with_index_as_start | **bool** | تحدد هذه العلامة طريقة بدء الإدراج: من شريحة جديدة أو من الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **true** ، فسيبدأ إدراج البيانات من مساحة فارغة على الشريحة ذات الفهرس المحدد.<br/><br/>            إذا **false** ، فستُضاف البيانات إلى الشرائح التي تم إنشاؤها. |



### انظر أيضًا
* الفئة [`IExternalResourceResolver`](/slides/python-net/ar/aspose.slides.importing/iexternalresourceresolver)
* الفئة [`ISlideCollection`](/slides/python-net/ar/aspose.slides/islidecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
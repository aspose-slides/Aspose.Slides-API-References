---
title: save method
second_title: Aspose.Slides للغة Python عبر مرجع API لـ .NET
description: 
type: docs
url: /ar/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
يحفظ جميع الشرائح في عرض تقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML markup.


```python
def save(self, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions) | خيارات تنسيق XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.


```python
def save(self, fname, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة.


```python
def save(self, stream, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}



```python
def save(self, fname, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) |  |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالصيغة المحددة ومع خيارات إضافية.


```python
def save(self, stream, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | إذا حاولت حفظ ملف مشفر بتنسيق غير Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.


```python
def save(self, fname, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون المتغيّر stream أو slides بقيمة None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات.


```python
def save(self, stream, slides, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.


```python
def save(self, fname, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالصيغة المحددة مع الحفاظ على أرقام الصفحات.


```python
def save(self, stream, slides, format, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة بمواقع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون المتغيّر stream أو slides بقيمة None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |



### انظر أيضًا
* فئة [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions)
* فئة [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* تعداد [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
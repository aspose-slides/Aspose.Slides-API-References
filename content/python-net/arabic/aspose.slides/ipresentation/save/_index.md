---
title: save method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ipresentation/save/
weight: 80
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
يحفظ جميع شرائح العرض التقديمي في مجموعة من الملفات التي تمثل تنسيق XAML.


```python
def save(self, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions) | خيارات تنسيق XAML. |


## save(self, fname, format) {#str-asposeslidesexportsaveformat}
يحفظ جميع شرائح العرض التقديمي في ملف بالتنسيق المحدد.


```python
def save(self, fname, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |


## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
يحفظ جميع شرائح العرض التقديمي في دفق بالتنسيق المحدد.


```python
def save(self, stream, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |


## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع شرائح العرض التقديمي في ملف بالتنسيق المحدد ومع خيارات إضافية.


```python
def save(self, fname, format, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |


## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع شرائح العرض التقديمي في دفق بالتنسيق المحدد ومع خيارات إضافية.


```python
def save(self, stream, format, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | إذا حاولت حفظ ملف مشفر في <br/>            تنسيق غير Office 2007-2010 |


## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة من العرض التقديمي في ملف بالتنسيق المحدد.


```python
def save(self, fname, slides, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة بأرقام مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة المتغيّر stream أو slides هي None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة من العرض التقديمي في دفق بالتنسيق المحدد.


```python
def save(self, stream, slides, format):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإخراج. |
| slides | **List[int]** | مصفوفة بأرقام مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة المتغيّر stream أو slides هي None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة من العرض التقديمي في ملف بالتنسيق المحدد.


```python
def save(self, fname, slides, format, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | المسار إلى الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة بأرقام مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة المتغيّر stream أو slides هي None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة من العرض التقديمي في دفق بالتنسيق المحدد.


```python
def save(self, stream, slides, format, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | دفق الإخراج. |
| slides | **List[int]** | مصفوفة بأرقام مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة المتغيّر stream أو slides هي None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغيّر slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |



### انظر أيضًا
* الفئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* الفئة [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions)
* الفئة [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions)
* التعداد [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
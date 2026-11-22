---
title: save method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ipresentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
يحفظ جميع الشرائح في عرض تقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML markup.

```python
def save(self, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions) | خيارات تنسيق XAML. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد.

```python
def save(self, fname, format):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```python
def save(self, stream, format):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع الشرائح في عرض تقديمي إلى ملف بالتنسيق المحدد ومع خيارات إضافية.

```python
def save(self, fname, format, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع الشرائح في عرض تقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

```python
def save(self, stream, format, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | إذا حاولت حفظ ملف مشفر في تنسيق غير Office 2007-2010 <br/>            none Office 2007-2010 format |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد.

```python
def save(self, fname, slides, format):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل stream أو slides هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```python
def save(self, stream, slides, format):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل stream أو slides هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة في عرض تقديمي إلى ملف بالتنسيق المحدد.

```python
def save(self, fname, slides, format, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل stream أو slides هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة في عرض تقديمي إلى تدفق بالتنسيق المحدد.

```python
def save(self, stream, slides, format, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، تبدأ من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| Exception | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما يكون معامل stream أو slides هو None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي معامل slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### أنظر أيضًا
* فئة [`IPresentation`](/slides/python-net/ar/aspose.slides/ipresentation)
* فئة [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions)
* فئة [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions)
* تعداد [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
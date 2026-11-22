---
title: save method
second_title: مرجع API لـ Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/presentation/save/
weight: 100
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
يحفظ جميع شرائح العرض التقديمي إلى مجموعة من الملفات التي تمثل ترميز XAML markup.

```python
def save(self, options):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions) | خيارات تنسيق XAML. |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
يحفظ جميع شرائح العرض التقديمي إلى ملف بالتنسيق المحدد.

```python
def save(self, fname, format):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد.

```python
def save(self, stream, format):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ جميع شرائح العرض التقديمي إلى تدفق بالتنسيق المحدد ومع خيارات إضافية.

```python
def save(self, stream, format, options):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | إذا حاولت حفظ ملف مشفر في <br/>            تنسيق غير Office 2007-2010 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```python
def save(self, fname, slides, format):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة stream أو slides فارغة (None). |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغير slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```python
def save(self, stream, slides, format):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة من العرض التقديمي إلى ملف بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```python
def save(self, fname, slides, format, options):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| fname | **str** | مسار الملف الذي تم إنشاؤه. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
يحفظ الشرائح المحددة من العرض التقديمي إلى تدفق بالتنسيق المحدد مع الحفاظ على أرقام الصفحات.

```python
def save(self, stream, slides, format, options):
    ...
```

| المعلمة | النوع | الوصف |
| :- | :- | :- |
| stream | **io.RawIOBase** | تدفق الإخراج. |
| slides | **List[int]** | مصفوفة تحتوي على مواضع الشرائح، بدءًا من 1. |
| format | [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat) | تنسيق البيانات المصدرة. |
| options | [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions) | خيارات تنسيق إضافية. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | عندما تكون قيمة stream أو slides فارغة (None). |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | عندما يحتوي المتغير slides على أرقام صفحات غير صحيحة. |
| **RuntimeError(Proxy error(InvalidOperationException))** | عند استخدام SaveFormat غير مدعوم، مثل PPTX، PPTM، PPSX، PPSM، POTX، POTM، PPT، ODP. |

### انظر أيضًا
* الفئة [`ISaveOptions`](/slides/python-net/ar/aspose.slides.export/isaveoptions)
* الفئة [`IXamlOptions`](/slides/python-net/ar/aspose.slides.export.xaml/ixamloptions)
* الفئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* تعداد [`SaveFormat`](/slides/python-net/ar/aspose.slides.export/saveformat)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
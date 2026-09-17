---
title: to_jpeg method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فسيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg" حيث N هو رقم الشريحة.

```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فسيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg" حيث N هو رقم الشريحة.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل |
| output_file_name | **str** | اسم ملف الإخراج. |
| image_size | **aspose.slides.Size** | حجم كل صورة مُولَّدة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.jpeg"، فسيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg" حيث N هو رقم الشريحة.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |
| scale | **float** | عامل التحجيم المطبق على صور الإخراج نسبةً إلى حجم الشريحة الأصلي. |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات العرض. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### انظر أيضًا
* الفئة [`Convert`](/slides/python-net/ar/aspose.slides.lowcode/convert)
* الفئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* الفئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* الوحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* المكتبة [`Aspose.Slides`](/slides/python-net)
---
title: to_tiff method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بصيغة TIFF.  
إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff"، فسيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.tiff"، حيث N هو رقم الشريحة.

```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
يقوم بتحويل العرض التقديمي المدخل إلى صيغة TIFF مع خيارات مخصصة.  
إذا تم إعطاء اسم ملف الإخراج كـ "myPath/myFilename.tiff" وكانت القيمة `multipage` هي `false`، فسيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.tiff"، حيث N هو رقم الشريحة.  
إلا إذا كانت القيمة `multipage` هي `true`، فإن النتيجة ستكون مستند "myPath/myFilename.tiff" متعدد الصفحات.

```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |
| options | [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions) | خيارات حفظ TIFF. |
| multipage | **bool** | يحدد ما إذا كان مستند TIFF المولّد يجب أن يكون متعدد الصفحات. |

### استثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### انظر أيضًا
* فئة [`Convert`](/slides/python-net/ar/aspose.slides.lowcode/convert)
* فئة [`ITiffOptions`](/slides/python-net/ar/aspose.slides.export/itiffoptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)
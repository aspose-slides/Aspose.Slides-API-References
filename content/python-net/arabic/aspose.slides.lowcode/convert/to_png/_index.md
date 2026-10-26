---
title: to_png method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG.  
            إذا تم توفير اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المُدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG.  
            إذا تم توفير اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المُدخل |
| output_file_name | **str** | اسم ملف الإخراج. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم كل صورة مُولدة. |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بصيغة PNG.  
            إذا تم توفير اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيتم حفظ النتيجة كمجموعة من الملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المُدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |
| scale | **float** | عامل التحجيم المطبق على الصور المُخرجة بالنسبة لحجم الشريحة الأصلي. |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |

### الاستثناءات

| استثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### انظر أيضًا
* فئة [`Convert`](/slides/python-net/ar/aspose.slides.lowcode/convert)
* فئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* فئة [`Size`](/slides/python-net/ar/aspose.slides/size)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)
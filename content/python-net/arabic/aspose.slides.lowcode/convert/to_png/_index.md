---
title: to_png method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيُحفظ الناتج كمجموعة من ملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيُحفظ الناتج كمجموعة من ملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل |
| output_file_name | **str** | اسم ملف الإخراج. |
| image_size | **aspose.slides.Size** | حجم كل صورة مُولَّدة. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
يحوِّل العرض التقديمي المدخل إلى مجموعة من الصور بتنسيق PNG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.png"، 
            سيُحفظ الناتج كمجموعة من ملفات "myPath/myFilename_N.png"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |
| scale | **float** | عامل القياس المطبَّق على الصور الناتجة نسبةً إلى حجم الشريحة الأصلي. |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات العرض. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### انظر أيضًا
* فئة [`Convert`](/slides/python-net/ar/aspose.slides.lowcode/convert)
* فئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)
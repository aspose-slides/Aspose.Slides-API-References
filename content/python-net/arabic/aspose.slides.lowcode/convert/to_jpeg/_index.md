---
title: to_jpeg method
second_title: مرجع Aspose.Slides للغة بايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.jpeg"،  
            سيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_jpeg(pres, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.jpeg"،  
            سيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل |
| output_file_name | **str** | اسم ملف الإخراج. |
| image_size | [`Size`](/slides/python-net/ar/aspose.slides/size) | حجم كل صورة مُولَّدة. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
يقوم بتحويل العرض التقديمي المدخل إلى مجموعة من صور بتنسيق JPEG.  
            إذا تم تحديد اسم ملف الإخراج كـ "myPath/myFilename.jpeg"،  
            سيتم حفظ النتيجة كمجموعة من ملفات "myPath/myFilename_N.jpeg"، حيث N هو رقم الشريحة.


```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/ar/aspose.slides/presentation) | العرض التقديمي المدخل. |
| output_file_name | **str** | اسم ملف الإخراج. |
| scale | **float** | معامل التحجيم المطبق على الصور الناتجة بالنسبة لحجم الشريحة الأصلي. |
| options | [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions) | خيارات التصيير. |

### الاستثناءات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### أنظر أيضًا
* فئة [`Convert`](/slides/python-net/ar/aspose.slides.lowcode/convert)
* فئة [`IRenderingOptions`](/slides/python-net/ar/aspose.slides.export/irenderingoptions)
* فئة [`Presentation`](/slides/python-net/ar/aspose.slides/presentation)
* فئة [`Size`](/slides/python-net/ar/aspose.slides/size)
* وحدة [`aspose.slides.lowcode`](/slides/python-net/ar/aspose.slides.lowcode)
* مكتبة [`Aspose.Slides`](/slides/python-net)
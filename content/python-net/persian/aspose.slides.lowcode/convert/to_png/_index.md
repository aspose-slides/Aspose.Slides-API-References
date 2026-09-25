---
title: to_png method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.

```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی. |
| output_file_name | **str** | نام فایل خروجی. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_png(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.

```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی |
| output_file_name | **str** | نام فایل خروجی. |
| image_size | [`Size`](/slides/python-net/fa/aspose.slides/size) | اندازهٔ هر تصویر تولید شده. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
Converts the input presentation to a set of PNG format images.  
            If the output file name is given as "myPath/myFilename.png", 
            the result will be saved as a set of "myPath/myFilename_N.png" files, where N is a slide number.

```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی. |
| output_file_name | **str** | نام فایل خروجی. |
| scale | **float** | ضریب مقیاس که روی تصاویر خروجی نسبت به اندازهٔ اسلاید اصلی اعمال می‌شود. |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### مرتبط
* کلاس [`Convert`](/slides/python-net/fa/aspose.slides.lowcode/convert)
* کلاس [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* کلاس [`Size`](/slides/python-net/fa/aspose.slides/size)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
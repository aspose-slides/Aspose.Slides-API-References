---
title: to_jpeg method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.lowcode/convert/to_jpeg/
weight: 20
---
## to_jpeg(pres, output_file_name) {#presentation-str}
ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند.  
اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.jpeg" ذخیره می‌شود که در آن N شمارهٔ اسلاید است.

```python
@staticmethod
def to_jpeg(pres, output_file_name):
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

## to_jpeg(pres, output_file_name, image_size) {#presentation-str-asposeslidessize}
ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند.  
اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.jpeg" ذخیره می‌شود که در آن N شمارهٔ اسلایд است.

```python
@staticmethod
def to_jpeg(pres, output_file_name, image_size):
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

## to_jpeg(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت JPEG تبدیل می‌کند.  
اگر نام فایل خروجی به صورت "myPath/myFilename.jpeg" داده شود، نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.jpeg" ذخیره می‌شود که در آن N شمارهٔ اسلاید است.

```python
@staticmethod
def to_jpeg(pres, output_file_name, scale, options):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی. |
| output_file_name | **str** | نام فایل خروجی. |
| scale | **float** | ضریب مقیاس اعمال‌شده بر روی تصاویر خروجی نسبت به اندازهٔ اصلی اسلاید. |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |

### موارد مرتبط
* کلاس [`Convert`](/slides/python-net/fa/aspose.slides.lowcode/convert)
* کلاس [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* کلاس [`Size`](/slides/python-net/fa/aspose.slides/size)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
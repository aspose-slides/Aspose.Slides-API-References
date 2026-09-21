---
title: to_png method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.lowcode/convert/to_png/
weight: 40
---
## to_png(pres, output_file_name) {#presentation-str}
ارائه ورودی را به مجموعه‌ای از تصاویر با فرمت PNG تبدیل می‌کند.  
            اگر نام فایل خروجی به صورت "myPath/myFilename.png" مشخص شود،  
            نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که N شماره اسلاید است.


```python
@staticmethod
def to_png(pres, output_file_name):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائه ورودی. |
| output_file_name | **str** | نام فایل خروجی. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, image_size) {#presentation-str-asposepydrawingsize}
ارائه ورودی را به مجموعه‌ای از تصاویر با فرمت PNG تبدیل می‌کند.  
            اگر نام فایل خروجی به صورت "myPath/myFilename.png" مشخص شود،  
            نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که N شماره اسلاید است.


```python
@staticmethod
def to_png(pres, output_file_name, image_size):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائه ورودی. |
| output_file_name | **str** | نام فایل خروجی. |
| image_size | **aspose.slides.Size** | اندازه هر تصویر تولید شده. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_png(pres, output_file_name, scale, options) {#presentation-str-float-asposeslidesexportirenderingoptions}
ارائه ورودی را به مجموعه‌ای از تصاویر با فرمت PNG تبدیل می‌کند.  
            اگر نام فایل خروجی به صورت "myPath/myFilename.png" مشخص شود،  
            نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.png" ذخیره می‌شود که N شماره اسلاید است.


```python
@staticmethod
def to_png(pres, output_file_name, scale, options):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائه ورودی. |
| output_file_name | **str** | نام فایل خروجی. |
| scale | **float** | عامل مقیاس‌گذاری اعمال شده بر تصاویر خروجی نسبت به اندازه اسلاید اصلی. |
| options | [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions) | گزینه‌های رندرینگ. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### موارد مرتبط
* کلاس [`Convert`](/slides/python-net/fa/aspose.slides.lowcode/convert)
* کلاس [`IRenderingOptions`](/slides/python-net/fa/aspose.slides.export/irenderingoptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
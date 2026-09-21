---
title: to_tiff method
second_title: Aspose.Slides برای Python از طریق .NET API Reference
description: 
type: docs
url: /fa/aspose.slides.lowcode/convert/to_tiff/
weight: 60
---
## to_tiff(pres, output_file_name) {#presentation-str}
ارائهٔ ورودی را به مجموعه‌ای از تصاویر با فرمت TIFF تبدیل می‌کند.  
            اگر نام فایل خروجی به صورت "myPath/myFilename.tiff" تعیین شود,  
            نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.tiff" ذخیره می‌شود، که N شمارهٔ اسلاید است.


```python
@staticmethod
def to_tiff(pres, output_file_name):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی. |
| output_file_name | **str** | نام فایل خروجی. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |


## to_tiff(pres, output_file_name, options, multipage) {#presentation-str-asposeslidesexportitiffoptions-bool}
ارائهٔ ورودی را با گزینه‌های سفارشی به فرمت TIFF تبدیل می‌کند.  
            اگر نام فایل خروجی به صورت "myPath/myFilename.tiff" باشد و `multipage` برابر `false` باشد,  
            نتیجه به‌صورت مجموعه‌ای از فایل‌های "myPath/myFilename_N.tiff" ذخیره می‌شود، که N شمارهٔ اسلاید است.  
            در غیر این صورت، اگر `multipage` برابر `true` باشد، نتیجه یک مستند چندصفحهٔ "myPath/myFilename.tiff" خواهد بود.


```python
@staticmethod
def to_tiff(pres, output_file_name, options, multipage):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| pres | [`Presentation`](/slides/python-net/fa/aspose.slides/presentation) | ارائهٔ ورودی. |
| output_file_name | **str** | نام فایل خروجی. |
| options | [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions) | گزینه‌های ذخیره‌سازی TIFF. |
| multipage | **bool** | مشخّص می‌کند که آیا سند TIFF تولید شده باید چندصفحه باشد یا نه. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** |  |



### موارد مرتبط
* کلاس [`Convert`](/slides/python-net/fa/aspose.slides.lowcode/convert)
* کلاس [`ITiffOptions`](/slides/python-net/fa/aspose.slides.export/itiffoptions)
* کلاس [`Presentation`](/slides/python-net/fa/aspose.slides/presentation)
* ماژول [`aspose.slides.lowcode`](/slides/python-net/fa/aspose.slides.lowcode)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
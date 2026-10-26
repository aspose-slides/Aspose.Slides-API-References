---
title: add_section_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
یک قاب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) جدید ایجاد شده.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | **float** | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ای که توسط قاب Section Zoom ارجاع شده است؛ <br/><br/>            باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع شده متعلق به ارائهٔ جاری نباشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) جدید ایجاد شده.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | **float** | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ای که توسط قاب Section Zoom ارجاع شده است؛ <br/><br/>            باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)ی که در قاب Section Zoom نمایش داده می‌شود. |

### استثناها

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع شده متعلق به ارائهٔ جاری نباشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* کلاس [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
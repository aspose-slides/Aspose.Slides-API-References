---
title: add_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) جدید ساخته‌شده.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب Zoom جدید، بر حسب نقاط. |
| y | **float** | مختصات y قاب Zoom جدید، بر حسب نقاط. |
| width | **float** | عرض قاب Zoom جدید، بر حسب نقاط. |
| height | **float** | ارتفاع قاب Zoom جدید، بر حسب نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) مورد ارجاع توسط قاب Zoom؛<br/><br/>            باید متعلق به این ارائه باشد. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | اگر اسلاید ارجاع‌شده متعلق به ارائهٔ جاری نباشد، پرتاب می‌شود. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) جدید ساخته‌شده.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x قاب Zoom جدید، بر حسب نقاط. |
| y | **float** | مختصات y قاب Zoom جدید، بر حسب نقاط. |
| width | **float** | عرض قاب Zoom جدید، بر حسب نقاط. |
| height | **float** | ارتفاع قاب Zoom جدید، بر حسب نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) مورد ارجاع توسط قاب Zoom؛<br/><br/>            باید متعلق به این ارائه باشد. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر برای اسلاید ارجاع‌شده [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | اگر اسلاید ارجاع‌شده متعلق به ارائهٔ جاری نباشد، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
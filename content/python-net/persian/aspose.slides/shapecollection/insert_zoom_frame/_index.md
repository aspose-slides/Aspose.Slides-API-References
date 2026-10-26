---
title: insert_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
یک قاب Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده درج می‌نماید.

### بازگشت

قاب جدید ایجاد شده [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | **float** | مختصات x قاب Zoom جدید، به نقاط. |
| y | **float** | مختصات y قاب Zoom جدید، به نقاط. |
| width | **float** | عرض قاب Zoom جدید، به نقاط. |
| height | **float** | ارتفاع قاب Zoom جدید، به نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید [`ISlide`](/slides/python-net/fa/aspose.slides/islide) که توسط قاب Zoom ارجاع می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که اسلاید ارجاع شده متعلق به ارائه فعلی نباشد، پرتاب می‌شود. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
یک قاب Zoom جدید با تصویر از پیش تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در شاخص مشخص شده درج می‌نماید.

### بازگشت

قاب جدید ایجاد شده [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | **float** | مختصات x قاب Zoom جدید، به نقاط. |
| y | **float** | مختصات y قاب Zoom جدید، به نقاط. |
| width | **float** | عرض قاب Zoom جدید، به نقاط. |
| height | **float** | ارتفاع قاب Zoom جدید، به نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | اسلاید [`ISlide`](/slides/python-net/fa/aspose.slides/islide) که توسط قاب Zoom ارجاع می‌شود. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر برای اسلاید [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که اسلاید ارجاع شده متعلق به ارائه فعلی نباشد، پرتاب می‌شود. |



### مراجع مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
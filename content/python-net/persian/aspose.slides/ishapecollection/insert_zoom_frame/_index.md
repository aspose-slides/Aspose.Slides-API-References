---
title: insert_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
یک Zoom frame جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص شده درج می‌سازد.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) تازه ایجاد شده.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | ایندکس صفر-پایه‌ای که Zoom frame در آن درج می‌شود. |
| x | **float** | مختصات x Zoom frame جدید، بر حسب نقاط. |
| y | **float** | مختصات y Zoom frame جدید، بر حسب نقاط. |
| width | **float** | عرض Zoom frame جدید، بر حسب نقاط. |
| height | **float** | ارتفاع Zoom frame جدید، بر حسب نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) مرتبط با Zoom frame. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | اگر اسلاید مرجع به ارائه فعلی تعلق نداشته باشد، پرتاب می‌شود. |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
یک Zoom frame جدید با تصویر پیش‌تعریف شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص شده درج می‌سازد.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) تازه ایجاد شده.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | ایندکس صفر-پایه‌ای که Zoom frame در آن درج می‌شود. |
| x | **float** | مختصات x Zoom frame جدید، بر حسب نقاط. |
| y | **float** | مختصات y Zoom frame جدید، بر حسب نقاط. |
| width | **float** | عرض Zoom frame جدید، بر حسب نقاط. |
| height | **float** | ارتفاع Zoom frame جدید، بر حسب نقاط. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) مرتبط با Zoom frame. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر برای اسلاید مرجع [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | اگر اسلاید مرجع به ارائه فعلی تعلق نداشته باشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
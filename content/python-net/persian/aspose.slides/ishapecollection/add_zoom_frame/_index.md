---
title: add_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET - مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) تازه ایجاد شده.



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| x | **float** | مختصات x قاب زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب زوم جدید، بر حسب نقطه. |
| width | **float** | عرض قاب زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب زوم جدید، بر حسب نقطه. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) ای که توسط قاب زوم ارجاع می‌شود؛<br/><br/> باید به این ارائه تعلق داشته باشد. |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که اسلاید ارجاع‌شده به ارائهٔ جاری تعلق نداشته باشد، پرتاب می‌شود. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
یک قاب زوم جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

### بازگشت

[`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe) تازه ایجاد شده.



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| پارامتر | نوع | توضیحات |
| :- | :- | :- |
| x | **float** | مختصات x قاب زوم جدید، بر حسب نقطه. |
| y | **float** | مختصات y قاب زوم جدید، بر حسب نقطه. |
| width | **float** | عرض قاب زوم جدید، بر حسب نقطه. |
| height | **float** | ارتفاع قاب زوم جدید، بر حسب نقطه. |
| slide | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) | [`ISlide`](/slides/python-net/fa/aspose.slides/islide) ای که توسط قاب زوم ارجاع می‌شود؛<br/><br/> باید به این ارائه تعلق داشته باشد. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویر برای اسلاید ارجاع‌شده [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage). |

### استثناها

| استثنا | توضیحات |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که اسلاید ارجاع‌شده به ارائهٔ جاری تعلق نداشته باشد، پرتاب می‌شود. |



### همچنین ببینید
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* کلاس [`ISlide`](/slides/python-net/fa/aspose.slides/islide)
* کلاس [`IZoomFrame`](/slides/python-net/fa/aspose.slides/izoomframe)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
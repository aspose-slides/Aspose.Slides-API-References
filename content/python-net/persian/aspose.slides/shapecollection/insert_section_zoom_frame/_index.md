---
title: insert_section_zoom_frame method
second_title: مرجع API Aspose.Slides برای Python از طریق .NET
description: 
type: docs
url: /fa/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
یک فریم Section Zoom جدید ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص‌شده درج می‌کند.

### Returns

فریم تازه ایجاد‌شده [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایه‌ای که فریم Section Zoom در آن درج می‌شود. |
| x | **float** | مختصات x فریم جدید Section Zoom، برحسب نقطه. |
| y | **float** | مختصات y فریم جدید Section Zoom، برحسب نقطه. |
| width | **float** | عرض فریم جدید Section Zoom، برحسب نقطه. |
| height | **float** | ارتفاع فریم جدید Section Zoom، برحسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ارجاع‌شده توسط فریم Section Zoom;<br/><br/>            باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

### Exceptions

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورت اینکه بخش ارجاع‌شده متعلق به ارائهٔ کنونی نباشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
یک فریم Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص‌شده درج می‌کند.

### Returns

فریم تازه ایجاد‌شده [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | اندیس صفر-پایه‌ای که فریم Section Zoom در آن درج می‌شود. |
| x | **float** | مختصات x فریم جدید Section Zoom، برحسب نقطه. |
| y | **float** | مختصات y فریم جدید Section Zoom، برحسب نقطه. |
| width | **float** | عرض فریم جدید Section Zoom، برحسب نقطه. |
| height | **float** | ارتفاع فریم جدید Section Zoom، برحسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ارجاع‌شده توسط فریم Section Zoom;<br/><br/>            باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویری که در داخل فریم Section Zoom نمایش داده می‌شود. |

### Exceptions

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورت اینکه بخش ارجاع‌شده متعلق به ارائهٔ کنونی نباشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |



### موارد مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* کلاس [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe)
* کلاس [`ShapeCollection`](/slides/python-net/fa/aspose.slides/shapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
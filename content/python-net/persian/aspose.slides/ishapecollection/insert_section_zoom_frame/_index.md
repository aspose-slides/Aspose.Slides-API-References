---
title: insert_section_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
یک قاب Section Zoom جدید ایجاد می‌کند و آن را در مجموعه اشکال در فهرست مشخص شده وارد می‌نماید.

### بازگشت

‏[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) تازه ایجاد شده.

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که قاب Section Zoom در آن وارد می‌شود. |
| x | **float** | مختصات x قاب Section Zoom جدید، به نقطه. |
| y | **float** | مختصات y قاب Section Zoom جدید، به نقطه. |
| width | **float** | عرض قاب Section Zoom جدید، به نقطه. |
| height | **float** | ارتفاع قاب Section Zoom جدید، به نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) که توسط قاب Section Zoom ارجاع داده شده است؛<br/><br/> باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید شامل شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع داده شده به ارائهٔ فعلی تعلق نداشته باشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |

## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
یک قاب Section Zoom جدید با تصویر از پیش تعریف‌شده ایجاد می‌کند و آن را در مجموعه اشکال در فهرست مشخص شده وارد می‌نماید.

### بازگشت

‏[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) تازه ایجاد شده.

```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| index | **int** | شاخص صفر-پایه‌ای که قاب Section Zoom در آن وارد می‌شود. |
| x | **float** | مختصات x قاب Section Zoom جدید، به نقطه. |
| y | **float** | مختصات y قاب Section Zoom جدید، به نقطه. |
| width | **float** | عرض قاب Section Zoom جدید، به نقطه. |
| height | **float** | ارتفاع قاب Section Zoom جدید، به نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) که توسط قاب Section Zoom ارجاع داده شده است؛<br/><br/> باید به این ارائه تعلق داشته باشد و حداقل یک اسلاید شامل شود. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | تصویری که در داخل قاب Section Zoom نمایش داده می‌شود. |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع داده شده به ارائهٔ فعلی تعلق نداشته باشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |

### موارد مرتبط
* کلاس [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* کلاس [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* کلاس [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe)
* کلاس [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* ماژول [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* کتابخانه [`Aspose.Slides`](/slides/python-net)
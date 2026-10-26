---
title: add_section_zoom_frame method
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
یک چارچوب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ shape collection اضافه می‌کند.

### بازگرداندن

[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) جدید ایجاد شده.

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x چارچوب Section Zoom جدید، بر حسب نقطه. |
| y | **float** | مختصات y چارچوب Section Zoom جدید، بر حسب نقطه. |
| width | **float** | عرض چارچوب Section Zoom جدید، بر حسب نقطه. |
| height | **float** | ارتفاع چارچوب Section Zoom جدید، بر حسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ارجاع داده شده توسط چارچوب Section Zoom؛ <br/><br/> باید به این presentation تعلق داشته باشد و حداقل یک slide داشته باشد. |

### استثنائات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع داده شده به پرزنتیشن جاری تعلق نداشته باشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
یک چارچوب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ shape collection اضافه می‌کند.

### بازگرداندن

[`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe) جدید ایجاد شده.

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| x | **float** | مختصات x چارچوب Section Zoom جدید، بر حسب نقطه. |
| y | **float** | مختصات y چارچوب Section Zoom جدید، بر حسب نقطه. |
| width | **float** | عرض چارچوب Section Zoom جدید، بر حسب نقطه. |
| height | **float** | ارتفاع چارچوب Section Zoom جدید، بر حسب نقطه. |
| section | [`ISection`](/slides/python-net/fa/aspose.slides/isection) | [`ISection`](/slides/python-net/fa/aspose.slides/isection) ارجاع داده شده توسط چارچوب Section Zoom؛ <br/><br/> باید به این presentation تعلق داشته باشد و حداقل یک slide داشته باشد. |
| image | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage) برای نمایش درون چارچوب Section Zoom. |

### استثنائات

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | در صورتی که بخش ارجاع داده شده به پرزنتیشن جاری تعلق نداشته باشد یا اسلایدی نداشته باشد، پرتاب می‌شود. |

### موارد مرتبط
* class [`IPPImage`](/slides/python-net/fa/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/fa/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/fa/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/fa/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/fa/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
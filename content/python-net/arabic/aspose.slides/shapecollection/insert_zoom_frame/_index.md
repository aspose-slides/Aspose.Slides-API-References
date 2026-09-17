---
title: insert_zoom_frame method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
ينشئ إطار Zoom جديدًا ويُدرجه في مجموعة الأشكال في الموضع المحدد.

### القيمة المرجعة
الـ [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج إطار Zoom. |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليها بواسطة إطار Zoom. |

### الاستثناءات
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced slide does not belong to the current presentation. |

## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
ينشئ إطار Zoom جديدًا بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال في الموضع المحدد.

### القيمة المرجعة
الـ [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | المؤشر الصفري الذي يتم عنده إدراج إطار Zoom. |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليها بواسطة إطار Zoom. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة للشريحة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |

### الاستثناءات
| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Thrown if the referenced slide does not belong to the current presentation. |

### انظر أيضًا
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* الفئة [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
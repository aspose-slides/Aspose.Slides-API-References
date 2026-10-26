---
title: add_zoom_frame method
second_title: Aspose.Slides للـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة
الـ [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛<br/><br/>            يجب أن يكون جزءًا من هذا العرض التقديمي. |

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يظهر إذا كان الشريحة المشار إليها لا تنتمي إلى العرض التقديمي الحالي. |

## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
ينشئ إطار Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة
الـ [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) الذي تم إنشاؤه حديثًا.

```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بالنقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛<br/><br/>            يجب أن يكون جزءًا من هذا العرض التقديمي. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة للشرائح المشار إليها [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |

### الاستثناءات
| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يظهر إذا كان الشريحة المشار إليها لا تنتمي إلى العرض التقديمي الحالي. |

### انظر أيضًا
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* الفئة [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
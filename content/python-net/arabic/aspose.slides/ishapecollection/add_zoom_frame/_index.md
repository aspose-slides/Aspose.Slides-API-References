---
title: add_zoom_frame method
second_title: مرجع API لـ Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_zoom_frame/
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
| x | **float** | إحداثي x لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدات النقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛<br/><br/>            يجب أن يكون جزءًا من هذا العرض التقديمي. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يحدث إذا لم يكن الشرائح المشار إليها جزءًا من العرض التقديمي الحالي. |


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
| x | **float** | إحداثي x لإطار Zoom الجديد، بوحدات النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد، بوحدات النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدات النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدات النقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ [`ISlide`](/slides/python-net/ar/aspose.slides/islide) المشار إليه بواسطة إطار Zoom؛<br/><br/>            يجب أن يكون جزءًا من هذا العرض التقديمي. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة للشرائح المشار إليها [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يحدث إذا لم يكن الشرائح المشار إليها جزءًا من العرض التقديمي الحالي. |



### انظر أيضًا
* فئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* فئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* فئة [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
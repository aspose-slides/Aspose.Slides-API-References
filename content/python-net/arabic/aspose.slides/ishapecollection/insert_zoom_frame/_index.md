---
title: insert_zoom_frame method
second_title: مرجع API Aspose.Slides للـ Python عبر .NET
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
ينشئ إطار Zoom جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرجعة

الـ[`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) التي تم إنشاؤها حديثًا.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج عنده إطار Zoom. |
| x | **float** | إحداثي x لإطار Zoom الجديد، بوحدة النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد، بوحدة النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدة النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدة النقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ[`ISlide`](/slides/python-net/ar/aspose.slides/islide) المرجعي لإطار Zoom. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح إذا كان الشريحة المرجعية لا تنتمي إلى العرض الحالي. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
ينشئ إطار Zoom جديدًا بصورة معرفة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرجعة

الـ[`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe) التي تم إنشاؤها حديثًا.



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج عنده إطار Zoom. |
| x | **float** | إحداثي x لإطار Zoom الجديد، بوحدة النقاط. |
| y | **float** | إحداثي y لإطار Zoom الجديد، بوحدة النقاط. |
| width | **float** | عرض إطار Zoom الجديد، بوحدة النقاط. |
| height | **float** | ارتفاع إطار Zoom الجديد، بوحدة النقاط. |
| slide | [`ISlide`](/slides/python-net/ar/aspose.slides/islide) | الـ[`ISlide`](/slides/python-net/ar/aspose.slides/islide) المرجعي لإطار Zoom. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة للشريحة المرجعية [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage). |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح إذا كان الشريحة المرجعية لا تنتمي إلى العرض الحالي. |



### انظر أيضًا
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الفئة [`ISlide`](/slides/python-net/ar/aspose.slides/islide)
* الفئة [`IZoomFrame`](/slides/python-net/ar/aspose.slides/izoomframe)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
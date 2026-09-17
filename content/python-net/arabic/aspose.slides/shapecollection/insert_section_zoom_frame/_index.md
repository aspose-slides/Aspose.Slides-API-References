---
title: insert_section_zoom_frame method
second_title: Aspose.Slides للبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
ينشئ إطار Section Zoom جديدًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### الإرجاع

العنصر الذي تم إنشاؤه حديثًا [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي تُدرج عنده إطار Section Zoom. |
| x | **float** | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | الـ [`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛<br/><br/> يجب أن يكون جزءًا من هذا العرض التقديمي وأن يحتوي على شريحة واحدة على الأقل. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا لم يكن القسم المشار إليه جزءًا من العرض التقديمي الحالي أو لا يحتوي على شرائح. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
ينشئ إطار Section Zoom جديدًا بصورة محددة مسبقًا ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### الإرجاع

العنصر الذي تم إنشاؤه حديثًا [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي تُدرج عنده إطار Section Zoom. |
| x | **float** | إحداثي x لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | الـ [`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛<br/><br/> يجب أن يكون جزءًا من هذا العرض التقديمي وأن يحتوي على شريحة واحدة على الأقل. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة التي يتم عرضها داخل إطار Section Zoom. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا لم يكن القسم المشار إليه جزءًا من العرض التقديمي الحالي أو لا يحتوي على شرائح. |



### انظر أيضًا
* class [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe)
* class [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
---
title: add_section_zoom_frame method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
ينشئ إطار Section Zoom جديدًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

الـ[`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي السيني لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | [`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن ينتمي إلى هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح إذا كان القسم المشار إليه لا ينتمي إلى العرض التقديمي الحالي أو لا يحتوي على أي شرائح. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
ينشئ إطار Section Zoom جديدًا بصورة محددة مسبقًا ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

الـ[`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| المعلمة | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي السيني لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | [`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار Section Zoom؛ يجب أن ينتمي إلى هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) التي سيتم عرضها داخل إطار Section Zoom. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطرح إذا كان القسم المشار إليه لا ينتمي إلى العرض التقديمي الحالي أو لا يحتوي على أي شرائح. |



### انظر أيضًا
* class [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
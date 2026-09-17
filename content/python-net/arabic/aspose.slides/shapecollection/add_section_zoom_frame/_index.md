---
title: add_section_zoom_frame method
second_title: Aspose.Slides للغة Python عبر .NET دليل API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
إنشاء إطار Section Zoom جديد وإضافته إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

[`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي السيني لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | ال[`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه من قبل إطار Section Zoom؛ <br/><br/> يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يتم إلقاؤه إذا لم يكن القسم المشار إليه جزءًا من العرض التقديمي الحالي أو لا يحتوي على أي شرائح. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
إنشاء إطار Section Zoom جديد مع صورة محددة مسبقًا وإضافته إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

[`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي السيني لإطار Section Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي الصادي لإطار Section Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Section Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Section Zoom الجديد، بالنقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | ال[`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه من قبل إطار Section Zoom؛ <br/><br/> يجب أن يكون جزءًا من هذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) التي سيتم عرضها داخل إطار Section Zoom. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يتم إلقاؤه إذا لم يكن القسم المشار إليه جزءًا من العرض التقديمي الحالي أو لا يحتوي على أي شرائح. |

### انظر أيضًا
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* الفئة [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
---
title: insert_section_zoom_frame method
second_title: Aspose.Slides لبايثون عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
ينشئ إطار تكبير القسم الجديد ويدخله في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرتجعة

الإطار [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار تكبير القسم. |
| x | **float** | إحداثي x لإطار تكبير القسم الجديد، بوحدة النقاط. |
| y | **float** | إحداثي y لإطار تكبير القسم الجديد، بوحدة النقاط. |
| width | **float** | عرض إطار تكبير القسم الجديد، بوحدة النقاط. |
| height | **float** | ارتفاع إطار تكبير القسم الجديد، بوحدة النقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | الـ[`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛<br/><br/>            يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا لم يكن القسم المشار إليه تابعًا للعرض التقديمي الحالي أو لا يحتوي على أي شرائح. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
ينشئ إطار تكبير القسم الجديد مع صورة محددة مسبقًا ويدخله في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرتجعة

الإطار [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe) الذي تم إنشاؤه حديثًا.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي يُدرج فيه إطار تكبير القسم. |
| x | **float** | إحداثي x لإطار تكبير القسم الجديد، بوحدة النقاط. |
| y | **float** | إحداثي y لإطار تكبير القسم الجديد، بوحدة النقاط. |
| width | **float** | عرض إطار تكبير القسم الجديد، بوحدة النقاط. |
| height | **float** | ارتفاع إطار تكبير القسم الجديد، بوحدة النقاط. |
| section | [`ISection`](/slides/python-net/ar/aspose.slides/isection) | الـ[`ISection`](/slides/python-net/ar/aspose.slides/isection) المشار إليه بواسطة إطار تكبير القسم؛<br/><br/>            يجب أن يكون تابعًا لهذا العرض التقديمي ويحتوي على شريحة واحدة على الأقل. |
| image | [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage) | الصورة التي ستُعرض داخل إطار تكبير القسم. |

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | يُطلق إذا لم يكن القسم المشار إليه تابعًا للعرض التقديمي الحالي أو لا يحتوي على أي شرائح. |



### انظر أيضًا
* الفئة [`IPPImage`](/slides/python-net/ar/aspose.slides/ippimage)
* الفئة [`ISection`](/slides/python-net/ar/aspose.slides/isection)
* الفئة [`ISectionZoomFrame`](/slides/python-net/ar/aspose.slides/isectionzoomframe)
* الفئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
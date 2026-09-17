---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
ينشئ إطار ملخص تكبير جديد ويُدرجه في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرجعة

المُنشأة حديثًا [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe).



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم إدراج إطار ملخص التكبير عنده. |
| x | **float** | الإحداثي x لإطار ملخص التكبير الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار ملخص التكبير الجديد، بالنقاط. |
| width | **float** | العرض لإطار ملخص التكبير الجديد، بالنقاط. |
| height | **float** | الارتفاع لإطار ملخص التكبير الجديد، بالنقاط. |

### ملاحظات

تنشئ هذه الطريقة إطار ملخص تكبير يجمع روابط الملخص لجميع الأقسام في العرض التقديمي.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمى إذا كان العرض التقديمي لا يحتوي على أقسام، أو إذا لم تكن الشريحة المستهدفة تنتمي إلى أي قسم. |



### انظر أيضًا
* فئة [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* فئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)
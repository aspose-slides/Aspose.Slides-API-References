---
title: add_summary_zoom_frame method
second_title: Aspose.Slides للـ Python عبر .NET API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

### القيمة المرجعة

الـ[`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.



```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```


| المعامل | النوع | الوصف |
| :- | :- | :- |
| x | **float** | الإحداثي س للإطار Summary Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي ص للإطار Summary Zoom الجديد، بالنقاط. |
| width | **float** | العرض للإطار Summary Zoom الجديد، بالنقاط. |
| height | **float** | الارتفاع للإطار Summary Zoom الجديد، بالنقاط. |

### ملاحظات

تنشئ هذه الطريقة إطار Summary Zoom يجمع روابط الملخص لجميع الأقسام في العرض التقديمي.

### الاستثناءات

| الاستثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُطرح إذا لم يكن هناك أقسام في العرض التقديمي، أو إذا لم تنتمي الشريحة المستهدفة إلى أي قسم. |



### انظر أيضًا
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* فئة [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
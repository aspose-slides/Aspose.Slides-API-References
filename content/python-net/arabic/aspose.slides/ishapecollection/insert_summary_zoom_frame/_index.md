---
title: insert_summary_zoom_frame method
second_title: Aspose.Slides لـ Python عبر .NET مرجع API
description: 
type: docs
url: /ar/aspose.slides/ishapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
ينشئ إطار Summary Zoom جديد ويدخله في مجموعة الأشكال عند الفهرس المحدد.

### القيمة المرجعة
الـ [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe) الذي تم إنشاؤه حديثًا.

```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | **int** | الفهرس الصفري الذي سيتم عنده إدراج إطار Summary Zoom. |
| x | **float** | إحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | **float** | إحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Summary Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Summary Zoom الجديد، بالنقاط. |

### ملاحظات
تنشئ هذه الطريقة إطار Summary Zoom يجمع روابط الملخص لجميع الأقسام في العرض التقديمي.

### استثناءات
| استثناء | الوصف |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يتم إلقاؤه إذا كان العرض التقديمي لا يحتوي على أقسام، أو إذا لم تكن الشريحة المستهدفة تنتمي إلى أي قسم. |

### انظر أيضًا
* فئة [`IShapeCollection`](/slides/python-net/ar/aspose.slides/ishapecollection)
* فئة [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)
* فئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* وحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* مكتبة [`Aspose.Slides`](/slides/python-net)
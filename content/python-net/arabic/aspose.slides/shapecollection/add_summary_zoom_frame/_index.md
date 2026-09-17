---
title: add_summary_zoom_frame method
second_title: مرجع API Aspose.Slides للبايثون عبر .NET
description: 
type: docs
url: /ar/aspose.slides/shapecollection/add_summary_zoom_frame/
weight: 140
---
## add_summary_zoom_frame(self, x, y, width, height) {#float-float-float-float}
ينشئ إطار Summary Zoom جديد ويضيفه إلى نهاية مجموعة الأشكال.

### Returns
المُنشأ حديثًا [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe).

```python
def add_summary_zoom_frame(self, x, y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | الإحداثي x لإطار Summary Zoom الجديد، بالنقاط. |
| y | **float** | الإحداثي y لإطار Summary Zoom الجديد، بالنقاط. |
| width | **float** | عرض إطار Summary Zoom الجديد، بالنقاط. |
| height | **float** | ارتفاع إطار Summary Zoom الجديد، بالنقاط. |

### Remarks
تنشئ هذه الطريقة Summary Zoom جديدًا وتضع فيه مجموعة من الكائنات لجميع الأقسام في هذا العرض.

### Exceptions

| Exception | Description |
| :- | :- |
| [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception) | يُرمى إذا لم تكن هناك أقسام في العرض، أو إذا لم تكن الشريحة المستهدفة تنتمي إلى أي قسم. |

### See Also
* الفئة [`ISummaryZoomFrame`](/slides/python-net/ar/aspose.slides/isummaryzoomframe)
* الفئة [`PptxEditException`](/slides/python-net/ar/aspose.slides/pptxeditexception)
* الفئة [`ShapeCollection`](/slides/python-net/ar/aspose.slides/shapecollection)
* الوحدة [`aspose.slides`](/slides/python-net/ar/aspose.slides)
* المكتبة [`Aspose.Slides`](/slides/python-net)
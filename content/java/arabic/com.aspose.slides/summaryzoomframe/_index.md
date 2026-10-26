---
title: SummaryZoomFrame
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل كائن Summary Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/summaryzoomframe/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المطبقة:**  
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)  
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

يمثل كائن Summary Zoom في شريحة.

## الطرق

| Method | الوصف |
| --- | --- |
| [getLayout()](#getLayout--) | يحصل على تخطيط Summary Zoom Sections في الإطار. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن Summary Zoom Frame. |

### getLayout() {#getLayout--}
```
public final int getLayout()
```

يحصل على تخطيط Summary Zoom Sections في الإطار. القيمة الافتراضية هي GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**  
int

### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن Summary Zoom Frame.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**  
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
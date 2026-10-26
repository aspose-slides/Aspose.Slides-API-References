---
title: SummaryZoomFrame
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يمثل كائن Summary Zoom في شريحة.
type: docs
url: /ar/com.aspose.slides/summaryzoomframe/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**جميع الواجهات المُنفَّذة:**  
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)  
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

يمثل كائن Summary Zoom في شريحة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLayout()](#getLayout--) | يحصل على تخطيط أقسام Summary Zoom في الإطار. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن Summary Zoom Frame. |

### getLayout() {#getLayout--}
```
public final int getLayout()
```

يحصل على تخطيط أقسام Summary Zoom في الإطار. القيمة الافتراضية هي GridLayout.

--------------------

> ```
> يوضح المثال الحصول على عنصر Summary Zoom Section حسب الفهرس:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
int

### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن Summary Zoom Frame.

--------------------

> ```
> يوضح المثال الحصول على عنصر Summary Zoom Section حسب الفهرس:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**  
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
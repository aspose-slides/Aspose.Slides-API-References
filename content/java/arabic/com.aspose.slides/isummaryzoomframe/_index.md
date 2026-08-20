---
title: ISummaryZoomFrame
second_title: مرجع API Aspose.Slides لجافا
description: يمثل إطار تكبير ملخص في الشريحة.
type: docs
url: /ar/com.aspose.slides/isummaryzoomframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

يمثل إطار تكبير موجز في الشريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLayout()](#getLayout--) | يحصل على تخطيط أقسام تكبير الموجز في الإطار. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن إطار تكبير الموجز. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

يحصل على تخطيط أقسام تكبير الموجز في الإطار. القيمة الافتراضية هي GridLayout.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

يحصل على [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لكائن إطار تكبير الموجز.

--------------------

> ```
> يوضح المثال كيفية الحصول على عنصر قسم تكبير الموجز حسب الفهرس:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**الإرجاع:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
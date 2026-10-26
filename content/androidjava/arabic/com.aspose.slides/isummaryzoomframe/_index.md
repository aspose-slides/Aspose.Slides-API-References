---
title: ISummaryZoomFrame
second_title: Aspose.Slides لـ Android عبر مرجع API جافا
description: يمثل إطار تكبير ملخص في شريحة.
type: docs
url: /ar/com.aspose.slides/isummaryzoomframe/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

يمثل إطار تكبير ملخص في شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getLayout()](#getLayout--) | يجلب تخطيط أقسام تكبير الملخص في الإطار. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | يجلب [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لإطار تكبير الملخص. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


يجلب تخطيط أقسام تكبير الملخص في الإطار. القيمة الافتراضية هي GridLayout.

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

**القيمة المرجعة:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


يجلب [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) لإطار تكبير الملخص.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
---
title: SummaryZoomFrame
second_title: Aspose.Slides Java API Referencia
description: Egy diában a Summary Zoom objektumot reprezentálja.
type: docs
url: /hu/com.aspose.slides/summaryzoomframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Egy diában a Summary Zoom objektumot reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLayout()](#getLayout--) | Lekéri a Summary Zoom szakaszok elrendezését a keretben. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Lekéri [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) a Summary Zoom Frame objektumhoz. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Lekéri a Summary Zoom szakaszok elrendezését a keretben. Alapértelmezett érték a GridLayout.

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

**Visszatérési érték:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Lekéri [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) a Summary Zoom Frame objektumhoz.

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

**Visszatérési érték:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
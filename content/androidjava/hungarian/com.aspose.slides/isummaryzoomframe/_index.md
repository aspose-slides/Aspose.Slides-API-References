---
title: ISummaryZoomFrame
second_title: Aspose.Slides Android számára Java API referencia
description: Egy Summary Zoom keretet ábrázol egy dián.
type: docs
url: /hu/com.aspose.slides/isummaryzoomframe/
---
**Összes megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Egy Summary Zoom keretet ábrázol egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLayout()](#getLayout--) | Lekéri a Summary Zoom szakaszok elrendezését a keretben. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Lekéri a [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) értékét a Summary Zoom Frame objektumhoz. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Lekéri a Summary Zoom szakaszok elrendezését a keretben. Az alapértelmezett érték a GridLayout.

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

**Visszatérési érték:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Lekéri a [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) értékét a Summary Zoom Frame objektumhoz.

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatérési érték:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
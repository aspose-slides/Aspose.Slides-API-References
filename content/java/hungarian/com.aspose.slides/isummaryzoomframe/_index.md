---
title: ISummaryZoomFrame
second_title: Aspose.Slides for Java API Referencia
description: Egy dián található Summary Zoom keretet ábrázol.
type: docs
url: /hu/com.aspose.slides/isummaryzoomframe/
---
**Minden implementált interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Egy dián található Summary Zoom keretet ábrázol.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getLayout()](#getLayout--) | A keretben lévő Summary Zoom szakaszok layout-ját kéri le. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Lekéri [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) a Summary Zoom Frame objektumhoz. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


A keretben lévő Summary Zoom szakaszok layout-ját kéri le. Alapértelmezett érték a GridLayout.

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


Lekéri [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) a Summary Zoom Frame objektumhoz.

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
---
title: ISummaryZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en Summary Zoom-ram i en bild.
type: docs
url: /sv/com.aspose.slides/isummaryzoomframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Representerar en Summary Zoom frame i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLayout()](#getLayout--) | Hämtar layout av Summary Zoom Sections i ramen. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Hämtar [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) för Summary Zoom Frame-objektet. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Hämtar layout av Summary Zoom Sections i ramen. Standardvärdet är GridLayout.

--------------------

> ```
> Exemplet visar hur man hämtar Summary Zoom Section-element efter index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Hämtar [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) för Summary Zoom Frame-objektet.

--------------------

> ```
> Exemplet visar hur man hämtar Summary Zoom Section-element efter index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
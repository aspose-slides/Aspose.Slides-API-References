---
title: SummaryZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Summary Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/summaryzoomframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Representerar ett Summary Zoom-objekt i en bild.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLayout()](#getLayout--) | Hämtar layout för Summary Zoom Sections i ramen. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Hämtar [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) for the Summary Zoom Frame object. |

### getLayout() {#getLayout--}
```
public final int getLayout()
```

Hämtar layout för Summary Zoom Sections i ramen. Standardvärdet är GridLayout.

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

**Returnerar:**
int

### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Hämtar [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) för Summary Zoom Frame object.

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


**Returnerar:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
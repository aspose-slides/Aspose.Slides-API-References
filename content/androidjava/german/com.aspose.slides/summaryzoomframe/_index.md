---
title: SummaryZoomFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt ein Summary Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/summaryzoomframe/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Stellt ein Summary Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLayout()](#getLayout--) | Ermittelt das Layout der Summary Zoom Sections im Frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Ermittelt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Ermittelt das Layout der Summary Zoom Sections im Frame. Der Standardwert ist GridLayout.

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

**Rückgabewert:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Ermittelt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt.

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

**Rückgabewert:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
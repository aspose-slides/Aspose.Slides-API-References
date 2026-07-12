---
title: ISummaryZoomFrame
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt einen Summary Zoom Frame in einer Folie dar.
type: docs
url: /de/com.aspose.slides/isummaryzoomframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Stellt einen Summary Zoom Frame in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLayout()](#getLayout--) | Ruft das Layout der Summary Zoom Sections im Frame ab. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Ruft [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt ab. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Ruft das Layout der Summary Zoom Sections im Frame ab. Der Standardwert ist GridLayout.

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

**Rückgabewert:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Ruft [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) für das Summary Zoom Frame-Objekt ab.

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

**Rückgabewert:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
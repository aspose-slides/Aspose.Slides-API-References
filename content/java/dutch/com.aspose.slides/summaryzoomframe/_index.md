---
title: SummaryZoomFrame
second_title: Aspose.Slides voor Java API Referentie
description: Stelt een Summary Zoom-object in een dia voor.
type: docs
url: /nl/com.aspose.slides/summaryzoomframe/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Stelt een Summary Zoom-object in een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLayout()](#getLayout--) | Haalt de lay-out op van Summary Zoom Sections in het frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Haalt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) op voor het Summary Zoom Frame-object. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Haalt de lay-out op van Summary Zoom Sections in het frame. Standaardwaarde is GridLayout.

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

**Retour:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Haalt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) op voor het Summary Zoom Frame-object.

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

**Retour:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
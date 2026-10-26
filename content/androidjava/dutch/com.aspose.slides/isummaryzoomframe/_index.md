---
title: ISummaryZoomFrame
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt een Summary Zoom-frame voor in een dia.
type: docs
url: /nl/com.aspose.slides/isummaryzoomframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Stelt een Summary Zoom-frame voor in een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLayout()](#getLayout--) | Haalt de lay-out van Summary Zoom-secties op in het frame. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Haalt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) op voor het Summary Zoom Frame-object. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


Haalt de lay-out van Summary Zoom-secties op in het frame. Standaardwaarde is GridLayout.

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

**Retour:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Haalt [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) op voor het Summary Zoom Frame-object.

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

**Retour:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
---
title: SummaryZoomFrame
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje objekt Summary Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/summaryzoomframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Reprezentuje objekt Summary Zoom na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLayout()](#getLayout--) | Získá rozvržení částí Summary Zoom v rámci. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Získá [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pro objekt Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Získá rozvržení částí Summary Zoom v rámci. Výchozí hodnota je GridLayout.

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


**Vrací:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Získá [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pro objekt Summary Zoom Frame.

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


**Vrací:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
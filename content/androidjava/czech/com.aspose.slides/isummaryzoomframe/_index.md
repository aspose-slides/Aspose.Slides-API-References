---
title: ISummaryZoomFrame
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Representuje rámec Summary Zoom ve snímku.
type: docs
url: /cs/com.aspose.slides/isummaryzoomframe/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Representuje rámeček Summary Zoom ve snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLayout()](#getLayout--) | Získá rozložení sekcí Summary Zoom v rámci. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Získá [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pro objekt Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Získá rozložení sekcí Summary Zoom v rámci. Výchozí hodnota je GridLayout.

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

**Vrací:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Získá [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pro objekt Summary Zoom Frame.

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

**Vrací:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
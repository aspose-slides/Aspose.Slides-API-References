---
title: ISummaryZoomFrame
second_title: Aspose.Slides dla dokumentacji API Java
description: Reprezentuje ramkę Summary Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/isummaryzoomframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

Reprezentuje ramkę Summary Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLayout()](#getLayout--) | Pobiera układ sekcji Summary Zoom w ramce. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Pobiera [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) dla obiektu Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Pobiera układ sekcji Summary Zoom w ramce. Domyślna wartość to GridLayout.

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

**Zwraca:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Pobiera [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) dla obiektu Summary Zoom Frame.

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

**Zwraca:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
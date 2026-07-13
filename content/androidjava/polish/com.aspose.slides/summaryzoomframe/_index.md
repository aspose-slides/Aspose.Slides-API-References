---
title: SummaryZoomFrame
second_title: Aspose.Slides dla Androida za pośrednictwem odwołania do API Java
description: Reprezentuje obiekt Summary Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/summaryzoomframe/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

Reprezentuje obiekt Summary Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLayout()](#getLayout--) | Pobiera układ sekcji Summary Zoom w ramce. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Pobiera [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) dla obiektu Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```

Pobiera układ sekcji Summary Zoom w ramce. Domyślna wartość to GridLayout.

--------------------

> ```
> Przykład demonstruje pobieranie elementu sekcji Summary Zoom według indeksu:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

**Zwraca:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```

Pobiera [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) dla obiektu Summary Zoom Frame.

--------------------

> ```
> Przykład demonstruje pobieranie elementu sekcji Summary Zoom według indeksu:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Zwraca:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
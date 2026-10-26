---
title: SummaryZoomFrame
second_title: Aspose.Slides pro Java API Reference
description: Představuje objekt Summary Zoom na snímku.
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

Představuje objekt Summary Zoom na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getLayout()](#getLayout--) | Získá rozložení sekcí Summary Zoom ve rámci. |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Získá [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) pro objekt Summary Zoom Frame. |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Získá rozložení sekcí Summary Zoom ve rámci. Výchozí hodnota je GridLayout.

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
> Příklad ukazuje získání prvku sekce Summary Zoom podle indexu:
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
---
title: ZoomFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Slide Zoom-object voor in een dia.
type: docs
url: /nl/com.aspose.slides/zoomframe/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Stelt een Slide Zoom-object voor in een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Haalt of stelt het dia-object in waarnaar het Slide Zoom-object linkt. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Haalt of stelt het dia-object in waarnaar het Slide Zoom-object linkt. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Haalt of stelt het dia-object in waarnaar het Slide Zoom-object linkt. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Volgend voorbeeld toont het wijzigen van de doel-dia en maakt een nieuwe afbeelding voor het Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Haalt of stelt het dia-object in waarnaar het Slide Zoom-object linkt. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Volgend voorbeeld toont het wijzigen van de doel-dia en maakt een nieuwe afbeelding voor het Slide Zoom-object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
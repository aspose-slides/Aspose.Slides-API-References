---
title: ZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Slide Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/zoomframe/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Representerar ett Slide Zoom-objekt i en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Hämtar eller anger slide-objektet som Slide Zoom-objektet länkar till. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Hämtar eller anger slide-objektet som Slide Zoom-objektet länkar till. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Hämtar eller anger slide-objektet som Slide Zoom-objektet länkar till. Läs/skriv [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Hämtar eller anger slide-objektet som Slide Zoom-objektet länkar till. Läs/skriv [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Nästa exempel demonstrerar hur målbilden ändras och skapar en ny bild för Slide Zoom-objektet:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
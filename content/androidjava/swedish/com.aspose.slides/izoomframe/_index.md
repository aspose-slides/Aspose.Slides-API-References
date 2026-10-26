---
title: IZoomFrame
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar ett Slide Zoom-objekt i en bild.
type: docs
url: /sv/com.aspose.slides/izoomframe/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Representerar ett Slide Zoom-objekt i en bild.
## Metoder

| Method | Description |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Hämtar eller ställer in bildobjektet som Slide Zoom-objektet länkar till. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Hämtar eller ställer in bildobjektet som Slide Zoom-objektet länkar till. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Hämtar eller ställer in bildobjektet som Slide Zoom-objektet länkar till. Läs/skriv [ISlide](../../com.aspose.slides/islide).

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
public abstract void setTargetSlide(ISlide value)
```


Hämtar eller ställer in bildobjektet som Slide Zoom-objektet länkar till. Läs/skriv [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
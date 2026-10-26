---
title: IZoomFrame
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een Slide Zoom-object voor in een dia.
type: docs
url: /nl/com.aspose.slides/izoomframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Stelt een Slide Zoom-object voor in een dia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Haalt of stelt het dia-object in waar het Slide Zoom-object naar linkt. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Haalt of stelt het dia-object in waar het Slide Zoom-object naar linkt. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Haalt of stelt het dia-object in waar het Slide Zoom-object naar linkt. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Haalt of stelt het dia-object in waar het Slide Zoom-object naar linkt. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
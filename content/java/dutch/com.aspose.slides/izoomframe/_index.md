---
title: IZoomFrame
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Slide Zoom-object in een dia voor.
type: docs
url: /nl/com.aspose.slides/izoomframe/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Stelt een Slide Zoom-object in een dia voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Haalt op of stelt het Slide-object in waar de Slide Zoom-object naar verwijst. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Haalt op of stelt het Slide-object in waar de Slide Zoom-object naar verwijst. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Haalt op of stelt het Slide-object in waar de Slide Zoom-object naar verwijst. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Retourwaarde:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Haalt op of stelt het Slide-object in waar de Slide Zoom-object naar verwijst. Lezen/Schrijven [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
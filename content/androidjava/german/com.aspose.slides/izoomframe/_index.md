---
title: IZoomFrame
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt ein Slide Zoom-Objekt in einer Folie dar.
type: docs
url: /de/com.aspose.slides/izoomframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Stellt ein Slide Zoom-Objekt in einer Folie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Liest oder setzt das Folienobjekt, auf das das Slide Zoom object verweist. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Liest oder setzt das Folienobjekt, auf das das Slide Zoom object verweist. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Liest oder setzt das Folienobjekt, auf das das Slide Zoom object verweist. Lesen/Schreiben [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Liest oder setzt das Folienobjekt, auf das das Slide Zoom object verweist. Lesen/Schreiben [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
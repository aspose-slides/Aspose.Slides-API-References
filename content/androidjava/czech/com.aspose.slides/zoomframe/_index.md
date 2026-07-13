---
title: ZoomFrame
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje objekt Slide Zoom ve snímku.
type: docs
url: /cs/com.aspose.slides/zoomframe/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Reprezentuje objekt Slide Zoom v snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Získá nebo nastaví objekt snímku, na který objekt Slide Zoom odkazuje. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Získá nebo nastaví objekt snímku, na který objekt Slide Zoom odkazuje. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Získá nebo nastaví objekt snímku, na který objekt Slide Zoom odkazuje. Čtení/Zápis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Získá nebo nastaví objekt snímku, na který objekt Slide Zoom odkazuje. Čtení/Zápis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
---
title: IZoomFrame
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje objekt Slide Zoom na snímku.
type: docs
url: /cs/com.aspose.slides/izoomframe/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Representuje objekt Slide Zoom na snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Získá nebo nastaví objekt snímku, na který odkazuje objekt Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Získá nebo nastaví objekt snímku, na který odkazuje objekt Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Získá nebo nastaví objekt snímku, na který odkazuje objekt Slide Zoom. Číst/Zapisovat [ISlide](../../com.aspose.slides/islide).

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
public abstract void setTargetSlide(ISlide value)
```

Získá nebo nastaví objekt snímku, na který odkazuje objekt Slide Zoom. Číst/Zapisovat [ISlide](../../com.aspose.slides/islide).

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
---
title: IZoomFrame
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje obiekt Slide Zoom w slajdzie.
type: docs
url: /pl/com.aspose.slides/izoomframe/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Reprezentuje obiekt Slide Zoom w slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. Odczyt/zapis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Zwraca:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. Odczyt/zapis [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
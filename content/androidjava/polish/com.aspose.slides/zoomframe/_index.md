---
title: ZoomFrame
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje obiekt Slide Zoom na slajdzie.
type: docs
url: /pl/com.aspose.slides/zoomframe/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Reprezentuje obiekt Slide Zoom na slajdzie.
## Metody

| Metoda | Opis |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Pobiera lub ustawia obiekt slajdu, do którego odwołuje się obiekt Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
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
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISSlide-}
```
public final void setTargetSlide(ISlide value)
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
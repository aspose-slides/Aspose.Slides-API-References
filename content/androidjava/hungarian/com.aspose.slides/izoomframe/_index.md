---
title: IZoomFrame
second_title: Aspose.Slides Android számára Java API referencia
description: Slide Zoom objektumot képvisel egy dián.
type: docs
url: /hu/com.aspose.slides/izoomframe/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Egy Slide Zoom objektumot képvisel egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | A Slide Zoom objektumhoz kapcsolódó diát adja vissza vagy állítja be. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | A Slide Zoom objektumhoz kapcsolódó diát adja vissza vagy állítja be. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


A Slide Zoom objektumhoz kapcsolódó diát adja vissza vagy állítja be. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Visszatérési érték:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```


A Slide Zoom objektumhoz kapcsolódó diát adja vissza vagy állítja be. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
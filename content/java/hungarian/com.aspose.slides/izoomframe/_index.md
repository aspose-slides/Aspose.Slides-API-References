---
title: IZoomFrame
second_title: Aspose.Slides Java API Referencia
description: Egy dián lévő Slide Zoom objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/izoomframe/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Egy Slide Zoom objektumot képvisel egy dián.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Gets or sets the slide object that the Slide Zoom object links to. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Gets or sets the slide object that the Slide Zoom object links to. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Gets or sets the slide object that the Slide Zoom object links to. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Visszatér:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISSlide-}
```
public abstract void setTargetSlide(ISlide value)
```


Gets or sets the slide object that the Slide Zoom object links to. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> A következő példa bemutatja a cél dia módosítását és egy új képet hoz létre a Slide Zoom objektumhoz:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
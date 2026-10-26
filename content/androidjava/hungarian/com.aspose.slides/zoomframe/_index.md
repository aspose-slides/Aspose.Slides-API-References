---
title: ZoomFrame
second_title: Aspose.Slides for Android a Java API hivatkozás alapján
description: Egy dián egy Slide Zoom objektumot képvisel.
type: docs
url: /hu/com.aspose.slides/zoomframe/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Minden megvalósított interfész:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Egy Slide Zoom objektumot képvisel egy dián.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | A dia objektumát kapja vagy állítja, amelyhez a Slide Zoom objektum kapcsolódik. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | A dia objektumát kapja vagy állítja, amelyhez a Slide Zoom objektum kapcsolódik. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


A dia objektumát kapja vagy állítja, amelyhez a Slide Zoom objektum kapcsolódik. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

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
public final void setTargetSlide(ISlide value)
```


A dia objektumát kapja vagy állítja, amelyhez a Slide Zoom objektum kapcsolódik. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> A következő példa bemutatja a cél dia megváltoztatását és egy új kép létrehozását a Slide Zoom objektumhoz:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
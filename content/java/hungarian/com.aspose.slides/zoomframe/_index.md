---
title: ZoomFrame
second_title: Aspose.Slides Java API hivatkozás
description: Egy dián lévő Slide Zoom objektumot képvisel.
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

Egy dián lévő Slide Zoom objektumot képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | A diát objektumot adja vissza vagy állítja be, amelyhez a Slide Zoom objektum kapcsolódik. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | A diát objektumot adja vissza vagy állítja be, amelyhez a Slide Zoom objektum kapcsolódik. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

A diát objektumot adja vissza vagy állítja be, amelyhez a Slide Zoom objektum kapcsolódik. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

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

A diát objektumot adja vissza vagy állítja be, amelyhez a Slide Zoom objektum kapcsolódik. Olvasás/írás [ISlide](../../com.aspose.slides/islide).

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
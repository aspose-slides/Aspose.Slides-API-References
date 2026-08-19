---
title: ZoomFrame
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un oggetto Slide Zoom in una diapositiva.
type: docs
url: /it/com.aspose.slides/zoomframe/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Rappresenta un oggetto Slide Zoom in una diapositiva.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Lettura/scrittura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Restituisce:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```


Ottiene o imposta l'oggetto slide a cui l'oggetto Slide Zoom è collegato. Lettura/scrittura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
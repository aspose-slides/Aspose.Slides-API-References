---
title: ZoomFrame
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un objeto Slide Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/zoomframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Representa un objeto Slide Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Obtiene o establece el objeto diapositiva al que enlaza el objeto Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Obtiene o establece el objeto diapositiva al que enlaza el objeto Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Obtiene o establece el objeto diapositiva al que enlaza el objeto Slide Zoom. Lectura/escritura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```

Obtiene o establece el objeto diapositiva al que enlaza el objeto Slide Zoom. Lectura/escritura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
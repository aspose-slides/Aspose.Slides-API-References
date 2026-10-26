---
title: IZoomFrame
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Representa un objeto Slide Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/izoomframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Representa un objeto Slide Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Obtiene o establece el objeto Slide al que enlaza el objeto Slide Zoom. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Obtiene o establece el objeto Slide al que enlaza el objeto Slide Zoom. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

Obtiene o establece el objeto Slide al que enlaza el objeto Slide Zoom. Lectura/escritura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> El siguiente ejemplo demuestra cómo cambiar la diapositiva de destino y crea una nueva imagen para el objeto Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Devuelve:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```

Obtiene o establece el objeto Slide al que enlaza el objeto Slide Zoom. Lectura/escritura [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Ejemplo siguiente demuestra cómo cambiar la diapositiva de destino y crea una nueva imagen para el objeto Slide Zoom:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
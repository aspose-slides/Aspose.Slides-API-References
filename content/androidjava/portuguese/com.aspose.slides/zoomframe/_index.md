---
title: ZoomFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Slide Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/zoomframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IZoomFrame](../../com.aspose.slides/izoomframe)
```
public class ZoomFrame extends ZoomObject implements IZoomFrame
```

Representa um objeto Slide Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. |
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```


Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. Leitura/Gravação [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Retorna:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public final void setTargetSlide(ISlide value)
```


Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. Leitura/Gravação [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) |  |
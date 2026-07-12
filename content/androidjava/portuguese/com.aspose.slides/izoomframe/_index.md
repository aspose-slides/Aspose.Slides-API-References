---
title: IZoomFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Slide Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/izoomframe/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface IZoomFrame extends IZoomObject
```

Representa um objeto Slide Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTargetSlide()](#getTargetSlide--) | Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. |
| [setTargetSlide(ISlide value)](#setTargetSlide-com.aspose.slides.ISlide-) | Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. |
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. Leitura/gravação [ISlide](../../com.aspose.slides/islide).

--------------------

> ```
> Next example demonstrates changing target slide and creates new image for the Slide Zoom object:
>  
>  IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  zoomFrame.setTargetSlide(pres.getSlides().get_Item(2));
> ```


**Retorno:**
[ISlide](../../com.aspose.slides/islide)
### setTargetSlide(ISlide value) {#setTargetSlide-com.aspose.slides.ISlide-}
```
public abstract void setTargetSlide(ISlide value)
```


Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. Leitura/gravação [ISlide](../../com.aspose.slides/islide).

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
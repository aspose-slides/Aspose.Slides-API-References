---
title: ISectionZoomFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Section Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/isectionzoomframe/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Representa um objeto Section Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. Leitura/gravação [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. Leitura/gravação [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> This example demonstrates changing target section and creates a new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |
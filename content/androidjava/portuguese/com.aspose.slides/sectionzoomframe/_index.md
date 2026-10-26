---
title: SectionZoomFrame
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um objeto Section Zoom em um slide.
type: docs
url: /pt/com.aspose.slides/sectionzoomframe/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Representa um objeto Section Zoom em um slide.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. Leitura/Escrita [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retorna:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Obtém ou define o objeto de seção ao qual o objeto Section Zoom está vinculado. Leitura/Escrita [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Next example demonstrates changing target section and creates new image for the section zoom object:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>      sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  
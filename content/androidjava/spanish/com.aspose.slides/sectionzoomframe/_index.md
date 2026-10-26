---
title: SectionZoomFrame
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa un objeto Section Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/sectionzoomframe/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject)

**Todas las interfaces implementadas:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public class SectionZoomFrame extends ZoomObject implements ISectionZoomFrame
```

Representa un objeto Section Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtiene o establece el objeto de sección al que enlaza el objeto Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtiene o establece el objeto de sección al que enlaza el objeto Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public final ISection getTargetSection()
```


Obtiene o establece el objeto de sección al que enlaza el objeto Section Zoom. Lectura/escritura [ISection](../../com.aspose.slides/isection).

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

**Devuelve:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public final void setTargetSection(ISection value)
```


Obtiene o establece el objeto de sección al que enlaza el objeto Section Zoom. Lectura/escritura [ISection](../../com.aspose.slides/isection).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |
---
title: ISectionZoomFrame
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un objeto Section Zoom en una diapositiva.
type: docs
url: /es/com.aspose.slides/isectionzoomframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IZoomObject](../../com.aspose.slides/izoomobject)
```
public interface ISectionZoomFrame extends IZoomObject
```

Representa un objeto Section Zoom en una diapositiva.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTargetSection()](#getTargetSection--) | Obtiene o establece el objeto de sección al que está vinculado el objeto Section Zoom. |
| [setTargetSection(ISection value)](#setTargetSection-com.aspose.slides.ISection-) | Obtiene o establece el objeto de sección al que está vinculado el objeto Section Zoom. |
### getTargetSection() {#getTargetSection--}
```
public abstract ISection getTargetSection()
```


Obtiene o establece el objeto de sección al que está vinculado el objeto Section Zoom. Lectura/escritura [ISection](../../com.aspose.slides/isection).

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

**Devuelve:**
[ISection](../../com.aspose.slides/isection)
### setTargetSection(ISection value) {#setTargetSection-com.aspose.slides.ISection-}
```
public abstract void setTargetSection(ISection value)
```


Obtiene o establece el objeto de sección al que está vinculado el objeto Section Zoom. Lectura/escritura [ISection](../../com.aspose.slides/isection).

--------------------

> ```
> Este ejemplo muestra cómo cambiar la sección objetivo y crea una nueva imagen para el objeto Section Zoom:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISectionZoomFrame sectionZoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>       sectionZoomFrame.setTargetSection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISection](../../com.aspose.slides/isection) |  |
---
title: ILayoutSlide
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa una diapositiva de diseño.
type: docs
url: /es/com.aspose.slides/ilayoutslide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Representa una diapositiva de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el gestor HeaderFooter de la diapositiva de diseño. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Devuelve el gestor de marcadores de posición de la diapositiva de diseño. |
| [getMasterSlide()](#getMasterSlide--) | Devuelve o establece la diapositiva maestra para un diseño. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Devuelve o establece la diapositiva maestra para un diseño. |
| [getLayoutType()](#getLayoutType--) | Devuelve el tipo de diseño de esta diapositiva de diseño. |
| [hasDependingSlides()](#hasDependingSlides--) | Devuelve true si existe al menos una diapositiva que dependa de esta diapositiva de diseño. |
| [getDependingSlides()](#getDependingSlides--) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva de diseño. |
| [remove()](#remove--) | Elimina el diseño de la presentación. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva de diseño. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el gestor HeaderFooter de la diapositiva de diseño. Solo lectura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Devuelve:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

Devuelve el gestor de marcadores de posición de la diapositiva de diseño. Solo lectura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Devuelve:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

Devuelve o establece la diapositiva maestra para un diseño. Lectura/escritura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

Devuelve o establece la diapositiva maestra para un diseño. Lectura/escritura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

Devuelve el tipo de diseño de esta diapositiva de diseño. Solo lectura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Devuelve:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Devuelve true si existe al menos una diapositiva que dependa de esta diapositiva de diseño. Solo lectura boolean.

**Devuelve:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva de diseño.

**Devuelve:**
com.aspose.slides.ISlide[] - Matriz con todas las diapositivas que dependen de esta diapositiva de diseño
### remove() {#remove--}
```
public abstract void remove()
```

Elimina el diseño de la presentación.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Devuelve una colección de guías de dibujo para la diapositiva de diseño. Solo lectura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Añadiendo la nueva guía de dibujo vertical a la izquierda del centro de la diapositiva
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
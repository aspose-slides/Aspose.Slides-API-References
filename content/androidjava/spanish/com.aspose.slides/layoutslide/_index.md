---
title: LayoutSlide
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa una diapositiva de diseño.
type: docs
url: /es/com.aspose.slides/layoutslide/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas las interfaces implementadas:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Representa una diapositiva de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva de diseño. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Devuelve el administrador de marcadores de posición de la diapositiva de diseño. |
| [getMasterSlide()](#getMasterSlide--) | Devuelve o establece la diapositiva maestra para un diseño. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Devuelve o establece la diapositiva maestra para un diseño. |
| [remove()](#remove--) | Elimina el diseño de la presentación. |
| [getThemeManager()](#getThemeManager--) | Devuelve el administrador de tema sobrescrito. |
| [getLayoutType()](#getLayoutType--) | Devuelve el tipo de diseño de esta diapositiva de diseño. |
| [getDependingSlides()](#getDependingSlides--) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva de diseño. |
| [hasDependingSlides()](#hasDependingSlides--) | Devuelve true si existe al menos una diapositiva que dependa de esta diapositiva de diseño. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva de diseño. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva de diseño. Solo lectura [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Devuelve:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Devuelve el administrador de marcadores de posición de la diapositiva de diseño. Solo lectura [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Devuelve:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Devuelve o establece la diapositiva maestra para un diseño. Lectura/escritura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Devuelve o establece la diapositiva maestra para un diseño. Lectura/escritura [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### remove() {#remove--}
```
public final void remove()
```

Elimina el diseño de la presentación.
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Devuelve el administrador de tema sobrescrito. Solo lectura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Devuelve:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Devuelve el tipo de diseño de esta diapositiva de diseño. Solo lectura [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Devuelve:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva de diseño.

**Devuelve:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Devuelve true si existe al menos una diapositiva que dependa de esta diapositiva de diseño. Solo lectura  boolean .

**Devuelve:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura  boolean .

**Devuelve:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura  boolean .

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
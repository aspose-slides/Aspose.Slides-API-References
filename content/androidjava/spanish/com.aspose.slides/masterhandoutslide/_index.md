---
title: MasterHandoutSlide
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa la diapositiva maestra para folletos.
type: docs
url: /es/com.aspose.slides/masterhandoutslide/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Representa la diapositiva maestra para folletos.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva maestra de folletos. |
| [getThemeManager()](#getThemeManager--) | Devuelve el administrador de temas. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva maestra de folletos. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la propia diapositiva maestra esta propiedad siempre devuelve false. Lectura/escritura boolean.

**Devuelve:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Para la propia diapositiva maestra esta propiedad siempre devuelve false. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva maestra de folletos. Solo lectura [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Devuelve:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Devuelve el administrador de temas. Solo lectura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Devuelve:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Devuelve una colección de guías de dibujo para la diapositiva maestra de folletos. Solo lectura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Agregando la nueva guía de dibujo horizontal encima del centro de la diapositiva
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
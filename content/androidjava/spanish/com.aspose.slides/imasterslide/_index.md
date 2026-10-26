---
title: IMasterSlide
second_title: Referencia de la API de Aspose.Slides para Android vía Java
description: Representa una diapositiva maestra en una presentación.
type: docs
url: /es/com.aspose.slides/imasterslide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Representa una diapositiva maestra en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva maestra. |
| [getTitleStyle()](#getTitleStyle--) | Devuelve el estilo de un texto de título. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo a ella y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [getBodyStyle()](#getBodyStyle--) | Devuelve el estilo de un texto del cuerpo. |
| [getOtherStyle()](#getOtherStyle--) | Devuelve el estilo de otro texto. |
| [getLayoutSlides()](#getLayoutSlides--) | Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. |
| [getPreserve()](#getPreserve--) | Determina si la maestra correspondiente se elimina cuando todas las diapositivas que siguen a esa maestra se eliminan. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina si la maestra correspondiente se elimina cuando todas las diapositivas que siguen a esa maestra se eliminan. |
| [hasDependingSlides()](#hasDependingSlides--) | Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra. |
| [getDependingSlides()](#getDependingSlides--) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva maestra. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva maestra. Solo lectura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Devuelve:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Devuelve el estilo de un texto de título. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo a ella y aplica la diapositiva maestra creada a todas las diapositivas dependientes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo de tema externo (.thmx). |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nuevo MasterSlide con tema.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Devuelve el estilo de un texto del cuerpo. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Devuelve el estilo de otro texto. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. Solo lectura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Puede acceder a la API alternativa para agregar/insertar/eliminar/duplicar diapositivas de diseño usando la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Devuelve:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Determina si la maestra correspondiente se elimina cuando todas las diapositivas que siguen a esa maestra se eliminan. Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí mismo; para eliminar realmente maestras sin usar llame a [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) booleano Lectura/escritura.

**Devuelve:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Determina si la maestra correspondiente se elimina cuando todas las diapositivas que siguen a esa maestra se eliminan. Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí mismo; para eliminar realmente maestras sin usar llame a [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) booleano Lectura/escritura.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra. Booleano solo lectura.

**Devuelve:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra.

**Devuelve:**
com.aspose.slides.ISlide[] - Matriz de [ISlide](../../com.aspose.slides/islide), que dependen de esta diapositiva maestra
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Devuelve una colección de guías de dibujo para la diapositiva maestra. Solo lectura [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Añadiendo la nueva guía de dibujo vertical a la derecha del centro de la diapositiva
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
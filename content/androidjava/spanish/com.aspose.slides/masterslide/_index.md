---
title: MasterSlide
second_title: Referencia de API de Java para Aspose.Slides for Android
description: Representa una diapositiva maestra en una presentación.
type: docs
url: /es/com.aspose.slides/masterslide/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Representa una diapositiva maestra en una presentación.

## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva maestra. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo y aplica la diapositiva maestra creada a todas las diapositivas dependientes. |
| [getTitleStyle()](#getTitleStyle--) | Devuelve el estilo de un texto de título. |
| [getBodyStyle()](#getBodyStyle--) | Devuelve el estilo de un texto de cuerpo. |
| [getOtherStyle()](#getOtherStyle--) | Devuelve el estilo de otro texto. |
| [getLayoutSlides()](#getLayoutSlides--) | Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. |
| [getPreserve()](#getPreserve--) | Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. |
| [getDependingSlides()](#getDependingSlides--) | Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra. |
| [hasDependingSlides()](#hasDependingSlides--) | Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra. |
| [getThemeManager()](#getThemeManager--) | Devuelve el administrador de temas. |
| [getName()](#getName--) | Devuelve o establece el nombre de una diapositiva maestra. |
| [setName(String value)](#setName-java.lang.String-) | Devuelve o establece el nombre de una diapositiva maestra. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [getDrawingGuides()](#getDrawingGuides--) | Devuelve una colección de guías de dibujo para la diapositiva maestra. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva maestra. Solo lectura [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Devuelve:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Crea una nueva diapositiva maestra basada en la actual, aplicando un tema externo y aplica la diapositiva maestra creada a todas las diapositivas dependientes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fname | java.lang.String | Ruta al archivo de tema externo (.thmx). |

**Devuelve:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nueva diapositiva maestra con tema.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Devuelve el estilo de un texto de título. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Devuelve el estilo de un texto de cuerpo. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Devuelve el estilo de otro texto. Solo lectura [ITextStyle](../../com.aspose.slides/itextstyle).

**Devuelve:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Devuelve la colección de diapositivas de diseño secundarias para esta diapositiva maestra. Solo lectura [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Puede acceder a una API alternativa para agregar/insertar/eliminar/clonar diapositivas de diseño mediante la propiedad ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Devuelve:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí mismo; para eliminar realmente las maestras sin usar llame a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lectura/escritura boolean.

**Devuelve:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Determina si la maestra correspondiente se elimina cuando se eliminan todas las diapositivas que siguen a esa maestra. Nota: Aspose.Slides nunca eliminará ninguna maestra sin usar por sí mismo; para eliminar realmente las maestras sin usar llame a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Devuelve una matriz con todas las diapositivas que dependen de esta diapositiva maestra.

**Devuelve:**
com.aspose.slides.ISlide[] - Matriz de [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Devuelve true si existe al menos una diapositiva que depende de esta diapositiva maestra. Solo lectura boolean.

**Devuelve:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Devuelve el administrador de temas. Solo lectura [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Devuelve:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Devuelve o establece el nombre de una diapositiva maestra. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Devuelve o establece el nombre de una diapositiva maestra. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

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

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
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
---
title: PortionFormat
second_title: Referencia de API Java de Aspose.Slides para Android
description: Esta clase contiene las propiedades de formato de la porción de texto.
type: docs
url: /es/com.aspose.slides/portionformat/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Todas las interfaces implementadas:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Esta clase contiene las propiedades de formato de la porción de texto. A diferencia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), todas las propiedades de esta clase son escribibles.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instanciar un objeto de presentación que representa un archivo de presentación
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides usa estos identificadores especiales (similares a los usados en PowerPoint):
>      // +mn-lt - Fuente del cuerpo Latin (Fuente Latin menor)
>      // +mj-lt -Fuente del encabezado Latin (Fuente Latin mayor)
>      // +mn-ea - Fuente del cuerpo East Asian (Fuente East Asian menor)
>      // +mj-ea - Fuente del cuerpo East Asian (Fuente East Asian menor)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Esta clase se utiliza para devolver y manipular las propiedades de formato de la porción de texto definidas para la porción específica. Esto significa que no se aplica herencia al obtener los valores, por lo que en la mayoría de los casos obtendrá valores que significan "undefined".

Para obtener los valores efectivos de los parámetros de formato, incluidos los heredados, debe usar el método [getEffective](../../com.aspose.slides/portionformat\#getEffective) que devuelve una instancia de [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inicializa una nueva instancia de la clase [PortionFormat](../../com.aspose.slides/portionformat). |

## Métodos

| Método | Descripción |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Devuelve o establece el identificador del marcador. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Devuelve o establece el identificador del marcador. |
| [getSmartTagClean()](#getSmartTagClean--) | Determina si la etiqueta inteligente debe ser limpiada. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determina si la etiqueta inteligente debe ser limpiada. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Devuelve o establece el hipervínculo definido para clic del mouse. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Devuelve o establece el hipervínculo definido para clic del mouse. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Devuelve o establece el hipervínculo definido para pasar el mouse. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Devuelve o establece el hipervínculo definido para pasar el mouse. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Gestor de hipervínculos. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato de la porción efectivamente con la herencia aplicada. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Inicializa una nueva instancia de la clase [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Devuelve o establece el identificador del marcador. Lectura/escritura String.

**Devuelve:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Devuelve o establece el identificador del marcador. Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Determina si la etiqueta inteligente debe ser limpiada. No se aplica herencia. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Determina si la etiqueta inteligente debe ser limpiada. No se aplica herencia. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Devuelve o establece el hipervínculo definido para clic del mouse. Lectura/escritura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Devuelve o establece el hipervínculo definido para clic del mouse. Lectura/escritura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Devuelve:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Devuelve o establece el hipervínculo definido para pasar el mouse. Lectura/escritura [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Gestor de hipervínculos. Solo lectura [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Devuelve:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

Obtiene los datos de formato de la porción efectivamente con la herencia aplicada.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - Un [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
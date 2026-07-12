---
title: Paragraph
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un párrafo de texto.
type: docs
url: /es/com.aspose.slides/paragraph/
---
**Herencia:**  
java.lang.Object

**Todas las interfaces implementadas:**  
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject  
```
public final class Paragraph implements IParagraph, IDOMObject
```

Representa un párrafo de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializa una nueva instancia de la clase Paragraph con propiedades predeterminadas. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Constructor de copia que inicializa una nueva instancia de la clase Paragraph. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getPortions()](#getPortions--) | Devuelve la colección de porciones de texto. |
| [getParagraphFormat()](#getParagraphFormat--) | Devuelve el objeto de formato para este párrafo. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une fragmentos con el mismo formato. |
| [getText()](#getText--) | Obtiene o establece el texto sin formato de un párrafo. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto sin formato de un párrafo. |
| [getRect()](#getRect--) | Obtiene las coordenadas del rectángulo que delimita el párrafo. |
| [getLinesCount()](#getLinesCount--) | Obtiene el número de líneas en un párrafo. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Devuelve la diapositiva principal de un párrafo. |
| [getPresentation()](#getPresentation--) | Devuelve la presentación principal de un párrafo. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Inicializa una nueva instancia de la clase Paragraph con propiedades predeterminadas.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Constructor de copia que inicializa una nueva instancia de la clase Paragraph.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Devuelve la colección de porciones de texto. Solo lectura [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Devuelve:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)

### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Devuelve el objeto de formato para este párrafo. Solo lectura [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

El objeto de formato contiene los parámetros de formato definidos únicamente para el párrafo actual; los datos heredados no se aplican.

Para obtener los valores efectivos, incluidos los heredados, use el método [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Devuelve:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Une fragmentos con el mismo formato.

### getText() {#getText--}
```
public final String getText()
```

Obtiene o establece el texto sin formato de un párrafo. Lectura/escritura String.

Valor: El texto.

**Devuelve:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtiene o establece el texto sin formato de un párrafo. Lectura/escritura String.

Valor: El texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Obtiene las coordenadas del rectángulo que delimita el párrafo. El rectángulo incluye todas las líneas de texto en el párrafo, incluidas las vacías.

**Devuelve:**
android.graphics.RectF

### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

Obtiene el número de líneas en un párrafo.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
int - Conteo de líneas en un párrafo

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última.

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Especifica las propiedades de la porción que se usarán si se inserta otra porción después de la última.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Devuelve el objeto Parent_Immediate. Solo lectura IDOMObject.

**Devuelve:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Devuelve la diapositiva principal de un párrafo. Solo lectura [BaseSlide](../../com.aspose.slides/baseslide).

**Devuelve:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Devuelve la presentación principal de un párrafo. Solo lectura [IPresentation](../../com.aspose.slides/ipresentation).

**Devuelve:**
[IPresentation](../../com.aspose.slides/ipresentation)
---
title: ITextFrame
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa un TextFrame.
type: docs
url: /es/com.aspose.slides/itextframe/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Representa un TextFrame.
## Métodos

| Método | Descripción |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Devuelve la lista de todos los párrafos en un marco. |
| [getText()](#getText--) | Obtiene o establece el texto sin formato para un TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto sin formato para un TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Devuelve el objeto de formato para este objeto TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Proporciona acceso fácil a los hipervínculos contenidos. |
| [getParentShape()](#getParentShape--) | Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape. Sólo lectura [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une ejecuciones con el mismo formato en todos los párrafos. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Resalta todas las coincidencias del texto de ejemplo con el color especificado. |
| [splitTextByColumns()](#splitTextByColumns--) | Divide el contenido de texto del [ITextFrame](../../com.aspose.slides/itextframe) en una matriz de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Resalta todas las coincidencias del texto de ejemplo con el color especificado. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias del texto de ejemplo con el color especificado. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Resalta todas las coincidencias de la expresión regular con el color especificado. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las apariciones del texto especificado con otro texto especificado. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Reemplaza todas las coincidencias de la expresión regular con la cadena especificada. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Devuelve la lista de todos los párrafos en un marco. Sólo lectura [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Devuelve:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Obtiene o establece el texto sin formato para un TextFrame. Lectura/escritura String.

Valor: El texto.

**Devuelve:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtiene o establece el texto sin formato para un TextFrame. Lectura/escritura String.

Valor: El texto.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Devuelve el objeto de formato para este objeto TextFrame. Sólo lectura [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Devuelve:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Proporciona acceso fácil a los hipervínculos contenidos. Sólo lectura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Devuelve:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Devuelve la forma padre o null si el objeto padre no implementa la interfaz IShape. Sólo lectura [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Estas aserciones son siempre verdaderas
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Devuelve la celda padre o null si el objeto padre no implementa la interfaz ICell. Sólo lectura [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Estas aserciones son siempre verdaderas
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Devuelve:**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Une ejecuciones con el mismo formato en todos los párrafos.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Resalta todas las coincidencias del texto de ejemplo con el color especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Divide el contenido de texto del [ITextFrame](../../com.aspose.slides/itextframe) en una matriz de cadenas, donde cada elemento corresponde a una columna de texto separada dentro del marco.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Obtén la primera forma en la diapositiva y conviértela a ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Divide el contenido del frame de texto en columnas
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Imprime el texto de cada columna en la consola
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
java.lang.String[] - Una matriz de cadenas, donde cada cadena representa el contenido de texto de una columna específica en el [ITextFrame](../../com.aspose.slides/itextframe).

If the text frame does not contain multiple columns, the returned array will have a single element containing the full text. Empty columns will be represented as empty strings in the array.

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Resalta todas las coincidencias del texto de ejemplo con el color especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opciones de resaltado. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Resalta todas las coincidencias del texto de ejemplo con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // resaltando todas las palabras 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // resaltando todas las ocurrencias separadas de 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | El texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Resalta todas las coincidencias de la expresión regular con el color especificado.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // resaltando todas las palabras con 5 símbolos o más
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener cadenas a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Resalta todas las coincidencias de la expresión regular con el color especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.lang.String | Texto de la expresión regular para obtener texto a resaltar. |
| highlightColor | java.lang.Integer | El color para resaltar el texto. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Opciones de resaltado. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Reemplaza todas las apariciones del texto especificado con otro texto especificado.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Reemplaza todas las ocurrencias separadas de 'the' con '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| oldText | java.lang.String | La cadena a reemplazar. |
| newText | java.lang.String | La cadena para reemplazar todas las apariciones de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opciones de búsqueda de texto [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Reemplaza todas las coincidencias de la expresión regular con la cadena especificada.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Reemplaza todas las palabras con 5 símbolos o más con '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| regex | java.util.regex.Pattern | La expresión regular java.util.regex.Pattern para obtener cadenas a reemplazar. |
| newText | java.lang.String | La cadena para reemplazar todas las apariciones de las cadenas a ser reemplazadas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | El objeto de devolución de llamada para recibir resultados de búsqueda [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
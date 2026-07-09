---
title: ITextFrame
second_title: Aspose.Slides pour Android via la référence d'API Java
description: Représente un TextFrame.
type: docs
url: /fr/com.aspose.slides/itextframe/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Représente un TextFrame.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Renvoie la liste de tous les paragraphes d'un cadre. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'un TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'un TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Renvoie l'objet de formatage pour cet objet TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [getParentShape()](#getParentShape--) | Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape. Lecture seule [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les portions avec le même formatage dans tous les paragraphes. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [splitTextByColumns()](#splitTextByColumns--) | Divise le contenu texte du [ITextFrame](../../com.aspose.slides/itextframe) en un tableau de chaînes, où chaque élément correspond à une colonne de texte distincte dans le cadre. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Met en surbrillance toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Renvoie la liste de tous les paragraphes d'un cadre. Lecture seule [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Renvoie :**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String.

Valeur : Le texte.

**Renvoie :**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String.

Valeur : Le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Renvoie l'objet de formatage pour cet objet TextFrame. Lecture seule [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Renvoie :**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fournit un accès facile aux hyperliens contenus. Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie :**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape. Lecture seule [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // These assertions are always true
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Returns the parent cell or null if the parent object does not implement the ICell interface. Read-only [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Ces assertions sont toujours vraies
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[ICell](../../com.aspose.slides/icell)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Highlights all matches of the sample text with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Splits the text content of the [ITextFrame](../../com.aspose.slides/itextframe) into an array of strings, where each element corresponds to a separate text column within the frame.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Obtenir la première forme sur la diapositive et la caster en ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Diviser le contenu du texte du cadre en colonnes
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Imprimer le texte de chaque colonne dans la console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String[] - An array of strings, where each string represents the text content of a specific column in the [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

If the text frame does not contain multiple columns, the returned array will have a single element containing the full text. Empty columns will be represented as empty strings in the array.
### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Highlights all matches of the sample text with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // mise en surbrillance de tous les mots 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // mise en surbrillance de toutes les occurrences séparées de 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Highlights all matches of the regular expression with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // mise en surbrillance de tous les mots de 5 caractères ou plus
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Highlights all matches of the regular expression with the specified color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Text of regular expression to get text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Replaces all occurrences of the specified text with another specified text.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplace toutes les occurrences séparées de 'the' par '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | The string to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)


Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Replace all words with 5 symbols or longer with '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à remplacer. |
| newText | java.lang.String | La chaîne pour remplacer toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
---
title: TextFrame
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un TextFrame.
type: docs
url: /fr/com.aspose.slides/textframe/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées :**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Représente un TextFrame.

## Méthodes

| Méthode | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Renvoie la liste de tous les paragraphes d'un cadre. |
| [getText()](#getText--) | Obtient ou définit le texte brut d'un TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Obtient ou définit le texte brut d'un TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Renvoie l'objet de mise en forme pour cet objet TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joint les segments avec la même mise en forme dans tous les paragraphes. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [splitTextByColumns()](#splitTextByColumns--) | Divise le contenu texte du [ITextFrame](../../com.aspose.slides/itextframe) en un tableau de chaînes, chaque élément correspondant à une colonne de texte distincte dans le cadre. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Remplace toutes les occurrences du texte spécifié par un autre texte spécifié. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée. |
| [getSlide()](#getSlide--) | Renvoie la diapositive parente d'un TextFrame. |
| [getPresentation()](#getPresentation--) | Renvoie la présentation parente d'un TextFrame. |
| [getParentShape()](#getParentShape--) | Renvoie la forme parente ou null si l'objet parent n'implémente pas l'interface IShape. Lecture seule [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface ICell. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Renvoie l'objet Parent_Immediate. Lecture seule IDOMObject.

**Renvoie:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Renvoie la liste de tous les paragraphes d'un cadre. Lecture seule [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Renvoie:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String.

Valeur : le texte.

**Renvoie:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String.

Valeur : le texte.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Renvoie l'objet de mise en forme pour cet objet TextFrame. Lecture seule [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Renvoie:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Fournit un accès facile aux hyperliens contenus. Lecture seule [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Renvoie:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Joint les segments avec la même mise en forme dans tous les paragraphes.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Échantillon de texte à surligner. |
| highlightColor | java.awt.Color | Couleur à utiliser pour surligner le texte. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // surligner tous les mots 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // surligner toutes les occurrences séparées de 'the'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à surligner. |
| highlightColor | java.awt.Color | La couleur à surligner le texte. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Options de surlignage. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Divise le contenu texte du [ITextFrame](../../com.aspose.slides/itextframe) en un tableau de chaînes, chaque élément correspondant à une colonne de texte distincte dans le cadre.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Obtenir la première forme sur la diapositive et la convertir en ITextFrame
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


**Renvoie:**
java.lang.String[] - Un tableau de chaînes, chaque chaîne représentant le contenu texte d'une colonne spécifique dans le [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Si le cadre texte ne contient pas plusieurs colonnes, le tableau renvoyé contiendra un seul élément contenant le texte complet. Les colonnes vides seront représentées par des chaînes vides dans le tableau.

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // surligner tous les mots 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // surligner toutes les occurrences séparées de 'the'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à surligner. |
| highlightColor | java.awt.Color | La couleur à surligner le texte. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // surligner tous les mots de 10 caractères ou plus
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Texte de l'expression régulière à surligner. |
| highlightColor | java.awt.Color | Couleur à utiliser pour surligner le texte. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Options de surlignage. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // surligner tous les mots de 5 caractères ou plus
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à surligner. |
| highlightColor | java.awt.Color | Couleur à utiliser pour surligner le texte. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplacer toutes les occurrences séparées de 'the' par '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | Chaîne à remplacer. |
| newText | java.lang.String | Chaîne qui remplacera toutes les occurrences de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour enregistrer le résultat de l'opération de remplacement [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Remplacer tous les mots de 5 caractères ou plus par '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern dont les chaînes seront remplacées. |
| newText | java.lang.String | Chaîne qui remplacera toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objet de rappel pour enregistrer le résultat de l'opération de remplacement [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Renvoie la diapositive parente d'un TextFrame. Lecture seule [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Renvoie:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Renvoie la présentation parente d'un TextFrame. Lecture seule [IPresentation](../../com.aspose.slides/ipresentation).

**Renvoie:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
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
>      // Ces assertions sont toujours vraies
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Renvoie la cellule parente ou null si l'objet parent n'implémente pas l'interface ICell. Lecture seule [ICell](../../com.aspose.slides/icell).

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
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie:**
[ICell](../../com.aspose.slides/icell)
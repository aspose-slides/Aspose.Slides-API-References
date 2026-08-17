---
title: ITextFrame
second_title: Référence de l'API Aspose.Slides pour Java
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
| [getTextFrameFormat()](#getTextFrameFormat--) | Renvoie l'objet de mise en forme pour cet objet TextFrame. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fournit un accès facile aux hyperliens contenus. |
| [getParentShape()](#getParentShape--) | Renvoie la forme parent ou null si l'objet parent n'implémente pas l'interface IShape Lecture seule [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Renvoie la cellule parent ou null si l'objet parent n'implémente pas l'interface ICell. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fusionne les segments avec la même mise en forme dans tous les paragraphes. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [splitTextByColumns()](#splitTextByColumns--) | Divise le contenu texte du [ITextFrame](../../com.aspose.slides/itextframe) en un tableau de chaînes, chaque élément correspondant à une colonne texte distincte dans le cadre. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée. |
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

Valeur : le texte.

**Renvoie :**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Obtient ou définit le texte brut d'un TextFrame. Lecture/écriture String.

Valeur : le texte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Renvoie l'objet de mise en forme pour cet objet TextFrame. Lecture seule [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

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

Renvoie la forme parent ou null si l'objet parent n'implémente pas l'interface IShape Lecture seule [IShape](../../com.aspose.slides/ishape).

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

**Renvoie :**  
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Renvoie la cellule parent ou null si l'objet parent n'implémente pas l'interface ICell. Lecture seule [ICell](../../com.aspose.slides/icell).

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
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Renvoie :**  
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Fusionne les segments avec la même mise en forme dans tous les paragraphes.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à surligner. |
| highlightColor | java.awt.Color | La couleur pour surligner le texte. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Divise le contenu texte du [ITextFrame](../../com.aspose.slides/itextframe) en un tableau de chaînes, chaque élément correspondant à une colonne texte distincte dans le cadre.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Obtenir la première forme sur la diapositive et la convertir en ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Diviser le contenu du cadre texte en colonnes
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Imprimer le texte de chaque colonne dans la console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Renvoie :**  
java.lang.String[] - Un tableau de chaînes, où chaque chaîne représente le contenu texte d'une colonne spécifique dans le [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

Si le cadre texte ne contient pas plusieurs colonnes, le tableau retourné contiendra un seul élément contenant le texte complet. Les colonnes vides seront représentées par des chaînes vides dans le tableau.

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Surligne toutes les correspondances du texte d'exemple avec la couleur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à surligner. |
| highlightColor | java.awt.Color | La couleur pour surligner le texte. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Options de surlignage. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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
>      // highlighting all words 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Le texte à surligner. |
| highlightColor | java.awt.Color | La couleur pour surligner le texte. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
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


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'expression régulière java.util.regex.Pattern pour obtenir les chaînes à surligner. |
| highlightColor | java.awt.Color | La couleur pour surligner le texte. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Surligne toutes les correspondances de l'expression régulière avec la couleur spécifiée.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Texte de l'expression régulière pour obtenir le texte à surligner. |
| highlightColor | java.awt.Color | La couleur pour surligner le texte. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Options de surlignage. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Remplace toutes les occurrences du texte spécifié par un autre texte spécifié.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Remplacer toutes les occurrences distinctes de 'the' par '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | La chaîne à remplacer. |
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences de oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Options de recherche de texte [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Remplace toutes les correspondances de l'expression régulière par la chaîne spécifiée.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Remplacer tous les mots de 5 symboles ou plus par '***'
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
| newText | java.lang.String | La chaîne qui remplace toutes les occurrences des chaînes à remplacer. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'objet de rappel pour recevoir les résultats de recherche [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
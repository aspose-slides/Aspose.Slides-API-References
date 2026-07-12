---
title: ITextFrame
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt ein TextFrame dar.
type: docs
url: /de/com.aspose.slides/itextframe/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Stellt ein TextFrame dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Gibt die Liste aller Absätze in einem Frame zurück. |
| [getText()](#getText--) | Liest oder setzt den Klartext für ein TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Klartext für ein TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf enthaltene Hyperlinks. |
| [getParentShape()](#getParentShape--) | Gibt das übergeordnete Shape zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur lesend [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fügt Laufabschnitte mit gleicher Formatierung in allen Absätzen zusammen. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [splitTextByColumns()](#splitTextByColumns--) | Teilt den Textinhalt von [ITextFrame](../../com.aspose.slides/itextframe) in ein Array von Zeichenketten, wobei jedes Element einer separaten Textspalte im Frame entspricht. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Gibt die Liste aller Absätze in einem Frame zurück. Nur lesend [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Rückgabe:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Liest oder setzt den Klartext für ein TextFrame. Lese/Schreib String.

Wert: Der Text.

**Rückgabe:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Liest oder setzt den Klartext für ein TextFrame. Lese/Schreib String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück. Nur lesend [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Rückgabe:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesend [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabe:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Gibt das übergeordnete Shape zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur lesend [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Diese Assertions sind immer wahr
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert. Nur lesend [ICell](../../com.aspose.slides/icell).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Diese Assertions sind immer wahr
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Rückgabe:**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Fügt Laufabschnitte mit gleicher Formatierung in allen Absätzen zusammen.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text hervorgehoben werden soll. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Teilt den Textinhalt von [ITextFrame](../../com.aspose.slides/itextframe) in ein Array von Zeichenketten, wobei jedes Element einer separaten Textspalte im Frame entspricht.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Holen Sie das erste Shape auf der Folie und casten Sie es zu ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Teilen Sie den Inhalt des TextFrames in Spalten
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Geben Sie den Text jeder Spalte in der Konsole aus
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
java.lang.String[] - Ein Array von Zeichenketten, wobei jede Zeichenkette den Textinhalt einer bestimmten Spalte im [ITextFrame](../../com.aspose.slides/itextframe) darstellt.

--------------------

Wenn das TextFrame nicht mehrere Spalten enthält, hat das zurückgegebene Array ein einzelnes Element, das den gesamten Text enthält. Leere Spalten werden im Array als leere Zeichenketten dargestellt.

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text hervorgehoben werden soll. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Hervorhebungsoptionen. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Hervorhebung aller Wörter 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // Hervorhebung aller einzelnen 'the' Vorkommen
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text hervorgehoben werden soll. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuche-Optionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Hervorhebung aller Wörter mit 5 oder mehr Symbolen
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um Zeichenketten zum Hervorheben zu erhalten. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text hervorgehoben werden soll. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.lang.String | Text des regulären Ausdrucks, um Text zum Hervorheben zu erhalten. |
| highlightColor | java.lang.Integer | Die Farbe, mit der der Text hervorgehoben werden soll. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Hervorhebungsoptionen. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersetzt alle einzelnen 'the'-Vorkommen durch '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | java.lang.String | Der zu ersetzende String. |
| newText | java.lang.String | Der String, der alle Vorkommen von oldText ersetzen soll. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuche-Optionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Ersetzt alle Wörter mit 5 Symbolen oder länger durch '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um Zeichenketten zu ersetzen. |
| newText | java.lang.String | Der String, der alle Vorkommen der zu ersetzenden Zeichenketten ersetzt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
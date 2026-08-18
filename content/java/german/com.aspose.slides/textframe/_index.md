---
title: TextFrame
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen TextFrame dar.
type: docs
url: /de/com.aspose.slides/textframe/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Stellt einen TextFrame dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Gibt die Liste aller Absätze in einem Rahmen zurück. |
| [getText()](#getText--) | Liest oder setzt den Klartext für einen TextFrame. |
| [setText(String value)](#setText-java.lang.String-) | Liest oder setzt den Klartext für einen TextFrame. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf enthaltene Hyperlinks. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor. |
| [splitTextByColumns()](#splitTextByColumns--) | Teilt den Textinhalt von [ITextFrame](../../com.aspose.slides/itextframe) in ein Array von Zeichenketten, wobei jedes Element einer separaten Textspalte im Rahmen entspricht. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines TextFrames zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines TextFrames zurück. |
| [getParentShape()](#getParentShape--) | Gibt die übergeordnete Form zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur lesend [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesend IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Gibt die Liste aller Absätze in einem Rahmen zurück. Nur lesend [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Rückgabe:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Liest oder setzt den Klartext für einen TextFrame. Lesen/Schreiben String.

Wert: Der Text.

**Rückgabe:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Liest oder setzt den Klartext für einen TextFrame. Lesen/Schreiben String.

Wert: Der Text.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Gibt das Formatierungsobjekt für dieses TextFrame-Objekt zurück. Nur lesend [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Rückgabe:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesend [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabe:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Verbindet Läufe mit gleicher Formatierung in allen Absätzen.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Textprobe zum Hervorheben. |
| highlightColor | java.awt.Color | Die Farbe zum Hervorheben des Textes. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor.

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // highlighting all words 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // highlighting all separate 'the' occurrences
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.awt.Color | Die Farbe zum Hervorheben des Textes. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Hervorhebungsoptionen. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Teilt den Textinhalt von [ITextFrame](../../com.aspose.slides/itextframe) in ein Array von Zeichenketten, wobei jedes Element einer separaten Textspalte im Rahmen entspricht.

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Get the first shape on the slide and cast it to ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Split the text frame content into columns
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Print each column's text to the console
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
java.lang.String[] - Ein Array von Zeichenketten, wobei jede Zeichenkette den Textinhalt einer bestimmten Spalte im [ITextFrame](../../com.aspose.slides/itextframe) darstellt.

Falls der Textframe keine mehreren Spalten enthält, hat das zurückgegebene Array ein einzelnes Element, das den gesamten Text enthält. Leere Spalten werden im Array als leere Zeichenketten dargestellt.

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Hebt alle Treffer des Beispiels-Texts mit der angegebenen Farbe hervor.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| text | java.lang.String | Der zu hervorhebende Text. |
| highlightColor | java.awt.Color | Die Farbe zum Hervorheben des Textes. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor.

> ```
> Das folgende Codebeispiel zeigt, wie man Text in einem TextFrame mit einem regulären Ausdruck hervorhebt.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // Alle Wörter mit 10 Zeichen oder länger hervorheben
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.lang.String | Text des regulären Ausdrucks, dessen Treffer hervorgehoben werden sollen. |
| highlightColor | java.awt.Color | Die Farbe zum Hervorheben des Textes. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Hervorhebungsoptionen. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Alle Wörter mit 5 Zeichen oder länger hervorheben
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um die zu highlightenden Zeichenketten zu erhalten. |
| highlightColor | java.awt.Color | Die Farbe zum Hervorheben des Textes. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Das Callback-Objekt zum Empfangen von Suchergebnissen [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text.

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersetze alle einzelnen 'the'-Vorkommen durch '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| oldText | java.lang.String | Der zu ersetzende Zeichenkette. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen von oldText ersetzt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsuchoptionen [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-Objekt zum Speichern des Ergebnisses der Ersetzungsoperation [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette.

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Ersetze alle Wörter mit 5 Zeichen oder länger durch '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Der reguläre Ausdruck java.util.regex.Pattern, um die zu ersetzenden Zeichenketten zu erhalten. |
| newText | java.lang.String | Die Zeichenkette, die alle Vorkommen der zu ersetzenden Zeichenketten ersetzt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-Objekt zum Speichern des Ergebnisses der Ersetzungsoperation [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines TextFrames zurück. Nur lesend [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines TextFrames zurück. Nur lesend [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Gibt die übergeordnete Form zurück oder null, wenn das übergeordnete Objekt das IShape-Interface nicht implementiert. Nur lesend [IShape](../../com.aspose.slides/ishape).

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
public final ICell getParentCell()
```

Gibt die übergeordnete Zelle zurück oder null, wenn das übergeordnete Objekt das ICell-Interface nicht implementiert. Nur lesend [ICell](../../com.aspose.slides/icell).

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

**Rückgabe:**
[ICell](../../com.aspose.slides/icell)
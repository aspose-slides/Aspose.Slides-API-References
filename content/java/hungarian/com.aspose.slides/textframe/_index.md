---
title: TextFrame
second_title: Aspose.Slides Java API referencia
description: A TextFrame-et képviseli.
type: docs
url: /hu/com.aspose.slides/textframe/
---
**Öröklés:**
java.lang.Object

**Az összes implementált interfész:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

A TextFrame-et képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Visszaadja a keret összes bekezdésének listáját. |
| [getText()](#getText--) | Lekérdezi vagy beállítja a TextFrame egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekérdezi vagy beállítja a TextFrame egyszerű szövegét. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti az azonos formázású futamokat az összes bekezdésben. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [splitTextByColumns()](#splitTextByColumns--) | Felosztja a(z) [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc-tömbbé, ahol minden elem a kereten belüli külön szövegoszlopnak felel meg. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes találatát a megadott karakterláncra. |
| [getSlide()](#getSlide--) | Visszaadja egy TextFrame szülődiapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja egy TextFrame szülő prezentációját. |
| [getParentShape()](#getParentShape--) | Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Lekérdezi a szülő alakzat geometria által definiált szövegtéglalapot. |
| [getParentCell()](#getParentCell--) | Visszaadja a szülő cellát, vagy null értéket, ha a szülő objektum nem valósítja meg az ICell interfészt. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszaad:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Visszaadja a keret összes bekezdésének listáját. Csak olvasható [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Visszaad:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Lekérdezi vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Visszaad:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lekérdezi vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz. Csak olvasható [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Visszaad:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszaad:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Egyesíti az azonos formázású futamokat az összes bekezdésben.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Kiemeli a minta szöveg összes egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg minta. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Kiemeli a minta szöveg összes egyezését a megadott színnel.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Felosztja a(z) [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc-tömbbé, ahol minden elem a kereten belüli külön szövegoszlopnak felel meg.

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

**Visszaad:**
java.lang.String[] - Egy karakterlánc-tömb, ahol minden karakterlánc egy adott oszlop szövegtartalmát reprezentálja a [ITextFrame](../../com.aspose.slides/itextframe)-ben.

Ha a szövegkeret nem tartalmaz több oszlopot, a visszaadott tömb egyetlen elemet tartalmaz, amely a teljes szöveget tartalmazza. Üres oszlopok üres karakterláncokként lesznek ábrázolva a tömbben.

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a minta szöveg összes egyezését a megadott színnel.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // a 10 vagy több szimbólumú összes szó kiemelése
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.lang.String | A reguláris kifejezés szövege a kiemelendő szöveghez. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // az összes 5 vagy több szimbólumú szó kiemelése
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A java.util.regex.Pattern típusú reguláris kifejezés a kiemelendő karakterláncokhoz. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Az összes különálló 'the' előfordulást cseréli '***'-ra
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | java.lang.String | A lecserélendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amely minden előfordulást lecserél az oldText-re. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Visszahívási objektum a csere művelet eredményének mentéséhez [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Az összes 5 vagy több szimbólumú szót cseréli '***'-ra
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A java.util.regex.Pattern típusú reguláris kifejezés a lecserélendő karakterláncokhoz. |
| newText | java.lang.String | A karakterlánc, amely a lecserélendő karakterláncok összes előfordulását lecseréli. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Visszahívási objektum a csere művelet eredményének mentéséhez [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a TextFrame szülődiapozitívját. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszaad:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a TextFrame szülőprezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszaad:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape).

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Ezek az állítások mindig igazak
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszaad:**
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

Lekérdezi a szülő alakzat geometria által definiált szövegtéglalapot.

**Visszaad:**
java.awt.geom.Rectangle2D.Float - Egy java.awt.geom.Rectangle2D.Float, amely meghatározza a szövegterületet.

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Visszaadja a szülő cellát, vagy null értéket, ha a szülő objektum nem valósítja meg az ICell interfészt. Csak olvasható [ICell](../../com.aspose.slides/icell).

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

**Visszaad:**
[ICell](../../com.aspose.slides/icell)
---
title: TextFrame
second_title: Aspose.Slides for Android a Java API hivatkozás
description: Egy TextFrame-et képvisel.
type: docs
url: /hu/com.aspose.slides/textframe/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

A TextFrame-et képviseli.
## Metódusok

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Visszatér a keretben lévő összes bekezdés listájával. |
| [getText()](#getText--) | Lekéri vagy beállítja a TextFrame egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a TextFrame egyszerű szövegét. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Visszatér ennek a TextFrame objektumnak a formázási objektumával. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összekapcsolja az azonos formázású futamokat az összes bekezdésben. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Kiemeli a minta szöveg minden egyezését a megadott színnel. |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a minta szöveg minden egyezését a megadott színnel. |
| [splitTextByColumns()](#splitTextByColumns--) | Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbre, ahol minden elem a kereten belüli külön szövegoszlopnak felel meg. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a minta szöveg minden egyezését a megadott színnel. |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a reguláris kifejezés minden egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés minden egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés minden egyezését a megadott karakterláncra. |
| [getSlide()](#getSlide--) | Visszatér a TextFrame szülő diájával. |
| [getPresentation()](#getPresentation--) | Visszatér a TextFrame szülő prezentációjával. |
| [getParentShape()](#getParentShape--) | Visszatér a szülő alakzattal, vagy null értékkel, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Visszatér a szülő cellával, vagy null értékkel, ha a szülő objektum nem valósítja meg az ICell interfészt. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

Visszatér a keretben lévő összes bekezdés listájával. Csak olvasható [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Visszatér:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Visszatér:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

Visszatér ennek a TextFrame objektumnak a formázási objektumával. Csak olvasható [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Egyszerű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Összekapcsolja az azonos formázású futamokat az összes bekezdésben.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Kiemeli a minta szöveg minden egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Kiemelendő szöveg minta. |
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

Kiemeli a minta szöveg minden egyezését a megadott színnel.

> ```
> A következő minta kód bemutatja, hogyan kell kiemelni a szöveget egy TextFrame-ben.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // az összes 'important' szó kiemelése
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // az összes különálló 'the' előfordulás kiemelése
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
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbre, ahol minden elem a kereten belüli külön szövegoszlopnak felel meg.

> ```
> A következő példa bemutatja, hogyan kell használni a #splitTextByColumns.splitTextByColumns-t:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Az első alakzat lekérése a dián, és átalakítása ITextFrame-re
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // A szövegkeret tartalmának felosztása oszlopokra
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Minden oszlop szövegének kiírása a konzolra
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
java.lang.String[] – Egy karakterlánc tömb, ahol minden karakterlánc a [ITextFrame](../../com.aspose.slides/itextframe) egy adott oszlopának szövegtartalmát képviseli.

Ha a szövegkeret nem tartalmaz több oszlopot, a visszatérő tömb egyetlen elemet tartalmaz a teljes szöveggel. Az üres oszlopok üres karakterláncokként jelennek meg a tömbben.

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a minta szöveg minden egyezését a megadott színnel.

> ```
> A következő kódrészlet bemutatja, hogyan kell kiemelni a szöveget egy TextFrame-ben.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // az összes 'important' szó kiemelése
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // az összes különálló 'the' előfordulás kiemelése
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
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

Kiemeli a reguláris kifejezés minden egyezését a megadott színnel.

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // az összes 10 vagy több szimbólumú szó kiemelése
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
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés minden egyezését a megadott színnel.

> ```
> A következő kódrészlet bemutatja, hogyan kell kiemelni a szöveget egy TextFrame-ben reguláris kifejezéssel.
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
| regex | java.util.regex.Pattern | A java.util.regex.Pattern reguláris kifejezés a kiemelendő karakterláncokhoz. |
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

> ```
> A következő minta kód bemutatja, hogyan lehet egy megadott karakterláncot egy másik megadott karakterláncra cserélni.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Az összes különálló 'the' előfordulás cseréje '***'-ra
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
| newText | java.lang.String | A karakterlánc, amely minden előfordulását lecseréli az oldText-nek. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Visszahívási objektum a helyettesítési művelet eredményének mentéséhez [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés minden egyezését a megadott karakterláncra.

> ```
> A következő minta kód bemutatja, hogyan lehet reguláris kifejezéssel helyettesíteni a szöveget egy megadott karakterláncra.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // az összes 5 vagy több szimbólumú szó cseréje '***'-ra
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A java.util.regex.Pattern reguláris kifejezés a lecserélendő karakterláncokhoz. |
| newText | java.lang.String | A karakterlánc, amely a lecserélendő karakterláncok minden előfordulását lecseréli. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Visszahívási objektum a helyettesítési művelet eredményének mentéséhez [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszatér a TextFrame szülő diájával. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszatér a TextFrame szülő prezentációjával. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

Visszatér a szülő alakzattal, vagy null értékkel, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape).

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


**Visszatér:**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

Visszatér a szülő cellával, vagy null értékkel, ha a szülő objektum nem valósítja meg az ICell interfészt. Csak olvasható [ICell](../../com.aspose.slides/icell).

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Ezek az állítások mindig igazak
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[ICell](../../com.aspose.slides/icell)
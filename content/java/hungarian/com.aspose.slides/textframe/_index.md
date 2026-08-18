---
title: TextFrame
second_title: Aspose.Slides Java API Referenciája
description: Egy TextFrame-et reprezentál.
type: docs
url: /hu/com.aspose.slides/textframe/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

Egy TextFrame-et ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | Visszaadja keretben található összes bekezdés listáját. |
| [getText()](#getText--) | Lekérdezi vagy beállítja egy TextFrame egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | A TextFrame egyszerű szövegét kérdezi le vagy állítja be. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Visszaadja a formázási objektumot ehhez a TextFrame objektumhoz. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti az azonos formázású run-okat az összes bekezdésben. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [splitTextByColumns()](#splitTextByColumns--) | Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbre, ahol minden elem a keretben lévő különálló szövegoszlopnak felel meg. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [getSlide()](#getSlide--) | Visszaadja egy TextFrame szülődiapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja egy TextFrame szülőprezentációját. |
| [getParentShape()](#getParentShape--) | Visszaadja a szülő alakzatot, vagy null értéket, ha a szülőobjektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape). |
| [getParentCell()](#getParentCell--) | Visszaadja a szülő cellát, vagy null értéket, ha a szülőobjektum nem valósítja meg az ICell interfészt. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Visszaad egy Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```


Visszaadja az összes bekezdés listáját egy keretben. Csak olvasható [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Visszatérési érték:**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```


Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

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

**Visszatér:**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít a tartalmazott hivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Összevonja a futamokat azonos formázással minden bekezdésben.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Kiemelendő szövegminta. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // az összes 'important' szót kiemeli
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // az összes különálló 'the' előfordulást kiemeli
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
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbbe, ahol minden elem a kereten belül egy külön szövegoszlopnak felel meg.

--------------------

> ```
> A következő példa bemutatja a #splitTextByColumns.splitTextByColumns használatát:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Az első alakzatot a dián lekéri és ITextFrame típusra konvertálja
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // A szövegkeret tartalmát oszlopokra bontja
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Minden oszlop szövegét kiírja a konzolra
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
java.lang.String[] - Egy karakterláncok tömbje, ahol minden karakterlánc egy adott oszlop szövegtartalmát képviseli a [ITextFrame](../../com.aspose.slides/itextframe)-ben.

--------------------

Ha a szövegkeret nem tartalmaz több oszlopot, a visszaadott tömb egyetlen elemet fog tartalmazni, amely az egész szöveget tartalmazza. Üres oszlopok a tömbben üres karakterláncként lesznek ábrázolva.
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Kiemeli a minta szöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // az összes 'important' szót kiemeli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // az összes különálló 'the' előfordulást kiemeli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.awt.Color | The color to highlight the text. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // a 10 vagy több szimbólumú összes szót kiemeli
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Text of regular expression to get text to highlight. |
| highlightColor | java.awt.Color | The color to highlight the text. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // a 5 vagy több szimbólumú összes szót kiemeli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | java.awt.Color | The color to highlight the text. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Az összes különálló 'the' előfordulást '***'-ra cseréli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | The string to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback object for saving replacement operation result [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // A 5 vagy több szimbólumú összes szót '***'-ra cseréli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of strings to be replaced. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback object for saving replacement operation result [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Ezek az ellenőrzések mindig igazak
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

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // Ezek az ellenőrzések mindig igazak
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[ICell](../../com.aspose.slides/icell)
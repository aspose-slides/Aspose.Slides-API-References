---
title: ITextFrame
second_title: Aspose.Slides Java API referencia
description: Egy TextFrame-et reprezentál.
type: docs
url: /hu/com.aspose.slides/itextframe/
---
**All Implemented Interfaces:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

Egy TextFrame-et képvisel.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | Visszaadja a keretben lévő összes bekezdés listáját. |
| [getText()](#getText--) | Lekéri vagy beállítja a TextFrame egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a TextFrame egyszerű szövegét. |
| [getTextFrameFormat()](#getTextFrameFormat--) | Visszaadja ennek a TextFrame objektumnak a formázási objektumát. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [getParentShape()](#getParentShape--) | Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape). |
| [getTextRect()](#getTextRect--) | Lekéri a szülő alakzat geometriája által meghatározott szövegtéglalapot. |
| [getParentCell()](#getParentCell--) | Visszaadja a szülő cellát, vagy null értéket, ha a szülő objektum nem valósítja meg az ICell interfészt. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a formázásban egyforma szakaszokat az összes bekezdésben. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [splitTextByColumns()](#splitTextByColumns--) | Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbbe, ahol minden elem egy külön szövegoszlopnak felel meg a keretben. |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg minden előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

Visszaadja a keretben lévő összes bekezdés listáját. Csak olvasható [IParagraphCollection](../../com.aspose.slides/iparagraphcollection).

**Visszatér:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Visszatér:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Lekéri vagy beállítja a TextFrame egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

Visszaadja ennek a TextFrame objektumnak a formázási objektumát. Csak olvasható [ITextFrameFormat](../../com.aspose.slides/itextframeformat).

**Visszatér:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

Visszaadja a szülő alakzatot, vagy null értéket, ha a szülő objektum nem valósítja meg az IShape interfészt. Csak olvasható [IShape](../../com.aspose.slides/ishape).

--------------------

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

### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

Lekéri a szülő alakzat geometriája által meghatározott szövegtéglalapot.

**Visszatér:**  
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float, amely meghatározza a szövegtérületet.

--------------------

A téglalap koordinátái a szülő alakzat bal felső sarkához relatívak.

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

Visszaadja a szülő cellát, vagy null értéket, ha a szülő objektum nem valósítja meg az ICell interfészt. Csak olvasható [ICell](../../com.aspose.slides/icell).

--------------------

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

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Egyesíti a formázásban egyforma szakaszokat az összes bekezdésben.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

Felosztja a [ITextFrame](../../com.aspose.slides/itextframe) szövegtartalmát egy karakterlánc tömbbe, ahol minden elem egy külön szövegoszlopnak felel meg a keretben.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // Szerezze meg az első alakzatot a dián, és alakítsa át ITextFrame-re
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // Ossza fel a szövegkeret tartalmát oszlopokra
>      String[] columnsText = textFrame.splitTextByColumns();
>      // Írassa ki minden oszlop szövegét a konzolra
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**  
java.lang.String[] - Egy karakterlánc tömb, ahol minden karakterlánc a [ITextFrame](../../com.aspose.slides/itextframe) egy adott oszlopának szövegtartalmát képviseli.

Ha a szövegkeret nem tartalmaz több oszlopot, a visszaadott tömb egyetlen elemet tartalmaz, amely a teljes szöveget tartalmazza. Üres oszlopok üres karakterláncként jelennek meg a tömbben.

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

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
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // az összes 5 vagy több szimbólumú szót kiemeli
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés (java.util.regex.Pattern), amely meghatározza a kiemelendő karakterláncokat. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.lang.String | A reguláris kifejezés szövege, amely meghatározza a kiemelendő szöveget. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használandó szín. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Kiemelési beállítások. |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Lecseréli a megadott szöveg minden előfordulását egy másik megadott szövegre.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Cserélje le az összes különálló 'the' előfordulást '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | java.lang.String | A cserélendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amely minden előfordulását lecseréli az oldText-nek. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // Cserélje le az összes 5 vagy több szimbólumú szót '***'-ra
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés (java.util.regex.Pattern), amely meghatározza a cserélendő karakterláncokat. |
| newText | java.lang.String | A karakterlánc, amely a cserélendő karakterláncok minden előfordulását helyettesíti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
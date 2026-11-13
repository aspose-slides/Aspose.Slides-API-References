---
title: TextFrame
second_title: Aspose.Slides for Java API 參考
description: 表示 TextFrame。
type: docs
url: /zh-hant/com.aspose.slides/textframe/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject
```
public final class TextFrame implements ITextFrame, IDOMObject
```

表示 TextFrame。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | 返回框架中所有段落的列表。 |
| [getText()](#getText--) | 取得或設定 TextFrame 的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定 TextFrame 的純文字。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | 返回此 TextFrame 物件的格式化物件。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對包含之超連結的簡易存取。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併所有段落中格式相同的執行段。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [splitTextByColumns()](#splitTextByColumns--) | 將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容分割成字串陣列，每個元素對應框架內的獨立文字欄。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 以指定顏色突顯正規表達式的所有匹配項目。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯正規表達式的所有匹配項目。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將所有指定文字的出現替換為另一指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將正規表達式的所有匹配項目替換為指定字串。 |
| [getSlide()](#getSlide--) | 返回 TextFrame 的父投影片。 |
| [getPresentation()](#getPresentation--) | 返回 TextFrame 的父簡報。 |
| [getParentShape()](#getParentShape--) | 返回父形狀；如果父物件未實作 IShape 介面則返回 null。唯讀 [IShape](../../com.aspose.slides/ishape)。 |
| [getTextRect()](#getTextRect--) | 取得由父形狀幾何形狀定義的文字矩形。 |
| [getParentCell()](#getParentCell--) | 返回父儲存格；如果父物件未實作 ICell 介面則返回 null。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**返回：**
com.aspose.slides.IDOMObject
### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

返回框架中所有段落的清單。唯讀 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**返回：**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)
### getText() {#getText--}
```
public final String getText()
```

取得或設定 TextFrame 的純文字。可讀寫 String。

值：文字。

**返回：**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

取得或設定 TextFrame 的純文字。可讀寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

返回此 TextFrame 物件的格式化物件。唯讀 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**返回：**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供對包含之超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

合併所有段落中格式相同的執行段。
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

以指定顏色突顯樣本文本的所有匹配項目。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字樣本。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

以指定顏色突顯樣本文本的所有匹配項目。

--------------------

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字樣本。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |
### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容分割成字串陣列，每個元素對應框架內的獨立文字欄。

--------------------

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

**返回：**
java.lang.String[] - 一個字串陣列，每個字串代表 [ITextFrame](../../com.aspose.slides/itextframe) 中特定欄位的文字內容。

--------------------

如果文字框未包含多個欄位，返回的陣列將僅有一個元素，包含完整文字。空欄位將以空字串表示於陣列中。
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定顏色突顯樣本文本的所有匹配項目。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字樣本。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

以指定顏色突顯正規表達式的所有匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // highlighting all words with 10 symbols or longer
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.lang.String | 用於取得要突顯文字的正規表達式文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

以指定顏色突顯正規表達式的所有匹配項目。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 突顯所有長度為 5 個符號或更長的字詞
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜尋結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將所有指定文字的出現替換為另一指定文字。

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 替換所有獨立的 'the' 出現為 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 取代 oldText 所有出現的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於儲存取代操作結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將正規表達式的所有匹配項目替換為指定字串。

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 將所有長度為 5 個符號或更長的字詞替換為 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要被取代字串的正規表達式 java.util.regex.Pattern。 |
| newText | java.lang.String | 取代所有被取代字串出現的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於儲存取代操作結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 TextFrame 的父投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回：**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 TextFrame 的父簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回：**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

返回父形狀；如果父物件未實作 IShape 介面則返回 null。唯讀 [IShape](../../com.aspose.slides/ishape)。

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 這些斷言永遠為真
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[IShape](../../com.aspose.slides/ishape)
### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

取得由父形狀幾何形狀定義的文字矩形。

**返回：**
java.awt.geom.Rectangle2D.Float - 定義文字區域的 java.awt.geom.Rectangle2D.Float。
### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

返回父儲存格；如果父物件未實作 ICell 介面則返回 null。唯讀 [ICell](../../com.aspose.slides/icell)。

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 這些斷言永遠為真
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[ICell](../../com.aspose.slides/icell)
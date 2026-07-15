---
title: TextFrame
second_title: Aspose.Slides for Android 的 Java API 參考
description: 表示一個 TextFrame。
type: docs
url: /zh-hant/com.aspose.slides/textframe/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

代表一個 TextFrame。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | 傳回框架中所有段落的列表。 |
| [getText()](#getText--) | 取得或設定 TextFrame 的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定 TextFrame 的純文字。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | 傳回此 TextFrame 物件的格式化物件。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對所包含超連結的簡易存取。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併所有段落中格式相同的文字區段。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 以指定的顏色突顯樣本文本的所有匹配項。 |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 以指定的顏色突顯樣本文本的所有匹配項。 |
| [splitTextByColumns()](#splitTextByColumns--) | 將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容切割成字串陣列，每個元素對應框架內的單獨文字欄。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定的顏色突顯樣本文本的所有匹配項。 |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 以指定的顏色突顯正規表達式的所有匹配項。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 以指定的顏色突顯正規表達式的所有匹配項。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將指定文字的所有出現取代為另一指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將正規表達式的所有匹配取代為指定字串。 |
| [getSlide()](#getSlide--) | 傳回 TextFrame 所屬的投影片。 |
| [getPresentation()](#getPresentation--) | 傳回 TextFrame 所屬的簡報。 |
| [getParentShape()](#getParentShape--) | 傳回父形狀，若父物件未實作 IShape 介面則傳回 null。唯讀 [IShape](../../com.aspose.slides/ishape)。 |
| [getParentCell()](#getParentCell--) | 傳回父儲存格，若父物件未實作 ICell 介面則傳回 null。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

傳回 Parent_Immediate 物件。唯讀 IDOMObject。

**傳回值:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

傳回框架中所有段落的列表。唯讀 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**傳回值:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

取得或設定 TextFrame 的純文字。可讀寫 String。

值：文字。

**傳回值:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

取得或設定 TextFrame 的純文字。可讀寫 String。

值：文字。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

傳回此 TextFrame 物件的格式化物件。唯讀 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**傳回值:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供對所包含超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**傳回值:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

合併所有段落中格式相同的文字區段。

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

以指定的顏色突顯樣本文本的所有匹配項。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字樣本。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

以指定的顏色突顯樣本文本的所有匹配項。

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

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容切割成字串陣列，每個元素對應框架內的單獨文字欄。

--------------------

> ```
> 以下範例示範如何使用 #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 取得投影片上的第一個形狀並將其轉型為 ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 將文字框內容分割成欄位
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 將每個欄位的文字印出到主控台
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值:**  
java.lang.String[] - 一個字串陣列，每個字串代表 [ITextFrame](../../com.aspose.slides/itextframe) 中特定欄位的文字內容。

--------------------

若文字框未包含多欄，返回的陣列將只有一個元素，內含完整文字。空欄位將以空字串表示。

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定的顏色突顯樣本文本的所有匹配項。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 突顯所有單字 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 突顯所有單獨的 'the' 出現
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) 的回呼物件。 |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)
```

以指定的顏色突顯正規表達式的所有匹配項。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 突顯所有長度為 10 個字符或更長的單字
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.lang.String | 正規表達式文字，用於取得要突顯的文字。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

以指定的顏色突顯正規表達式的所有匹配項。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 突顯所有長度為 5 個字符或更長的單字
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式 java.util.regex.Pattern。 |
| highlightColor | java.lang.Integer | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於接收搜尋結果 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) 的回呼物件。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將指定文字的所有出現取代為另一指定文字。

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有獨立出現的 'the' 取代為 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| oldText | java.lang.String | 要被取代的字串。 |
| newText | java.lang.String | 用於取代所有 oldText 出現的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜尋選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於儲存取代作業結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將正規表達式的所有匹配取代為指定字串。

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 將所有長度為 5 個字符或更長的單詞取代為 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要被取代字串的正規表達式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用於取代所有被取代字串出現的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用於儲存取代作業結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

傳回 TextFrame 所屬的投影片。唯讀 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**傳回值:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

傳回 TextFrame 所屬的簡報。唯讀 [IPresentation](../../com.aspose.slides/ipresentation)。

**傳回值:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

傳回父形狀，若父物件未實作 IShape 介面則傳回 null。唯讀 [IShape](../../com.aspose.slides/ishape)。

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

**傳回值:**  
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

傳回父儲存格，若父物件未實作 ICell 介面則傳回 null。唯讀 [ICell](../../com.aspose.slides/icell)。

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

**傳回值:**  
[ICell](../../com.aspose.slides/icell)
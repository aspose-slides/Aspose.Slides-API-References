---
title: ITextFrame
second_title: Aspose.Slides for Java API 參考
description: 代表一個 TextFrame.
type: docs
url: /zh-hant/com.aspose.slides/itextframe/
---
**所有已實作的介面：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

代表一個 TextFrame。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | 返回框架中所有段落的列表。 |
| [getText()](#getText--) | 取得或設定 TextFrame 的純文字。 |
| [setText(String value)](#setText-java.lang.String-) | 取得或設定 TextFrame 的純文字。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | 返回此 TextFrame 物件的格式化物件。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供對所含超連結的簡易存取。 |
| [getParentShape()](#getParentShape--) | 返回父形狀；如果父物件未實作 IShape 介面則返回 null。唯讀 [IShape](../../com.aspose.slides/ishape)。 |
| [getTextRect()](#getTextRect--) | 取得由父形狀幾何形態定義的文字矩形。 |
| [getParentCell()](#getParentCell--) | 返回父儲存格；如果父物件未實作 ICell 介面則返回 null。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合併所有段落中具有相同格式的執行區段。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 以指定顏色突顯樣本文本的所有匹配項。 |
| [splitTextByColumns()](#splitTextByColumns--) | 將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容分割為字串陣列，每個元素對應框架內的單獨文字欄。 |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 以指定顏色突顯樣本文本的所有匹配項。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯樣本文本的所有匹配項。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 以指定顏色突顯正規表達式的所有匹配項。 |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 以指定顏色突顯正規表達式的所有匹配項。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 將所有指定文字的出現替換為另一個指定文字。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 將正規表達式的所有匹配項替換為指定的字串。 |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

返回框架中所有段落的列表。唯讀 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**返回值：**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

取得或設定 TextFrame 的純文字。讀寫 String。

值：文字。

**返回值：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

取得或設定 TextFrame 的純文字。讀寫 String。

值：文字。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

返回此 TextFrame 物件的格式化物件。唯讀 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**返回值：**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供對所含超連結的簡易存取。唯讀 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回值：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
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
>      // 這些斷言始終為真
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回值：**
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public abstract Rectangle2D.Float getTextRect()
```

取得由父形狀幾何形態定義的文字矩形。

**返回值：**
java.awt.geom.Rectangle2D.Float - 定義文字區域的 java.awt.geom.Rectangle2D.Float。

--------------------

文字矩形座標相對於父形狀的左上角。

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
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
>      // 這些斷言始終為真
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回值：**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

合併所有段落中具有相同格式的執行區段。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

以指定顏色突顯樣本文本的所有匹配項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

將 [ITextFrame](../../com.aspose.slides/itextframe) 的文字內容分割為字串陣列，每個元素對應框架內的單獨文字欄。

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 取得投影片上的第一個形狀並將其轉型為 ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 將文字框內容分割為多個欄位
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 將每個欄位的文字印出到主控台
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
java.lang.String[] - 每個字串代表 [ITextFrame](../../com.aspose.slides/itextframe) 中特定欄的文字內容。

--------------------

如果文字框未包含多個欄位，返回的陣列將只有一個元素，包含完整文字。空欄位將以空字串表示。

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

以指定顏色突顯樣本文本的所有匹配項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

以指定顏色突顯樣本文本的所有匹配項。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 突顯所有單詞 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 突顯所有單獨的 'the' 出現
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜索選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

以指定顏色突顯正規表達式的所有匹配項。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 突顯所有長度為 5 個或以上的字詞
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要突顯字串的正規表達式。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

以指定顏色突顯正規表達式的所有匹配項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.lang.String | 正規表達式的文字，用於取得要突顯的文字。 |
| highlightColor | java.awt.Color | 用於突顯文字的顏色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突顯選項。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

將所有指定文字的出現替換為另一個指定文字。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 將所有單獨的 'the' 出現取代為 '***'
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
| newText | java.lang.String | 用於取代所有 oldText 出現的字串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文字搜索選項 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

將正規表達式的所有匹配項替換為指定的字串。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 將所有長度為 5 個或以上的字詞取代為 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用於取得要取代字串的正規表達式。 |
| newText | java.lang.String | 用於取代所有要取代字串出現的字串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索結果的回呼物件 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。
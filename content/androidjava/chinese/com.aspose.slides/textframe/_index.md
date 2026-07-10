---
title: TextFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个 TextFrame。
type: docs
url: /zh/com.aspose.slides/textframe/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.ITextFrame](../../com.aspose.slides/itextframe), com.aspose.slides.IDOMObject  
```
public final class TextFrame implements ITextFrame, IDOMObject
```

表示一个 TextFrame。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getParagraphs()](#getParagraphs--) | 返回帧中所有段落的列表。 |
| [getText()](#getText--) | 获取或设置 TextFrame 的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置 TextFrame 的纯文本。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | 返回此 TextFrame 对象的格式化对象。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对包含的超链接的便捷访问。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并所有段落中具有相同格式的文本段落。 |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [splitTextByColumns()](#splitTextByColumns--) | 将 [ITextFrame](../../com.aspose.slides/itextframe) 的文本内容拆分为字符串数组，每个元素对应帧内的单独文本列。 |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将指定文本的所有出现替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配项替换为指定字符串。 |
| [getSlide()](#getSlide--) | 返回 TextFrame 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 TextFrame 的父演示文稿。 |
| [getParentShape()](#getParentShape--) | 返回父形状，如果父对象未实现 IShape 接口则返回 null。只读 [IShape](../../com.aspose.slides/ishape)。 |
| [getParentCell()](#getParentCell--) | 返回父单元格，如果父对象未实现 ICell 接口则返回 null。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回值:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

返回帧中所有段落的列表。只读 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**返回值:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

获取或设置 TextFrame 的纯文本。读/写 String。

值：文本。

**返回值:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

获取或设置 TextFrame 的纯文本。读/写 String。

值：文本。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public final ITextFrameFormat getTextFrameFormat()
```

返回此 TextFrame 对象的格式化对象。只读 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**返回值:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供对包含的超链接的便捷访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回值:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

合并所有段落中具有相同格式的文本段落。

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

使用指定颜色突出显示样本文本的所有匹配项。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要高亮显示的文本样本。 |
| highlightColor | java.lang.Integer | 用于高亮显示文本的颜色。 |

### highlightText(String text, Integer highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Integer highlightColor, ITextHighlightingOptions options)
```

使用指定颜色突出显示样本文本的所有匹配项。

---

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### splitTextByColumns() {#splitTextByColumns--}
```  
public final String[] splitTextByColumns()  
```

Splits the text content of the [ITextFrame](../../com.aspose.slides/itextframe) into an array of strings, where each element corresponds to a separate text column within the frame.

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 获取幻灯片上的第一个形状并将其转换为 ITextFrame
>      ITextFrame textFrame = (ITextFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      // 将文本框内容拆分为列
>      String[] columnsText = textFrame.splitTextByColumns();
>      // 将每列的文本打印到控制台
>      for (String column : columnsText)
>          System.out.println(column);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
java.lang.String[] - An array of strings, where each string represents the text content of a specific column in the [ITextFrame](../../com.aspose.slides/itextframe).

--------------------

If the text frame does not contain multiple columns, the returned array will have a single element containing the full text. Empty columns will be represented as empty strings in the array.
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```  
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)  
```

Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 突出显示所有单词 'important'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("important", Color.BLUE);
>      // 突出显示所有独立的 'the' 出现
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | The text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Text search options [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.lang.Integer-com.aspose.slides.ITextHighlightingOptions-}
```  
public final void highlightRegex(String regex, Integer highlightColor, ITextHighlightingOptions options)  
```

Highlights all matches of the regular expression with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      TextHighlightingOptions options = new TextHighlightingOptions();
>      // 突出显示所有长度为10个字符或更长的单词
>      ((AutoShape) pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex("\\b[^\\s){5,}\\b", Color.BLUE, options);
>      pres.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.lang.String | Text of regular expression to get text to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | Highlighting options. |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```  
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)  
```

Highlights all matches of the regular expression with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 突出显示所有长度为5个字符或更长的单词
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to highlight. |
| highlightColor | java.lang.Integer | The color to highlight the text. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | The callback object for receiving search results [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```  
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)  
```

Replaces all occurrences of the specified text with another specified text.

--------------------

> ```
> The following sample code shows how to replace one speified string with another speified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有独立的 'the' 出现替换为 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
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

Replaces all matches of regular expression with specified string.

--------------------

> ```
> The following sample code shows how to replace text using regular expression with specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 将所有长度为5个字符或更长的单词替换为 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | The regular expression java.util.regex.Pattern to get strings to be replaced. |
| newText | java.lang.String | The string to replace all occurrences of strings to be replaced. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback object for saving replacement operation result [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### getSlide() {#getSlide--}
```  
public final IBaseSlide getSlide()  
```

Returns the parent slide of a TextFrame. Read-only [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```  
public final IPresentation getPresentation()  
```

Returns the parent presentation of a TextFrame. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParentShape() {#getParentShape--}
```  
public final IShape getParentShape()  
```

Returns the parent shape or null if the parent object does not implement the IShape interface Read-only [IShape](../../com.aspose.slides/ishape).

--------------------

> ```
> The following code sample shows 
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      AutoShape autoShape = (AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      Table table = (Table)presentation.getSlides().get_Item(0).getShapes().get_Item(1);
> 
>      // 这些断言始终为真
>      Assert.assertTrue(autoShape.getTextFrame().getParentShape() == autoShape);
>      Assert.assertTrue((table.get_Item(0,0).getTextFrame()).getParentShape() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### getParentCell() {#getParentCell--}
```  
public final ICell getParentCell()  

返回父单元格，如果父对象未实现 ICell 接口则返回 null。只读 [ICell](../../com.aspose.slides/icell)。

---

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

**返回值:**  
[ICell](../../com.aspose.slides/icell)
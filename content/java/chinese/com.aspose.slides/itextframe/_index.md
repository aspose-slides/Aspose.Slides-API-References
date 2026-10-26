---
title: ITextFrame
second_title: Aspose.Slides for Java API 参考
description: 表示一个 TextFrame。
type: docs
url: /zh/com.aspose.slides/itextframe/
---
**所有实现的接口：**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ITextFrame extends ISlideComponent
```

表示一个 TextFrame。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParagraphs()](#getParagraphs--) | 返回帧中所有段落的列表。 |
| [getText()](#getText--) | 获取或设置 TextFrame 的纯文本。 |
| [setText(String value)](#setText-java.lang.String-) | 获取或设置 TextFrame 的纯文本。 |
| [getTextFrameFormat()](#getTextFrameFormat--) | 返回此 TextFrame 对象的格式化对象。 |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对包含的超链接的简便访问。 |
| [getParentShape()](#getParentShape--) | 返回父形状，如果父对象未实现 IShape 接口则返回 null。只读 [IShape](../../com.aspose.slides/ishape)。 |
| [getParentCell()](#getParentCell--) | 返回父单元格，如果父对象未实现 ICell 接口则返回 null。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 合并所有段落中具有相同格式的运行。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [splitTextByColumns()](#splitTextByColumns--) | 将 [ITextFrame](../../com.aspose.slides/itextframe) 的文本内容拆分为字符串数组，每个元素对应框内的单独文本列。 |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示样本文本的所有匹配项。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将指定文本的所有出现替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配项替换为指定字符串。 |

### getParagraphs() {#getParagraphs--}
```
public abstract IParagraphCollection getParagraphs()
```

返回帧中所有段落的列表。只读 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**返回：**
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public abstract String getText()
```

获取或设置 TextFrame 的纯文本。读写 String。

值：文本。

**返回：**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

获取或设置 TextFrame 的纯文本。读写 String。

值：文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFrameFormat() {#getTextFrameFormat--}
```
public abstract ITextFrameFormat getTextFrameFormat()
```

返回此 TextFrame 对象的格式化对象。只读 [ITextFrameFormat](../../com.aspose.slides/itextframeformat)。

**返回：**
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

提供对包含的超链接的简便访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回：**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getParentShape() {#getParentShape--}
```
public abstract IShape getParentShape()
```

返回父形状，如果父对象未实现 IShape 接口则返回 null。只读 [IShape](../../com.aspose.slides/ishape)。

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


**返回：**
[IShape](../../com.aspose.slides/ishape)

### getParentCell() {#getParentCell--}
```
public abstract ICell getParentCell()
```

返回父单元格，如果父对象未实现 ICell 接口则返回 null。只读 [ICell](../../com.aspose.slides/icell)。

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
>      Assert.assertTrue(table.get_Item(0,0).getTextFrame().getParentCell() == table.get_Item(0,0));
>      Assert.assertTrue(autoShape.getTextFrame().getParentCell() == null);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**返回：**
[ICell](../../com.aspose.slides/icell)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

合并所有段落中具有相同格式的运行。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

使用指定颜色突出显示样本文本的所有匹配项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public abstract String[] splitTextByColumns()
```

将 [ITextFrame](../../com.aspose.slides/itextframe) 的文本内容拆分为字符串数组，每个元素对应框内的单独文本列。

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


**返回：**
java.lang.String[] - 一个字符串数组，每个字符串代表 [ITextFrame](../../com.aspose.slides/itextframe) 中特定列的文本内容。

如果文本框不包含多列，返回的数组将只有一个元素，包含完整文本。空列将在数组中表示为空字符串。

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

使用指定颜色突出显示样本文本的所有匹配项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突出显示选项。 |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

使用指定颜色突出显示样本文本的所有匹配项。

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
>      // 突出显示所有单独的 'the' 出现
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

使用指定颜色突出显示正则表达式的所有匹配项。

--------------------

> ```
> The following code sample shows how to highlight text in a TextFrame using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 突出显示所有 5 个字符或更长的单词
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要突出显示字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public abstract void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

使用指定颜色突出显示正则表达式的所有匹配项。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.lang.String | 正则表达式的文本，用于获取要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突出显示选项。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

将指定文本的所有出现替换为另一个指定文本。

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独的 'the' 出现替换为 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换 oldText 所有出现的字符串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

将正则表达式的所有匹配项替换为指定字符串。

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{5,}\\b");
>      // 将所有长度为 5 个字符或更长的单词替换为 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有待替换字符串的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |
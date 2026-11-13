---
title: TextFrame
second_title: Aspose.Slides 的 Java API 参考
description: 表示一个 TextFrame。
type: docs
url: /zh/com.aspose.slides/textframe/
---
**继承:**  
java.lang.Object

**全部已实现接口:**  
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
| [getHyperlinkQueries()](#getHyperlinkQueries--) | 提供对包含的超链接的简便访问。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | 在所有段落中将具有相同格式的运行合并。 |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [highlightText(String text, Color highlightColor, ITextHighlightingOptions options)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [splitTextByColumns()](#splitTextByColumns--) | 将 [ITextFrame](../../com.aspose.slides/itextframe) 的文本内容拆分为字符串数组，每个元素对应帧中的单独文本列。 |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示示例文本的所有匹配项。 |
| [highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)](#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | 使用指定颜色突出显示正则表达式的所有匹配项。 |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | 将所有指定文本的出现替换为另一个指定文本。 |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | 将正则表达式的所有匹配替换为指定字符串。 |
| [getSlide()](#getSlide--) | 返回 TextFrame 的父幻灯片。 |
| [getPresentation()](#getPresentation--) | 返回 TextFrame 的父演示文稿。 |
| [getParentShape()](#getParentShape--) | 返回父形状；如果父对象未实现 IShape 接口，则返回 null。只读 [IShape](../../com.aspose.slides/ishape)。 |
| [getTextRect()](#getTextRect--) | 获取由父形状几何定义的文本矩形。 |
| [getParentCell()](#getParentCell--) | 返回父单元格；如果父对象未实现 ICell 接口，则返回 null。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### getParagraphs() {#getParagraphs--}
```
public final IParagraphCollection getParagraphs()
```

返回帧中所有段落的列表。只读 [IParagraphCollection](../../com.aspose.slides/iparagraphcollection)。

**返回:**  
[IParagraphCollection](../../com.aspose.slides/iparagraphcollection)

### getText() {#getText--}
```
public final String getText()
```

获取或设置 TextFrame 的纯文本。读写 String。

值：文本。

**返回:**  
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

获取或设置 TextFrame 的纯文本。读写 String。

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

**返回:**  
[ITextFrameFormat](../../com.aspose.slides/itextframeformat)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

提供对包含的超链接的简便访问。只读 [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)。

**返回:**  
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

在所有段落中将具有相同格式的运行合并。

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

使用指定颜色突出显示示例文本的所有匹配项。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本示例。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |

### highlightText(String text, Color highlightColor, ITextHighlightingOptions options) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightText(String text, Color highlightColor, ITextHighlightingOptions options)
```

使用指定颜色突出显示示例文本的所有匹配项。

--------------------

> ```
> The following sample code shows how to Highlight Text in a TextFrame.
>  
>  try {
>      TextHighlightingOptions textHighlightingOptions = new TextHighlightingOptions();
>      textHighlightingOptions.setWholeWordsOnly(true);
>      // 突出显示所有单词 'important'
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("title", Color.BLUE);
>      // 突出显示所有单独的 'the' 出现
>      ((AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().highlightText("to", Color.MAGENTA, textHighlightingOptions);
>      pres.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突出显示选项。 |

### splitTextByColumns() {#splitTextByColumns--}
```
public final String[] splitTextByColumns()
```

将 [ITextFrame](../../com.aspose.slides/itextframe) 的文本内容拆分为字符串数组，每个元素对应帧中的单独文本列。

--------------------

> ```
> The following example demonstrates how to use #splitTextByColumns.splitTextByColumns:
>  
>  Presentation pres = new Presentation("example.pptx");
>  try {
>      // 获取幻灯片上的第一个形状并将其强制转换为 ITextFrame
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


**返回:**  
java.lang.String[] - 一个字符串数组，每个字符串表示 [ITextFrame](../../com.aspose.slides/itextframe) 中特定列的文本内容。

--------------------

如果文本框不包含多列，则返回的数组将只有一个包含完整文本的元素。空列将在数组中表示为空字符串。

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

使用指定颜色突出显示示例文本的所有匹配项。

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


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要突出显示的文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options) {#highlightRegex-java.lang.String-java.awt.Color-com.aspose.slides.ITextHighlightingOptions-}
```
public final void highlightRegex(String regex, Color highlightColor, ITextHighlightingOptions options)
```

使用指定颜色突出显示正则表达式的所有匹配项。

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


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.lang.String | 用于获取要突出显示文本的正则表达式文本。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| options | [ITextHighlightingOptions](../../com.aspose.slides/itexthighlightingoptions) | 突出显示选项。 |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

使用指定颜色突出显示正则表达式的所有匹配项。

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


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要突出显示字符串的正则表达式 java.util.regex.Pattern。 |
| highlightColor | java.awt.Color | 用于突出显示文本的颜色。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 接收搜索结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

将所有指定文本的出现替换为另一个指定文本。

--------------------

> ```
> 以下示例代码展示了如何将一个指定字符串替换为另一个指定字符串。
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // 将所有单独出现的 'the' 替换为 '***'
>      ((AutoShape)presentation.getSlides().get_Item(0).getShapes().get_Item(0)).getTextFrame().replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| oldText | java.lang.String | 要被替换的字符串。 |
| newText | java.lang.String | 用于替换所有 oldText 出现的字符串。 |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | 文本搜索选项 [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于保存替换操作结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

将正则表达式的所有匹配替换为指定字符串。

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


**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| regex | java.util.regex.Pattern | 用于获取要被替换字符串的正则表达式 java.util.regex.Pattern。 |
| newText | java.lang.String | 用于替换所有要被替换字符串出现的字符串。 |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | 用于保存替换操作结果的回调对象 [IFindResultCallback](../../com.aspose.slides/ifindresultcallback)。 |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

返回 TextFrame 的父幻灯片。只读 [IBaseSlide](../../com.aspose.slides/ibaseslide)。

**返回:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

返回 TextFrame 的父演示文稿。只读 [IPresentation](../../com.aspose.slides/ipresentation)。

**返回:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### getParentShape() {#getParentShape--}
```
public final IShape getParentShape()
```

返回父形状；如果父对象未实现 IShape 接口，则返回 null。只读 [IShape](../../com.aspose.slides/ishape)。

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


**返回:**  
[IShape](../../com.aspose.slides/ishape)

### getTextRect() {#getTextRect--}
```
public final Rectangle2D.Float getTextRect()
```

获取由父形状几何定义的文本矩形。

**返回:**  
java.awt.geom.Rectangle2D.Float - 一个定义文本区域的 java.awt.geom.Rectangle2D.Float。

### getParentCell() {#getParentCell--}
```
public final ICell getParentCell()
```

返回父单元格；如果父对象未实现 ICell 接口，则返回 null。只读 [ICell](../../com.aspose.slides/icell)。

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


**返回:**  
[ICell](../../com.aspose.slides/icell)
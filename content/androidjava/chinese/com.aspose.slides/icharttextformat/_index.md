---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Chart operate with restricted set of text format properties.
type: docs
url: /zh/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

图表使用受限的一组文本格式属性。IChartTextFormat、IChartTextBlockFormat、IChartParagraphFormat、IChartPortionFormat 接口描述了这组受限属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Returns format for the chart text elements. |
| [getParagraphFormat()](#getParagraphFormat--) | Returns paragraph format. |
| [getPortionFormat()](#getPortionFormat--) | Returns portion format. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Copies text format to specified text frame. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Copies text format from specified text frame. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```


返回图表文本元素的格式。只读 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)。

**返回：**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


返回段落格式。只读 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)。

**返回：**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


返回部分格式。只读 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat)。

**返回：**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


将文本格式复制到指定的文本框。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 要复制文本格式的文本框。 |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


从指定的文本框复制文本格式。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | 要复制文本格式的文本框。 |
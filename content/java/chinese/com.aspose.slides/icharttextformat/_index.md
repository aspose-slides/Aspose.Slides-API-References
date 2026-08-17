---
title: IChartTextFormat
second_title: Aspose.Slides for Java API Reference
description: 图表使用受限的文本格式属性进行操作。
type: docs
url: /zh/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

图表使用受限的文本格式属性进行操作。IChartTextFormat、IChartTextBlockFormat、IChartParagraphFormat、IChartPortionFormat 接口描述了此受限集合。
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


Returns format for the chart text elements. 只读 [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**返回:**  
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```


Returns paragraph format. 只读 [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**返回:**  
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```


Returns portion format. 只读 [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**返回:**  
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```


将文本格式复制到指定的文本框。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format to. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```


从指定的文本框复制文本格式。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Text frame to copy text format. |
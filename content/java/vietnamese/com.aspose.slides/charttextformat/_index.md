---
title: ChartTextFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Xác định định dạng văn bản mặc định cho các phần tử văn bản của biểu đồ.
type: docs
url: /vi/com.aspose.slides/charttextformat/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.IChartTextFormat](../../com.aspose.slides/icharttextformat), com.aspose.slides.IDOMObject
```
public class ChartTextFormat implements IChartTextFormat, IDOMObject
```

Xác định định dạng văn bản mặc định cho các phần tử văn bản của biểu đồ.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | TextBlockFormat. |
| [getParagraphFormat()](#getParagraphFormat--) | ParagraphFormat. |
| [getPortionFormat()](#getPortionFormat--) | PortionFormat. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Sao chép định dạng văn bản sang khung văn bản được chỉ định. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Sao chép định dạng văn bản từ khung văn bản được chỉ định. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public final IChartTextBlockFormat getTextBlockFormat()
```


TextBlockFormat. Chỉ đọc [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Trả về:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IChartParagraphFormat getParagraphFormat()
```


ParagraphFormat. Chỉ đọc [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Trả về:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public final IChartPortionFormat getPortionFormat()
```


PortionFormat. Chỉ đọc [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Trả về:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public final void copyTo(ITextFrame destTextFrame)
```


Sao chép định dạng văn bản sang khung văn bản được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Khung văn bản để sao chép định dạng văn bản tới. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public final void copyFrom(ITextFrame sourceTextFrame)
```


Sao chép định dạng văn bản từ khung văn bản được chỉ định.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Khung văn bản để sao chép định dạng văn bản. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
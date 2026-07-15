---
title: IChartTextFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu đồ hoạt động với một bộ giới hạn các thuộc tính định dạng văn bản.
type: docs
url: /vi/com.aspose.slides/icharttextformat/
---```
public interface IChartTextFormat
```

Biểu đồ hoạt động với một bộ giới hạn các thuộc tính định dạng văn bản. Các giao diện IChartTextFormat, IChartTextBlockFormat, IChartParagraphFormat, IChartPortionFormat mô tả bộ giới hạn này.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getTextBlockFormat()](#getTextBlockFormat--) | Trả về định dạng cho các phần tử văn bản biểu đồ. |
| [getParagraphFormat()](#getParagraphFormat--) | Trả về định dạng đoạn văn. |
| [getPortionFormat()](#getPortionFormat--) | Trả về định dạng phần. |
| [copyTo(ITextFrame destTextFrame)](#copyTo-com.aspose.slides.ITextFrame-) | Sao chép định dạng văn bản tới khung văn bản được chỉ định. |
| [copyFrom(ITextFrame sourceTextFrame)](#copyFrom-com.aspose.slides.ITextFrame-) | Sao chép định dạng văn bản từ khung văn bản được chỉ định. |
### getTextBlockFormat() {#getTextBlockFormat--}
```
public abstract IChartTextBlockFormat getTextBlockFormat()
```

Trả về định dạng cho các phần tử văn bản biểu đồ. Chỉ đọc [IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat).

**Trả về:**
[IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IChartParagraphFormat getParagraphFormat()
```

Trả về định dạng đoạn văn. Chỉ đọc [IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat).

**Trả về:**
[IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
### getPortionFormat() {#getPortionFormat--}
```
public abstract IChartPortionFormat getPortionFormat()
```

Trả về định dạng phần. Chỉ đọc [IChartPortionFormat](../../com.aspose.slides/ichartportionformat).

**Trả về:**
[IChartPortionFormat](../../com.aspose.slides/ichartportionformat)
### copyTo(ITextFrame destTextFrame) {#copyTo-com.aspose.slides.ITextFrame-}
```
public abstract void copyTo(ITextFrame destTextFrame)
```

Sao chép định dạng văn bản tới khung văn bản được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| destTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Khung văn bản để sao chép định dạng văn bản tới. |

### copyFrom(ITextFrame sourceTextFrame) {#copyFrom-com.aspose.slides.ITextFrame-}
```
public abstract void copyFrom(ITextFrame sourceTextFrame)
```

Sao chép định dạng văn bản từ khung văn bản được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| sourceTextFrame | [ITextFrame](../../com.aspose.slides/itextframe) | Khung văn bản để sao chép định dạng văn bản. |
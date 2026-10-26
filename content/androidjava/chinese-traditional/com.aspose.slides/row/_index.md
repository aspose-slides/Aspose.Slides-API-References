---
title: Row
second_title: Aspose.Slides for Android via Java API 參考
description: 表示表格中的一列。
type: docs
url: /zh-hant/com.aspose.slides/row/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

代表表格中的一列。
## Methods

| Method | Description |
| --- | --- |
| [getHeight()](#getHeight--) | 返回行的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回或設定行的最小可能高度。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 返回或設定行的最小可能高度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 將已定義的段落格式屬性套用至所有行儲存格的段落。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 將已定義的段落格式屬性套用至所有行儲存格的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 將已定義的文字框格式屬性套用至所有行儲存格的文字框。 |
| [getRowFormat()](#getRowFormat--) | 返回包含此行格式屬性的 RowFormat 物件。 |
### getHeight() {#getHeight--}
```
public final double getHeight()
```


返回行的高度。只讀 double。

**Returns:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```


返回或設定行的最小可能高度。可讀寫 double。

**Returns:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```


返回或設定行的最小可能高度。可讀寫 double。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


將已定義的段落格式屬性套用至所有行儲存格的段落。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已設定必要屬性的 IPortionFormat 物件。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


將已定義的段落格式屬性套用至所有行儲存格的段落。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已設定必要屬性的 IParagraphFormat 物件。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


將已定義的文字框格式屬性套用至所有行儲存格的文字框。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已設定必要屬性的 ITextFrameFormat 物件。 |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```


返回此行的 RowFormat 物件，其包含此行的格式屬性。只讀 [IRowFormat](../../com.aspose.slides/irowformat)。

**Returns:**
[IRowFormat](../../com.aspose.slides/irowformat)
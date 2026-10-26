---
title: Row
second_title: Aspose.Slides for Java API 參考手冊
description: 表示表格中的一行。
type: docs
url: /zh-hant/com.aspose.slides/row/
---
**繼承關係:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**所有已實作的介面:**
[com.aspose.slides.IRow](../../com.aspose.slides/irow)
```
public final class Row extends CellCollection implements IRow
```

代表表格中的一行。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight()](#getHeight--) | 返回行的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回或設定行的最小可能高度。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 返回或設定行的最小可能高度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 設定所有行儲存格的部分格式屬性。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 設定所有行儲存格的段落格式屬性。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 設定所有行儲存格的文字框格式屬性。 |
| [getRowFormat()](#getRowFormat--) | 返回包含此行格式屬性的 RowFormat 物件。 |
### getHeight() {#getHeight--}
```
public final double getHeight()
```

返回行的高度。唯讀 double。

**返回值:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

返回或設定行的最小可能高度。可讀寫 double。

**返回值:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public final void setMinimalHeight(double value)
```

返回或設定行的最小可能高度。可讀寫 double。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

設定所有行儲存格的部分格式屬性。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat 物件，已設定必要屬性。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

設定所有行儲存格的段落格式屬性。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat 物件，已設定必要屬性。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```

設定所有行儲存格的文字框格式屬性。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat 物件，已設定必要屬性。 |

### getRowFormat() {#getRowFormat--}
```
public final IRowFormat getRowFormat()
```

返回包含此行格式屬性的 RowFormat 物件。唯讀 [IRowFormat](../../com.aspose.slides/irowformat)。

**返回值:**
[IRowFormat](../../com.aspose.slides/irowformat)
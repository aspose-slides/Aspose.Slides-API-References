---
title: Column
second_title: Aspose.Slides for Android via Java API 參考
description: 表示表格中的欄。
type: docs
url: /zh-hant/com.aspose.slides/column/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**All Implemented Interfaces:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

表示表格中的一個欄。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getWidth()](#getWidth--) | 傳回或設定欄的寬度。 |
| [setWidth(double value)](#setWidth-double-) | 傳回或設定欄的寬度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 設定所有欄位儲存格之部分的已定義部分格式屬性。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 設定所有欄位儲存格之段落的已定義段落格式屬性。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 設定所有欄位儲存格之文字框的已定義文字框格式屬性。 |
| [getColumnFormat()](#getColumnFormat--) | 傳回包含此欄位格式屬性的 ColumnFormat 物件。 |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


傳回或設定欄的寬度。讀寫 double。

**傳回：**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


傳回或設定欄的寬度。讀寫 double。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


設定所有欄位儲存格之部分的已定義部分格式屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 已設定必要屬性的 IPortionFormat 物件。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


設定所有欄位儲存格之段落的已定義段落格式屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 已設定必要屬性的 IParagraphFormat 物件。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFrameFormat(ITextFrameFormat source)
```


設定所有欄位儲存格之文字框的已定義文字框格式屬性。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 已設定必要屬性的 ITextFrameFormat 物件。 |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


傳回包含此欄位格式屬性的 ColumnFormat 物件。唯讀 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**傳回：**
[IColumnFormat](../../com.aspose.slides/icolumnformat)
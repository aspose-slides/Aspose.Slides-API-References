---
title: Column
second_title: Aspose.Slides for Java API 參考
description: 表示表格中的欄。
type: docs
url: /zh-hant/com.aspose.slides/column/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**所有已實作的介面:**  
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)  
```
public final class Column extends CellCollection implements IColumn
```

表示表格中的欄。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getWidth()](#getWidth--) | 返回或設定欄的寬度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或設定欄的寬度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 將已定義的區段格式屬性設定到所有欄儲存格的區段。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 將已定義的段落格式屬性設定到所有欄儲存格的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 將已定義的文字框架格式屬性設定到所有欄儲存格的文字框架。 |
| [getColumnFormat()](#getColumnFormat--) | 返回包含此欄格式屬性的 ColumnFormat 物件。 |
### getWidth() {#getWidth--}
```
public final double getWidth()
```

返回或設定欄的寬度。可讀寫 double.

**返回:**  
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```

返回或設定欄的寬度。可讀寫 double.

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |
### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```

將已定義的區段格式屬性設定到所有欄儲存格的區段。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | 具有必要屬性設定的 IPortionFormat 物件。 |
### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```

將已定義的段落格式屬性設定到所有欄儲存格的段落。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | 具有必要屬性設定的 IParagraphFormat 物件。 |
### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```

將已定義的文字框架格式屬性設定到所有欄儲存格的文字框架。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | 具有必要屬性設定的 ITextFrameFormat 物件。 |
### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```

返回包含此欄格式屬性的 ColumnFormat 物件。唯讀 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**返回:**  
[IColumnFormat](../../com.aspose.slides/icolumnformat)
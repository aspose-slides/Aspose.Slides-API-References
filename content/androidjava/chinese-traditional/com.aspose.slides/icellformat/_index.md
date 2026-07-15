---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /zh-hant/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

表示表格儲存格的格式。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 傳回儲存格填充屬性物件。 |
| [getBorderLeft()](#getBorderLeft--) | 傳回左邊框線屬性物件。 |
| [getBorderTop()](#getBorderTop--) | 傳回上邊框線屬性物件。 |
| [getBorderRight()](#getBorderRight--) | 傳回右邊框線屬性物件。 |
| [getBorderBottom()](#getBorderBottom--) | 傳回下邊框線屬性物件。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 傳回左上至右下對角線屬性物件。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 傳回左下至右上對角線屬性物件。 |
| [getTransparency()](#getTransparency--) | 取得或設定填色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 取得或設定填色的透明度。 |
| [getEffective()](#getEffective--) | 取得有效的表格儲存格格式屬性，套用繼承與表格樣式。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

傳回儲存格填充屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

傳回左邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

傳回上邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

傳回右邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

傳回下邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

傳回左上至右下對角線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

傳回左下至右上對角線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

取得或設定填色的透明度。可讀寫  float 。

**返回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

取得或設定填色的透明度。可讀寫  float 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

取得有效的表格儲存格格式屬性，套用繼承與表格樣式。

**返回：**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - 一個 [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
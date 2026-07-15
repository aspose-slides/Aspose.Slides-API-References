---
title: CellFormat
second_title: Aspose.Slides for Android via Java API 參考
description: 表示表格儲存格的格式。
type: docs
url: /zh-hant/com.aspose.slides/cellformat/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有實作介面：**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

代表表格儲存格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | 傳回儲存格填充屬性物件。 |
| [getBorderLeft()](#getBorderLeft--) | 傳回左側邊框線屬性物件。 |
| [getBorderTop()](#getBorderTop--) | 傳回上方邊框線屬性物件。 |
| [getBorderRight()](#getBorderRight--) | 傳回右側邊框線屬性物件。 |
| [getBorderBottom()](#getBorderBottom--) | 傳回下方邊框線屬性物件。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 傳回左上至右下對角線屬性物件。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 傳回左下至右上對角線屬性物件。 |
| [getEffective()](#getEffective--) | 取得套用繼承與表格樣式後的有效表格儲存格格式屬性。 |
| [getTransparency()](#getTransparency--) | 取得或設定填充顏色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 取得或設定填充顏色的透明度。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**傳回：**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

傳回儲存格填充屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

傳回左側邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

傳回上方邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

傳回右側邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

傳回下方邊框線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

傳回左上至右下對角線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

傳回左下至右上對角線屬性物件。唯讀 [ILineFormat](../../com.aspose.slides/ilineformat)。

**傳回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

取得套用繼承與表格樣式後的有效表格儲存格格式屬性。

--------------------

> ```
> 本範例示範取得不同表格邏輯部份的有效填充格式。
>  請注意，儲存格格式始終具有比列格式更高的優先權，列 - 高於欄，欄 - 高於整個表格。
>  因此最終會使用 CellFormatEffectiveData 屬性來繪製表格。以下程式碼僅為 API 示例。
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回：**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata)。
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

取得或設定填充顏色的透明度。可讀寫  float 。

**傳回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

取得或設定填充顏色的透明度。可讀寫  float 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | float |  |
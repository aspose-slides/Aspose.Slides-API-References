---
title: TableFormat
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示表格的格式。
type: docs
url: /zh-hant/com.aspose.slides/tableformat/
---
**繼承:**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

代表表格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 傳回表格填滿屬性物件。 |
| [getTransparency()](#getTransparency--) | 取得或設定填色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 取得或設定填色的透明度。 |
| [getEffective()](#getEffective--) | 取得套用繼承與表格樣式後的有效表格格式屬性。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

傳回表格填滿屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

取得或設定填色的透明度。讀寫  float 。

**傳回值:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

取得或設定填色的透明度。讀寫  float 。

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

取得套用繼承與表格樣式後的有效表格格式屬性。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**傳回值:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - 一個 [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata)。
### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。唯讀 long。

**傳回值:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

傳回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回值:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
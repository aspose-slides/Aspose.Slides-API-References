---
title: TableFormat
second_title: Aspose.Slides for Java API 參考文件
description: 表示表格的格式。
type: docs
url: /zh-hant/com.aspose.slides/tableformat/
---
**繼承關係：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

表示表格的格式。
## 方法

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


返回表格填充屬性物件。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


取得或設定填色的透明度。可讀寫  float .

**返回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


取得或設定填色的透明度。可讀寫  float .

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


取得套用繼承與表格樣式後的有效表格格式屬性。

--------------------

> ```
> 此範例示範取得不同表格邏輯部分的有效填充格式。
>  請注意，儲存格格式的優先權永遠高於列格式，列高於欄，欄高於整個表格。
>  因此最終會使用 CellFormatEffectiveData 屬性來繪製表格。以下程式碼僅為 API 範例。
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


**返回：**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - 一個 [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


版本。唯讀 long。

**返回：**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


返回父級 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
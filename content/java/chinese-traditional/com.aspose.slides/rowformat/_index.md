---
title: RowFormat
second_title: Aspose.Slides for Java API 參考
description: 表示表格列的格式。
type: docs
url: /zh-hant/com.aspose.slides/rowformat/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**全部已實作介面：**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

表示表格列的格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得具有繼承和表格樣式套用的有效表格列格式屬性。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


取得具有繼承和表格樣式套用的有效表格列格式屬性。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回值：**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - 一個 [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata)。

### getVersion() {#getVersion--}
```
public final long getVersion()
```


版本。唯讀 long。

**返回值：**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


返回父層 IPresentationComponent。唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回值：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
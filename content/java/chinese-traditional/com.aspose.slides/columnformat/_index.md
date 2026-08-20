---
title: ColumnFormat
second_title: Aspose.Slides for Java API 參考
description: 表示表格欄位的格式。
type: docs
url: /zh-hant/com.aspose.slides/columnformat/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有實作的介面：**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

表示表格欄位的格式。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承與表格樣式的有效表格欄位格式屬性。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


取得套用繼承與表格樣式的有效表格欄位格式屬性。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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


**傳回：**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - A [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata)。
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Version. 唯讀 long。

**傳回：**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


傳回 parent IPresentationComponent. 唯讀 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**傳回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
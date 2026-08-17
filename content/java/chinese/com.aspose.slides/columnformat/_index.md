---
title: ColumnFormat
second_title: Aspose.Slides Java API 参考
description: 表示表格列的格式。
type: docs
url: /zh/com.aspose.slides/columnformat/
---
**继承:**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

表示表格列的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getEffective()](#getEffective--) | 获取带有继承和表格样式应用的有效表格列格式属性。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

获取带有继承和表格样式应用的有效表格列格式属性。

--------------------

> ```
> 此示例演示如何获取不同表格逻辑部分的有效填充格式。
>  请注意，单元格格式始终优先于行格式，行格式优先于列格式，列格式优先于整个表格。
>  因此最终始终使用 CellFormatEffectiveData 属性来绘制表格。以下代码仅作为 API 示例。
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


**返回:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - 一个 [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata)。
### getVersion() {#getVersion--}
```
public final long getVersion()
```

版本。只读 long.

**返回:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

返回父级 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)。

**返回:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
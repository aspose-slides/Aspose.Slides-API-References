---
title: TableFormat
second_title: Aspose.Slides Android 版 Java API 参考
description: 表示表格的格式。
type: docs
url: /zh/com.aspose.slides/tableformat/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

表示表格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回表格填充属性对象。 |
| [getTransparency()](#getTransparency--) | 获取或设置填充颜色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 获取或设置填充颜色的透明度。 |
| [getEffective()](#getEffective--) | 获取带有继承和表格样式应用的有效表格格式属性。 |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


返回表格填充属性对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


获取或设置填充颜色的透明度。读/写  float 。

**返回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


获取或设置填充颜色的透明度。读/写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


获取带有继承和表格样式应用的有效表格格式属性。

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

**Returns:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. Read-only long.

**Returns:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()


返回父级 IPresentationComponent。只读 [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**返回：**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
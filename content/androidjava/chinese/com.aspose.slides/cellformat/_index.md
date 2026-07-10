---
title: CellFormat
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示表格单元格的格式。
type: docs
url: /zh/com.aspose.slides/cellformat/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

表示表格单元格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | 返回一个单元格填充属性对象。 |
| [getBorderLeft()](#getBorderLeft--) | 返回一个左边框线属性对象。 |
| [getBorderTop()](#getBorderTop--) | 返回一个顶部边框线属性对象。 |
| [getBorderRight()](#getBorderRight--) | 返回一个右边框线属性对象。 |
| [getBorderBottom()](#getBorderBottom--) | 返回一个底部边框线属性对象。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 返回一个左上到右下对角线属性对象。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 返回一个左下到右上对角线属性对象。 |
| [getEffective()](#getEffective--) | 获取已应用继承和表格样式的有效表格单元格格式属性。 |
| [getTransparency()](#getTransparency--) | 获取或设置填充颜色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 获取或设置填充颜色的透明度。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

返回一个单元格填充属性对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

返回一个左边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

返回一个顶部边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

返回一个右边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

返回一个底部边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

返回一个左上到右下对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

返回一个左下到右上对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

获取已应用继承和表格样式的有效表格单元格格式属性。

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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

**Returns:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Gets or sets the transparency of the fill color. Read/write  float .

**Returns:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
获取或设置填充颜色的透明度。可读写 float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
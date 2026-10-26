---
title: CellFormat
second_title: Aspose.Slides for Java API 参考
description: 表示表格单元格的格式。
type: docs
url: /zh/com.aspose.slides/cellformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口：**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

表示表格单元格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | 返回单元格填充属性对象。 |
| [getBorderLeft()](#getBorderLeft--) | 返回左边框线属性对象。 |
| [getBorderTop()](#getBorderTop--) | 返回上边框线属性对象。 |
| [getBorderRight()](#getBorderRight--) | 返回右边框线属性对象。 |
| [getBorderBottom()](#getBorderBottom--) | 返回下边框线属性对象。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 返回左上到右下对角线属性对象。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 返回左下到右上对角线属性对象。 |
| [getEffective()](#getEffective--) | 获取在继承和表格样式应用后的有效表格单元格格式属性。 |
| [getTransparency()](#getTransparency--) | 获取或设置填充颜色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 获取或设置填充颜色的透明度。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回：**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

返回单元格填充属性对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

返回左边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

返回上边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

返回右边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

返回下边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

返回左上到右下对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

返回左下到右上对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回：**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

获取在继承和表格样式应用后的有效表格单元格格式属性。

--------------------

> ```
> 此示例演示了获取不同表格逻辑部分的有效填充格式。
>  请注意，单元格格式始终优先于行格式，行格式优先于列格式，列格式优先于整个表格。
>  因此，最终绘制表格时始终使用 CellFormatEffectiveData 属性。以下代码仅为 API 示例。
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


**返回：**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - 一个 [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata)。
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

获取或设置填充颜色的透明度。可读写  float 。

**返回：**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

获取或设置填充颜色的透明度。可读写  float 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
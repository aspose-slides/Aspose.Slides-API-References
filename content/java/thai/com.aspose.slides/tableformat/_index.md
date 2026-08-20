---
title: TableFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงรูปแบบของตาราง.
type: docs
url: /th/com.aspose.slides/tableformat/
---
**Inheritance:**  
การสืบทอด: java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject  
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Represents format of a table.  
แสดงรูปแบบของตาราง.
## เมธอด

| เมธอด | คำอธิบาย |
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

ส่งคืนวัตถุคุณสมบัติการเติมของตาราง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**ส่งคืน:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

Gets or sets the transparency of the fill color. อ่าน/เขียน  float .

**ส่งคืน:**  
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Gets or sets the transparency of the fill color. อ่าน/เขียน  float .

**พารามิเตอร์:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Gets effective table formatting properties with inheritance and table styles applied.

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

**ส่งคืน:**  
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - หนึ่ง [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Version. อ่านอย่างเดียว long.

**ส่งคืน:**  
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Returns parent IPresentationComponent. อ่านอย่างเดียว [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**ส่งคืน:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
---
title: TableFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn định dạng của một bảng.
type: docs
url: /vi/com.aspose.slides/tableformat/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được thực hiện:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Biểu diễn định dạng của một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Trả về một đối tượng thuộc tính tô màu bảng. |
| [getTransparency()](#getTransparency--) | Lấy hoặc đặt độ trong suốt của màu tô. |
| [setTransparency(float value)](#setTransparency-float-) | Lấy hoặc đặt độ trong suốt của màu tô. |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng bảng hiệu lực với kế thừa và kiểu bảng đã áp dụng. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Trả về một đối tượng thuộc tính tô màu bảng. Chỉ đọc [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Lấy hoặc đặt độ trong suốt của màu tô. Đọc/ghi  float .

**Trả về:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Lấy hoặc đặt độ trong suốt của màu tô. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Lấy các thuộc tính định dạng bảng hiệu lực với kế thừa và kiểu bảng đã áp dụng.

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

**Trả về:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Trả về IPresentationComponent cha. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
---
title: CellFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho định dạng của một ô bảng.
type: docs
url: /vi/com.aspose.slides/cellformat/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Đại diện cho định dạng của một ô bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Trả về một đối tượng thuộc tính tô màu cell. |
| [getBorderLeft()](#getBorderLeft--) | Trả về một đối tượng thuộc tính đường viền trái. |
| [getBorderTop()](#getBorderTop--) | Trả về một đối tượng thuộc tính đường viền trên. |
| [getBorderRight()](#getBorderRight--) | Trả về một đối tượng thuộc tính đường viền phải. |
| [getBorderBottom()](#getBorderBottom--) | Trả về một đối tượng thuộc tính đường viền dưới. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Trả về một đối tượng thuộc tính đường chéo từ trên-trái xuống dưới-phải. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Trả về một đối tượng thuộc tính đường chéo từ dưới-trái lên trên-phải. |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng ô bảng hiệu lực với kế thừa và kiểu bảng đã áp dụng. |
| [getTransparency()](#getTransparency--) | Lấy hoặc đặt độ trong suốt của màu tô. |
| [setTransparency(float value)](#setTransparency-float-) | Lấy hoặc đặt độ trong suốt của màu tô. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Đọc-chỉ long.

**Trả về:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Trả về một đối tượng thuộc tính tô màu cell. Đọc-chỉ [IFillFormat](../../com.aspose.slides/ifillformat).

**Trả về:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```

Trả về một đối tượng thuộc tính đường viền trái. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```

Trả về một đối tượng thuộc tính đường viền trên. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```

Trả về một đối tượng thuộc tính đường viền phải. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```

Trả về một đối tượng thuộc tính đường viền dưới. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```

Trả về một đối tượng thuộc tính đường chéo từ trên-trái xuống dưới-phải. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```

Trả về một đối tượng thuộc tính đường chéo từ dưới-trái lên trên-phải. Đọc-chỉ [ILineFormat](../../com.aspose.slides/ilineformat).

**Trả về:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```

Lấy các thuộc tính định dạng ô bảng hiệu lực với kế thừa và kiểu bảng đã áp dụng.

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


**Trả về:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
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
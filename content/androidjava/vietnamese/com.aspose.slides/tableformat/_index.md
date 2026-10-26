---
title: TableFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn định dạng của một bảng.
type: docs
url: /vi/com.aspose.slides/tableformat/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Biểu diễn định dạng của một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Trả về một đối tượng thuộc tính tô màu bảng. |
| [getTransparency()](#getTransparency--) | Lấy hoặc đặt độ trong suốt của màu nền. |
| [setTransparency(float value)](#setTransparency-float-) | Lấy hoặc đặt độ trong suốt của màu nền. |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng bảng hiệu quả với kế thừa và kiểu bảng được áp dụng. |
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

Lấy hoặc đặt độ trong suốt của màu nền. Đọc/ghi  float .

**Trả về:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

Lấy hoặc đặt độ trong suốt của màu nền. Đọc/ghi  float .

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

Lấy các thuộc tính định dạng bảng hiệu quả với kế thừa và kiểu bảng được áp dụng.

--------------------

> ```
> Ví dụ này minh họa cách lấy định dạng tô màu hiệu quả cho các phần logic của bảng khác nhau.
>  Lưu ý rằng định dạng ô luôn có mức ưu tiên cao hơn định dạng hàng, hàng - cao hơn cột, cột - cao hơn toàn bộ bảng.
>  Do đó cuối cùng các thuộc tính CellFormatEffectiveData luôn được sử dụng để vẽ bảng. Đoạn mã sau chỉ là một ví dụ về API.
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
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - một [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
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
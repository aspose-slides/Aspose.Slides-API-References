---
title: RowFormat
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho định dạng của một hàng bảng.
type: docs
url: /vi/com.aspose.slides/rowformat/
---
**Kế thừa:**  
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện đã triển khai:**  
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject  
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Đại diện cho định dạng của một hàng bảng.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng hàng bảng có hiệu lực với kế thừa và các kiểu bảng được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```

Lấy các thuộc tính định dạng hàng bảng có hiệu lực với kế thừa và các kiểu bảng được áp dụng.

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


**Trả về:**  
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - một [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).

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

Trả về phần cha IPresentationComponent. Chỉ đọc [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Trả về:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
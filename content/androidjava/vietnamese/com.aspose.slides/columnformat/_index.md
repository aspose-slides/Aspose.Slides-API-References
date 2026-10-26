---
title: ColumnFormat
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho định dạng của một cột bảng.
type: docs
url: /vi/com.aspose.slides/columnformat/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Đại diện cho định dạng của một cột bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng cột bảng hiệu quả với kế thừa và các kiểu bảng đã áp dụng. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

Lấy các thuộc tính định dạng cột bảng hiệu quả với kế thừa và các kiểu bảng đã áp dụng.

--------------------

> ```
> Ví dụ này minh họa cách lấy định dạng tô đầy hiệu quả cho các phần logic khác nhau của bảng.
>  Lưu ý rằng định dạng ô luôn có độ ưu tiên cao hơn định dạng hàng, hàng cao hơn cột, cột cao hơn toàn bảng.
>  Do đó cuối cùng các thuộc tính CellFormatEffectiveData luôn được sử dụng để vẽ bảng. Đoạn mã sau chỉ là một ví dụ về API.
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
```

**Trả về:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - Một [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
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
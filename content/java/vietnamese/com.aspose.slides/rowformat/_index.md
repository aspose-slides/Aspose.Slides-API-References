---
title: RowFormat
second_title: Tham chiếu API Aspose.Slides cho Java
description: Mô tả định dạng của một hàng bảng.
type: docs
url: /vi/com.aspose.slides/rowformat/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Mô tả định dạng của một hàng bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getEffective()](#getEffective--) | Lấy các thuộc tính định dạng hàng bảng thực tế với kế thừa và kiểu bảng được áp dụng. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Lấy các thuộc tính định dạng hàng bảng thực tế với kế thừa và kiểu bảng được áp dụng.

--------------------

> ```
> Ví dụ này minh họa cách lấy định dạng tô đầy thực tế cho các phần logic khác nhau của bảng.
>  Lưu ý rằng định dạng ô luôn có ưu tiên cao hơn định dạng hàng, hàng - cao hơn cột, cột - cao hơn toàn bộ bảng.
>  Do đó cuối cùng các thuộc tính CellFormatEffectiveData luôn được sử dụng để vẽ bảng. Đoạn mã sau chỉ là một ví dụ về API.
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
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - Một [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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
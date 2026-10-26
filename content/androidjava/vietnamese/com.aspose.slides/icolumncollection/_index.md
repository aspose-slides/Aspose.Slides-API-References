---
title: IColumnCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn tập hợp các cột trong một bảng.
type: docs
url: /vi/com.aspose.slides/icolumncollection/
---
**Tất cả các giao diện được thực hiện:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Biểu diễn tập hợp các cột trong một bảng.
## Phương thức

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về cột tại chỉ mục đã chỉ định. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối một bảng. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một cột tại vị trí đã chỉ định khỏi một bảng. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Trả về cột tại chỉ mục đã chỉ định. Chỉ đọc [IColumn](../../com.aspose.slides/icolumn).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối một bảng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép cả tất cả các cột được gắn vào hàng mẫu. |

**Giá trị trả về:**
com.aspose.slides.IColumn[] - Các cột đã thêm.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ mục của cột mới. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép cả tất cả các cột được gắn vào cột mẫu. |

**Giá trị trả về:**
com.aspose.slides.IColumn[] - Các cột đã chèn.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Xóa một cột tại vị trí đã chỉ định khỏi một bảng.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstColumnIndex | int | Chỉ mục của cột cần xóa. |
| withAttachedRows | boolean | True để xóa cả tất cả các cột được gắn. |
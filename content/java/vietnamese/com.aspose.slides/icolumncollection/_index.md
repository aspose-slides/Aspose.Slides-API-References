---
title: IColumnCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị tập hợp các cột trong một bảng.
type: docs
url: /vi/com.aspose.slides/icolumncollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Biểu thị tập hợp các cột trong một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về cột tại chỉ mục được chỉ định. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối bảng. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của cột mẫu được chỉ định và chèn nó vào vị trí được chỉ định trong bảng. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một cột tại vị trí được chỉ định khỏi bảng. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Trả về cột tại chỉ mục được chỉ định. Chỉ đọc [IColumn](../../com.aspose.slides/icolumn).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Giá trị trả về:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để cũng sao chép tất cả các cột được gắn vào hàng mẫu. |

**Giá trị trả về:**
com.aspose.slides.IColumn[] - Các cột đã thêm.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của cột mẫu được chỉ định và chèn nó vào vị trí được chỉ định trong bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của cột mới. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để cũng sao chép tất cả các cột được gắn vào cột mẫu. |

**Giá trị trả về:**
com.aspose.slides.IColumn[] - Các cột đã chèn.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Xóa một cột tại vị trí được chỉ định khỏi bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstColumnIndex | int | Chỉ mục của cột cần xóa. |
| withAttachedRows | boolean | True để cũng xóa tất cả các cột được gắn. |
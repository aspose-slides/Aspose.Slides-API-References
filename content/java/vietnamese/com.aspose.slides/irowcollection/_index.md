---
title: IRowCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn bộ sưu tập các hàng của bảng.
type: docs
url: /vi/com.aspose.slides/irowcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Biểu diễn bộ sưu tập các hàng trong bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục được chỉ định. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối một bảng. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào vị trí được chỉ định trong một bảng. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một hàng tại vị trí được chỉ định khỏi một bảng. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```


Lấy phần tử tại chỉ mục được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```


Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả tất cả các hàng được gắn vào hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã thêm.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```


Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào vị trí được chỉ định trong một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một hàng mới. |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả tất cả các hàng được gắn vào hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã chèn.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```


Xóa một hàng tại vị trí được chỉ định khỏi một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstRowIndex | int | Chỉ mục của một hàng để xóa. |
| withAttachedRows | boolean | True để xóa cả tất cả các hàng được gắn. |
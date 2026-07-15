---
title: IRowCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Đại diện cho bộ sưu tập hàng bảng.
type: docs
url: /vi/com.aspose.slides/irowcollection/
---
**Tất cả các giao diện đã triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Đại diện cho bộ sưu tập hàng bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối bảng. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong bảng. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một hàng tại vị trí đã chỉ định khỏi bảng. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Lấy phần tử tại chỉ mục đã chỉ định.

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

Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả tất cả các hàng đính kèm vào hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã thêm.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hàng mới. |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả tất cả các hàng đính kèm vào hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã chèn.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Xóa một hàng tại vị trí đã chỉ định khỏi bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstRowIndex | int | Chỉ mục của hàng cần xóa. |
| withAttachedRows | boolean | True để xóa cũng tất cả các hàng đính kèm. |
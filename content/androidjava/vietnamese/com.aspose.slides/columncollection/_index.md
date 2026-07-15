---
title: ColumnCollection
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Biểu diễn tập hợp các cột trong một bảng.
type: docs
url: /vi/com.aspose.slides/columncollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IColumnCollection](../../com.aspose.slides/icolumncollection)
```
public final class ColumnCollection extends DomObject<RowCollection> implements IColumnCollection
```

Biểu diễn tập hợp các cột trong một bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số cột trong một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về cột tại chỉ mục đã cho. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối bảng. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã cho trong bảng. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một cột tại vị trí đã chỉ định khỏi bảng. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị chỉ ra việc truy cập vào tập hợp có được đồng bộ hoá (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### size() {#size--}
```
public final int size()
```

Trả về số cột trong một tập hợp. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```

Trả về cột tại chỉ mục đã cho. Chỉ đọc [Column](../../com.aspose.slides/column).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép cả các cột được gắn vào hàng mẫu. |

**Trả về:**
com.aspose.slides.IColumn[] - Các cột được thêm.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã cho trong bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của cột mới. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép cả các cột được gắn vào cột mẫu. |

**Trả về:**
com.aspose.slides.IColumn[] - Các cột được chèn.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Xóa một cột tại vị trí đã chỉ định khỏi bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstColumnIndex | int | Chỉ mục của cột cần xóa. |
| withAttachedRows | boolean | True để xóa cả các cột gắn liền. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Một IGenericEnumerator có thể dùng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - Một java.util.Iterator cho toàn bộ tập hợp.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị chỉ ra việc truy cập vào tập hợp có được đồng bộ hoá (thread-safe) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**
java.lang.Object
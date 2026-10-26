---
title: RowCollection
second_title: Tham chiếu API Aspose.Slides cho Android qua Java
description: Đại diện cho bộ sưu tập hàng của bảng.
type: docs
url: /vi/com.aspose.slides/rowcollection/
---
**Kế thừa:**
java.lang.Object, com.aspose.slides.DomObject

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IRowCollection](../../com.aspose.slides/irowcollection)
```
public final class RowCollection extends DomObject<Table> implements IRowCollection
```

Biểu diễn bộ sưu tập hàng của bảng.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng hàng thực sự chứa trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về hàng tại chỉ mục được chỉ định. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối một bảng. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một hàng tại vị trí được chỉ định khỏi một bảng. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ hoá (an toàn với đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ hoá. |
### size() {#size--}
```
public final int size()
```

Lấy số lượng hàng thực sự chứa trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IRow get_Item(int index)
```

Trả về hàng tại chỉ mục được chỉ định. Chỉ đọc [Row](../../com.aspose.slides/row).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public final IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào cuối một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả các hàng đính kèm với hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã thêm.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public final IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Tạo một bản sao của hàng mẫu được chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của hàng mới. |
| templ | [IRow](../../com.aspose.slides/irow) | Hàng được sử dụng làm mẫu. |
| withAttachedRows | boolean | True để sao chép cả các hàng đính kèm với hàng mẫu. |

**Trả về:**
com.aspose.slides.IRow[] - Các hàng đã chèn.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Xóa một hàng tại vị trí được chỉ định khỏi một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstRowIndex | int | Chỉ mục của hàng cần xóa. |
| withAttachedRows | boolean | True để xóa cả các hàng đính kèm. |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iterator()
```

Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IRow> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IRow> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép tất cả các phần tử từ bộ sưu tập vào mảng đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ hoá (an toàn với đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một gốc đồng bộ hoá. Chỉ đọc Object.

**Trả về:**
java.lang.Object
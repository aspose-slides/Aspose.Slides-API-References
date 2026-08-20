---
title: ColumnCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho tập hợp các cột trong một bảng.
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
| [size()](#size--) | Trả về số lượng cột trong một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về cột tại chỉ mục đã chỉ định. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối một bảng. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Xóa một cột tại vị trí đã chỉ định khỏi một bảng. |
| [iterator()](#iterator--) | Trả về một enumerator để lặp qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp vào mảng đã chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
### size() {#size--}
```
public final int size()
```


Trả về số lượng cột trong một tập hợp. Chỉ đọc int.

**Kết quả:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColumn get_Item(int index)
```


Trả về cột tại chỉ mục đã chỉ định. Chỉ đọc [Column](../../com.aspose.slides/column).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Kết quả:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Tạo một bản sao của hàng mẫu đã chỉ định và chèn nó vào cuối một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép thêm tất cả các cột được gắn vào hàng mẫu. |

**Kết quả:**
com.aspose.slides.IColumn[] - Added columns.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public final IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Tạo một bản sao của cột mẫu đã chỉ định và chèn nó vào vị trí đã chỉ định trong một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của cột mới. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Cột được sử dụng làm mẫu. |
| withAttachedColumns | boolean | True để sao chép thêm tất cả các cột được gắn vào cột mẫu. |

**Kết quả:**
com.aspose.slides.IColumn[] - Inserted columns.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public final void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Xóa một cột tại vị trí đã chỉ định khỏi một bảng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| firstColumnIndex | int | Chỉ mục của cột cần xóa. |
| withAttachedRows | boolean | True để xóa thêm tất cả các cột được gắn. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iterator()
```


Trả về một enumerator để lặp qua tập hợp.

**Kết quả:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColumn> iteratorJava()
```


Trả về một java iterator cho toàn bộ tập hợp.

**Kết quả:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColumn> - An java.util.Iterator for the entire collection.
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


Trả về một giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Kết quả:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một synchronization root. Chỉ đọc Object.

**Kết quả:**
java.lang.Object
---
title: VbaModuleCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn một tập hợp các mô-đun VBA Project.
type: docs
url: /vi/com.aspose.slides/vbamodulecollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Biểu diễn một tập hợp các mô-đun VBA Project.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Lấy số lượng phần tử thực sự chứa trong bộ sưu tập. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Thêm một mô-đun trống mới vào VBA Project. |
| [get_Item(int index)](#get-Item-int-) | Lấy phần tử tại chỉ mục đã chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một gốc đồng bộ. |
### size() {#size--}
```
public final int size()
```


Lấy số lượng phần tử thực sự chứa trong bộ sưu tập. Chỉ-đọc int.

**Trả về:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Xóa lần xuất hiện đầu tiên của một đối tượng cụ thể khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Mô-đun cần xóa khỏi bộ sưu tập. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Thêm một mô-đun trống mới vào VBA Project.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| name | java.lang.String | Tên của mô-đun |

**Trả về:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Mô-đun đã thêm.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Lấy phần tử tại chỉ mục đã chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Trả về một enumerator duyệt qua bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Một java.util.Iterator cho toàn bộ bộ sưu tập.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về một giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn với luồng) hay không. Chỉ-đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một gốc đồng bộ. Chỉ-đọc Object.

**Trả về:**
java.lang.Object
---
title: ColorOperationCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho một tập hợp các phép biến đổi màu.
type: docs
url: /vi/com.aspose.slides/coloroperationcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Đại diện cho một tập hợp các phép biến đổi màu.
## Phương thức

| Method | Description |
| --- | --- |
| [size()](#size--) | Trả về số lượng phép biến đổi trong một tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về hoặc thiết lập phép biến đổi tại chỉ mục được chỉ định. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Trả về hoặc thiết lập phép biến đổi tại chỉ mục được chỉ định. |
| [add(int operation, float parameter)](#add-int-float-) | Thêm một phép biến đổi mới vào cuối tập hợp. |
| [add(int operation)](#add-int-) | Thêm một phép biến đổi mới vào cuối tập hợp. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Chèn phép biến đổi mới vào một tập hợp. |
| [insert(int position, int operation)](#insert-int-int-) | Chèn phép biến đổi mới vào một tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa phép biến đổi màu khỏi một tập hợp. |
| [clear()](#clear--) | Xóa tất cả các phép biến đổi màu. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
| [deepClone()](#deepClone--) | Tạo một bản sao của một tập hợp ColorOperationCollection. |
| [cloneT()](#cloneT--) | Sao chép đối tượng hiện tại |
### size() {#size--}
```
public final int size()
```


Trả về số lượng phép biến đổi trong một tập hợp. Chỉ-đọc int.

**Trả về:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```


Trả về hoặc thiết lập phép biến đổi tại chỉ mục được chỉ định. Đọc/ghi [ColorOperation](../../com.aspose.slides/coloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```


Trả về hoặc thiết lập phép biến đổi tại chỉ mục được chỉ định. Đọc/ghi [ColorOperation](../../com.aspose.slides/coloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```


Thêm một phép biến đổi mới vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại phép biến đổi. |
| parameter | float | Tham số của phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã thêm.
### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```


Thêm một phép biến đổi mới vào cuối tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã thêm.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```


Chèn phép biến đổi mới vào một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà tại đó phép biến đổi sẽ được chèn. |
| operation | int | Loại phép biến đổi. |
| parameter | float | Tham số của phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã chèn.
### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```


Chèn phép biến đổi mới vào một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà tại đó phép biến đổi sẽ được chèn. |
| operation | int | Loại phép biến đổi. |

**Trả về:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Phép biến đổi đã chèn.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa phép biến đổi màu khỏi một tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phép biến đổi màu cần xóa. |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các phép biến đổi màu.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```


Trả về một enumerator để duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Một IGenericEnumerator có thể được sử dụng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```


Trả về một iterator java cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - Một java.util.Iterator cho toàn bộ tập hợp.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Sao chép tất cả các phần tử từ tập hợp sang mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích. |
| index | int | Chỉ mục bắt đầu trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. Chỉ-đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Trả về một synchronization root. Chỉ-đọc Object.

**Trả về:**
java.lang.Object
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Tạo một bản sao của một tập hợp ColorOperationCollection.

**Trả về:**
java.lang.Object - [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) collection mới.
### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```


Sao chép đối tượng hiện tại

**Trả về:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Bản sao
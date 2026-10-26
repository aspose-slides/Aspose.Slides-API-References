---
title: ColorOperationCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho một bộ sưu tập các thao tác biến đổi màu.
type: docs
url: /vi/com.aspose.slides/coloroperationcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)  
```
public final class ColorOperationCollection implements IColorOperationCollection
```

Đại diện cho một bộ sưu tập các thao tác biến đổi màu.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng thao tác trong bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về hoặc thiết lập thao tác tại chỉ mục được chỉ định. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Trả về hoặc thiết lập thao tác tại chỉ mục được chỉ định. |
| [add(int operation, float parameter)](#add-int-float-) | Thêm một thao tác mới vào cuối bộ sưu tập. |
| [add(int operation)](#add-int-) | Thêm một thao tác mới vào cuối bộ sưu tập. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Chèn thao tác mới vào bộ sưu tập. |
| [insert(int position, int operation)](#insert-int-int-) | Chèn thao tác mới vào bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa thao tác màu khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các thao tác màu. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép lặp lại qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép tất cả các phần tử từ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một synchronization root. |
| [deepClone()](#deepClone--) | Tạo một bản sao của bộ sưu tập ColorOperationCollection. |
| [cloneT()](#cloneT--) | Sao chép (nhân bản) đối tượng hiện tại |

### size() {#size--}
```
public final int size()
```

Trả về số lượng thao tác trong bộ sưu tập. Chỉ đọc int.

**Trả về:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

Trả về hoặc thiết lập thao tác tại chỉ mục được chỉ định. Đọc/ghi [ColorOperation](../../com.aspose.slides/coloroperation).

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

Trả về hoặc thiết lập thao tác tại chỉ mục được chỉ định. Đọc/ghi [ColorOperation](../../com.aspose.slides/coloroperation).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

Thêm một thao tác mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại thao tác. |
| parameter | float | Tham số của thao tác. |

**Trả về:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã thêm.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

Thêm một thao tác mới vào cuối bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| operation | int | Loại thao tác. |

**Trả về:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã thêm.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

Chèn thao tác mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà thao tác sẽ được chèn vào. |
| operation | int | Loại thao tác. |
| parameter | float | Tham số của thao tác. |

**Trả về:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã chèn.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

Chèn thao tác mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| position | int | Chỉ mục mà thao tác sẽ được chèn vào. |
| operation | int | Loại thao tác. |

**Trả về:**  
[IColorOperation](../../com.aspose.slides/icoloroperation) - Thao tác đã chèn.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa thao tác màu khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của thao tác màu cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các thao tác màu.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

Trả về một enumerator cho phép lặp lại qua bộ sưu tập.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Trả về:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - An java.util.Iterator for the entire collection.

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

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (an toàn đa luồng) hay không. Chỉ đọc boolean.

**Trả về:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một synchronization root. Chỉ đọc Object.

**Trả về:**  
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Tạo một bản sao của bộ sưu tập ColorOperationCollection.

**Trả về:**  
java.lang.Object - Bộ sưu tập [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection) mới.

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

Sao chép (nhân bản) đối tượng hiện tại

**Trả về:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - Bản sao
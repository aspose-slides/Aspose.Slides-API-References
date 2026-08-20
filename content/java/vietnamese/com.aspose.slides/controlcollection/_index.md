---
title: ControlCollection
second_title: Aspose.Slides cho Tham chiếu API Java
description: Một bộ sưu tập các điều khiển ActiveX.
type: docs
url: /vi/com.aspose.slides/controlcollection/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Một bộ sưu tập các điều khiển ActiveX.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng đối tượng trong bộ sưu tập. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tạo và thêm một điều khiển mới vào bộ sưu tập. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Xóa một điều khiển ActiveX khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi bộ sưu tập. |
| [clear()](#clear--) | Xóa tất cả các điều khiển khỏi bộ sưu tập. |
| [get_Item(int index)](#get-Item-int-) | Trả về một điều khiển tại vị trí được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator cho phép duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một iterator java cho toàn bộ bộ sưu tập. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về gốc đồng bộ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Trả về số lượng đối tượng trong bộ sưu tập. Chỉ đọc int.

**Giá trị trả về:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Tạo và thêm một điều khiển mới vào bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| controlType | int | Loại điều khiển để thêm. |
| x | float | Tọa độ X cho phía trái của khung hình dạng. |
| y | float | Tọa độ Y cho phía trên của khung hình dạng. |
| width | float | Chiều rộng của khung hình dạng. |
| height | float | Chiều cao của khung hình dạng. |

**Giá trị trả về:**
[IControl](../../com.aspose.slides/icontrol) - Điều khiển đã tạo.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Xóa một điều khiển ActiveX khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Điều khiển cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của điều khiển cần xóa. |

### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các điều khiển khỏi bộ sưu tập.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Trả về một điều khiển tại vị trí được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của một điều khiển. |

**Giá trị trả về:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Trả về một enumerator cho phép duyệt qua bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Một IGenericEnumerator có thể được sử dụng để duyệt qua bộ sưu tập.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Trả về một java iterator cho toàn bộ bộ sưu tập.

**Giá trị trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Một java.util.Iterator cho toàn bộ bộ sưu tập.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép toàn bộ bộ sưu tập vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ số trong mảng đích. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập bộ sưu tập có được đồng bộ (thread-safe) hay không. Chỉ đọc boolean.

**Giá trị trả về:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về gốc đồng bộ. Chỉ đọc Object.

**Giá trị trả về:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Giá trị trả về:**
com.aspose.slides.IDOMObject
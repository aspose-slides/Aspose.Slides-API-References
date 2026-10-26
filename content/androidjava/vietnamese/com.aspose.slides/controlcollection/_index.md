---
title: ControlCollection
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Một tập hợp các điều khiển ActiveX.
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

Một tập hợp các điều khiển ActiveX.
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [size()](#size--) | Trả về số lượng đối tượng trong tập hợp. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Tạo và thêm một điều khiển mới vào tập hợp. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Xóa một điều khiển ActiveX khỏi tập hợp. |
| [removeAt(int index)](#removeAt-int-) | Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi tập hợp. |
| [clear()](#clear--) | Xóa tất cả các điều khiển khỏi tập hợp. |
| [get_Item(int index)](#get-Item-int-) | Trả về một điều khiển tại vị trí chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator duyệt qua tập hợp. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ tập hợp. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Sao chép toàn bộ tập hợp vào mảng được chỉ định. |
| [isSynchronized()](#isSynchronized--) | Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. |
| [getSyncRoot()](#getSyncRoot--) | Trả về một đối tượng gốc đồng bộ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Trả về số lượng đối tượng trong tập hợp. chỉ đọc int.

**Trả về:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Tạo và thêm một điều khiển mới vào tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| controlType | int | Kiểu của điều khiển cần thêm. |
| x | float | Tọa độ X cho phía bên trái của khung hình. |
| y | float | Tọa độ Y cho phía trên của khung hình. |
| width | float | Chiều rộng của khung hình. |
| height | float | Chiều cao của khung hình. |

**Trả về:**
[IControl](../../com.aspose.slides/icontrol) - Điều khiển đã tạo.
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Xóa một điều khiển ActiveX khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Một điều khiển cần xóa. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Xóa một điều khiển ActiveX được lưu tại vị trí chỉ định khỏi tập hợp.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của điều khiển cần xóa. |
### clear() {#clear--}
```
public final void clear()
```

Xóa tất cả các điều khiển khỏi tập hợp.
### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Trả về một điều khiển tại vị trí chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của một điều khiển. |

**Trả về:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Trả về một enumerator duyệt qua tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Một IGenericEnumerator có thể được dùng để duyệt qua tập hợp.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Trả về một java iterator cho toàn bộ tập hợp.

**Trả về:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Một java.util.Iterator cho toàn bộ tập hợp.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Sao chép toàn bộ tập hợp vào mảng được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Mảng đích |
| index | int | Chỉ mục trong mảng đích. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Trả về giá trị cho biết việc truy cập vào tập hợp có được đồng bộ (an toàn đa luồng) hay không. chỉ đọc boolean.

**Trả về:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Trả về một đối tượng gốc đồng bộ. chỉ đọc Object.

**Trả về:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject
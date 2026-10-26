---
title: MotionPath
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn đường chuyển động.
type: docs
url: /vi/com.aspose.slides/motionpath/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

Represent motion path.
## Các hàm tạo

| Constructor | Description |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## Các phương thức

| Method | Description |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Thêm lệnh mới vào đường dẫn |
| [getCount()](#getCount--) | Trả về số lượng đường trong bộ sưu tập. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Chèn lệnh mới vào đường dẫn |
| [clear()](#clear--) | Xóa tất cả các lệnh khỏi bộ sưu tập. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Xóa các lệnh được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một lệnh tại chỉ số được chỉ định. |
| [get_Item(int index)](#get-Item-int-) | Trả về một lệnh tại chỉ số được chỉ định. |
| [iterator()](#iterator--) | Trả về một enumerator để duyệt qua bộ sưu tập. |
| [iteratorJava()](#iteratorJava--) | Trả về một java iterator cho toàn bộ bộ sưu tập. |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Thêm lệnh mới vào đường dẫn

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Mảng các điểm |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean tọa độ tương đối |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Trả về số lượng đường trong bộ sưu tập. int chỉ đọc.

**Returns:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


Chèn lệnh mới vào đường dẫn

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số bắt đầu từ 0 nơi mục sẽ được chèn. |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Mảng các điểm |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Boolean tọa độ tương đối |

### clear() {#clear--}
```
public final void clear()
```


Xóa tất cả các lệnh khỏi bộ sưu tập.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Xóa các lệnh được chỉ định khỏi bộ sưu tập.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Đường chuyển động cần xóa. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Xóa một lệnh tại chỉ số được chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số của lệnh cần xóa. |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Trả về một lệnh tại chỉ số được chỉ định.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Chỉ số của phần tử. |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - The [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Trả về một enumerator để duyệt qua bộ sưu tập.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Trả về một java iterator cho toàn bộ bộ sưu tập.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.
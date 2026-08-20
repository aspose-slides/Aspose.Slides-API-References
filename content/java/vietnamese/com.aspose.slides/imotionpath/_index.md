---
title: IMotionPath
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn đường chuyển động.
type: docs
url: /vi/com.aspose.slides/imotionpath/
---
**Tất cả các giao diện được triển khai:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Biểu diễn đường chuyển động.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | Thêm lệnh mới vào đường |
| [getCount()](#getCount--) | Trả về số lượng đường trong bộ sưu tập. |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | Chèn lệnh mới vào đường |
| [clear()](#clear--) | Xóa tất cả các lệnh khỏi bộ sưu tập. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Xóa các lệnh được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một lệnh tại chỉ mục đã cho. |
| [get_Item(int index)](#get-Item-int-) | Trả về một lệnh tại chỉ mục đã cho. |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Thêm lệnh mới vào đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại lệnh cho hành vi hiệu ứng chuyển động animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Mảng điểm java.awt.geom.Point2D.Float[] |
| ptsType | int | Loại điểm trong đường chuyển động animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Cho biết có sử dụng tọa độ tương đối hay không boolean |

**Giá trị trả về:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Lệnh của một đường [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Trả về số lượng đường trong bộ sưu tập. Chỉ đọc int.

**Giá trị trả về:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

Chèn lệnh mới vào đường

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục để chèn lệnh int |
| type | int | Loại lệnh cho hành vi hiệu ứng chuyển động animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | Mảng điểm java.awt.geom.Point2D.Float[] |
| ptsType | int | Loại điểm trong đường chuyển động animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Cho biết có sử dụng tọa độ tương đối hay không boolean |
### clear() {#clear--}
```
public abstract void clear()
```

Xóa tất cả các lệnh khỏi bộ sưu tập.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

Xóa các lệnh được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Đường chuyển động cần xóa [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Xóa một lệnh tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục để xóa lệnh int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

Trả về một lệnh tại chỉ mục đã cho.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của phần tử. |

**Giá trị trả về:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Lệnh tại chỉ mục đã cho [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
---
title: IMotionPath
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Biểu diễn đường chuyển động.
type: docs
url: /vi/com.aspose.slides/imotionpath/
---
**Tất cả các giao diện được thực thi:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Biểu diễn đường chuyển động.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Thêm lệnh mới vào đường dẫn |
| [getCount()](#getCount--) | Trả về số lượng đường trong bộ sưu tập. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Chèn lệnh mới vào đường dẫn |
| [clear()](#clear--) | Xóa tất cả lệnh khỏi bộ sưu tập. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Xóa các lệnh được chỉ định khỏi bộ sưu tập. |
| [removeAt(int index)](#removeAt-int-) | Xóa một lệnh tại chỉ số được chỉ định. |
| [get_Item(int index)](#get-Item-int-) | Trả về một lệnh tại chỉ số được chỉ định. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Thêm lệnh mới vào đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| type | int | Loại lệnh cho hành vi hiệu ứng chuyển động animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Mảng điểm android.graphics.PointF[] |
| ptsType | int | Loại điểm trong đường chuyển động animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Cho biết có sử dụng tọa độ tương đối hay không boolean |

**Trả về:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Trả về số lượng đường trong bộ sưu tập. Chỉ đọc int.

**Trả về:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Chèn lệnh mới vào đường dẫn

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số cho việc chèn lệnh int |
| type | int | Loại lệnh cho hành vi hiệu ứng chuyển động animation [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Mảng điểm android.graphics.PointF[] |
| ptsType | int | Loại điểm trong đường chuyển động animation [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Cho biết có sử dụng tọa độ tương đối hay không boolean |
### clear() {#clear--}
```
public abstract void clear()
```


Xóa tất cả lệnh khỏi bộ sưu tập.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Xóa các lệnh được chỉ định khỏi bộ sưu tập.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Đường chuyển động để xóa [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Xóa một lệnh tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số để xóa lệnh int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Trả về một lệnh tại chỉ số được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ số của phần tử. |

**Trả về:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
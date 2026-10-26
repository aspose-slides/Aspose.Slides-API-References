---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent one command of a path.
type: docs
url: /vi/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Biểu diễn một lệnh của đường dẫn.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPoints()](#getPoints--) | Xác định các điểm của lệnh. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | Xác định các điểm của lệnh. |
| [getCommandType()](#getCommandType--) | Xác định loại lệnh. |
| [setCommandType(int value)](#setCommandType-int-) | Xác định loại lệnh. |
| [isRelative()](#isRelative--) | Xác định tọa độ lệnh là tương đối hay không. |
| [setRelative(boolean value)](#setRelative-boolean-) | Xác định tọa độ lệnh là tương đối hay không. |
| [getPointsType()](#getPointsType--) | Xác định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Xác định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

Xác định các điểm của lệnh. Đọc/ghi android.graphics.PointF[].

**Trả về:**
android.graphics.PointF[]
### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

Xác định các điểm của lệnh. Đọc/ghi android.graphics.PointF[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

Xác định loại lệnh. Đọc/ghi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Trả về:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

Xác định loại lệnh. Đọc/ghi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

Xác định tọa độ lệnh là tương đối hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

Xác định tọa độ lệnh là tương đối hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

Xác định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Trả về:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

Xác định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
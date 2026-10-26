---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
description: Represent one command of a path.
type: docs
url: /vi/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

Biểu diễn một lệnh của một đường dẫn.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getPoints()](#getPoints--) | Chỉ định các điểm của lệnh. |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | Chỉ định các điểm của lệnh. |
| [getCommandType()](#getCommandType--) | Chỉ định loại lệnh. |
| [setCommandType(int value)](#setCommandType-int-) | Chỉ định loại lệnh. |
| [isRelative()](#isRelative--) | Xác định tọa độ lệnh là tương đối hay không. |
| [setRelative(boolean value)](#setRelative-boolean-) | Xác định tọa độ lệnh là tương đối hay không. |
| [getPointsType()](#getPointsType--) | Chỉ định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | Chỉ định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


Chỉ định các điểm của lệnh. Đọc/ghi java.awt.geom.Point2D.Float[].

**Trả về:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```


Chỉ định các điểm của lệnh. Đọc/ghi java.awt.geom.Point2D.Float[].

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


Chỉ định loại lệnh. Đọc/ghi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**Trả về:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


Chỉ định loại lệnh. Đọc/ghi [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

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


Chỉ định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Trả về:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


Chỉ định loại điểm lệnh Đọc/ghi [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
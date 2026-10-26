---
title: IMotionCmdPath
second_title: Aspose.Slides for Java API Reference
description: แสดงคำสั่งหนึ่งของเส้นทาง.
type: docs
url: /th/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

แสดงคำสั่งหนึ่งของเส้นทาง.
## เมธอด

| Method | Description |
| --- | --- |
| [getPoints()](#getPoints--) | ระบุจุดของคำสั่ง. |
| [setPoints(Point2D.Float[] value)](#setPoints-java.awt.geom.Point2D.Float---) | ระบุจุดของคำสั่ง. |
| [getCommandType()](#getCommandType--) | ระบุประเภทคำสั่ง. |
| [setCommandType(int value)](#setCommandType-int-) | ระบุประเภทคำสั่ง. |
| [isRelative()](#isRelative--) | กำหนดพิกัดคำสั่งว่าเป็นสัมพัทธ์หรือไม่. |
| [setRelative(boolean value)](#setRelative-boolean-) | กำหนดพิกัดคำสั่งว่าเป็นสัมพัทธ์หรือไม่. |
| [getPointsType()](#getPointsType--) | ระบุประเภทจุดของคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | ระบุประเภทจุดของคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
### getPoints() {#getPoints--}
```
public abstract Point2D.Float[] getPoints()
```


ระบุจุดของคำสั่ง. อ่าน/เขียน java.awt.geom.Point2D.Float[].

**ผลลัพธ์:**
java.awt.geom.Point2D.Float[]
### setPoints(Point2D.Float[] value) {#setPoints-java.awt.geom.Point2D.Float---}
```
public abstract void setPoints(Point2D.Float[] value)
```


ระบุจุดของคำสั่ง. อ่าน/เขียน java.awt.geom.Point2D.Float[].

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Point2D.Float[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```


ระบุประเภทคำสั่ง. อ่าน/เขียน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**ผลลัพธ์:**
int
### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```


ระบุประเภทคำสั่ง. อ่าน/เขียน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```


กำหนดพิกัดคำสั่งว่าเป็นสัมพัทธ์หรือไม่. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```


กำหนดพิกัดคำสั่งว่าเป็นสัมพัทธ์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```


ระบุประเภทจุดของคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**ผลลัพธ์:**
int
### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```


ระบุประเภทจุดของคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
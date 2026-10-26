---
title: IMotionCmdPath
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงคำสั่งหนึ่งของเส้นทาง.
type: docs
url: /th/com.aspose.slides/imotioncmdpath/
---```
public interface IMotionCmdPath
```

แสดงคำสั่งหนึ่งของเส้นทาง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getPoints()](#getPoints--) | ระบุจุดของคำสั่ง. |
| [setPoints(PointF[] value)](#setPoints-android.graphics.PointF---) | ระบุจุดของคำสั่ง. |
| [getCommandType()](#getCommandType--) | ระบุประเภทของคำสั่ง. |
| [setCommandType(int value)](#setCommandType-int-) | ระบุประเภทของคำสั่ง. |
| [isRelative()](#isRelative--) | กำหนดพิกัดของคำสั่งว่าเป็นสัมพัทธ์หรือไม่. |
| [setRelative(boolean value)](#setRelative-boolean-) | กำหนดพิกัดของคำสั่งว่าเป็นสัมพัทธ์หรือไม่. |
| [getPointsType()](#getPointsType--) | ระบุประเภทของจุดคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |
| [setPointsType(int value)](#setPointsType-int-) | ระบุประเภทของจุดคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype). |

### getPoints() {#getPoints--}
```
public abstract PointF[] getPoints()
```

ระบุจุดของคำสั่ง. อ่าน/เขียน android.graphics.PointF[].

**คืนค่า:**
android.graphics.PointF[]

### setPoints(PointF[] value) {#setPoints-android.graphics.PointF---}
```
public abstract void setPoints(PointF[] value)
```

ระบุจุดของคำสั่ง. อ่าน/เขียน android.graphics.PointF[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | android.graphics.PointF[] |  |

### getCommandType() {#getCommandType--}
```
public abstract int getCommandType()
```

ระบุประเภทของคำสั่ง. อ่าน/เขียน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**คืนค่า:**
int

### setCommandType(int value) {#setCommandType-int-}
```
public abstract void setCommandType(int value)
```

ระบุประเภทของคำสั่ง. อ่าน/เขียน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isRelative() {#isRelative--}
```
public abstract boolean isRelative()
```

กำหนดพิกัดของคำสั่งว่าเป็นสัมพัทธ์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setRelative(boolean value) {#setRelative-boolean-}
```
public abstract void setRelative(boolean value)
```

กำหนดพิกัดของคำสั่งว่าเป็นสัมพัทธ์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getPointsType() {#getPointsType--}
```
public abstract int getPointsType()
```

ระบุประเภทของจุดคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**คืนค่า:**
int

### setPointsType(int value) {#setPointsType-int-}
```
public abstract void setPointsType(int value)
```

ระบุประเภทของจุดคำสั่ง อ่าน/เขียน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
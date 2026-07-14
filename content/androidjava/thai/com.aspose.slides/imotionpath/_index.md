---
title: IMotionPath
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงเส้นทางการเคลื่อนที่.
type: docs
url: /th/com.aspose.slides/imotionpath/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

แสดงเส้นทางการเคลื่อนที่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | เพิ่มคำสั่งใหม่ลงในเส้นทาง |
| [getCount()](#getCount--) | คืนค่าจำนวนเส้นทางในคอลเลกชัน |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | แทรกคำสั่งใหม่ลงในเส้นทาง |
| [clear()](#clear--) | ลบคำสั่งทั้งหมดออกจากคอลเลกชัน |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | ลบคำสั่งที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคำสั่งที่ตำแหน่งที่ระบุ |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคำสั่งที่ตำแหน่งที่ระบุ |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

เพิ่มคำสั่งใหม่ลงในเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของคำสั่งสำหรับพฤติกรรมเอฟเฟกต์การเคลื่อนที่ของอนิเมชัน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | อาเรย์ของจุด android.graphics.PointF[] |
| ptsType | int | ประเภทของจุดในเส้นทางการเคลื่อนที่ของอนิเมชัน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | ระบุว่าจะใช้พิกัดสัมพัทธ์หรือไม่ boolean |

**ผลลัพธ์:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - คำสั่งของเส้นทาง [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

คืนค่าจำนวนเส้นทางในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```

แทรกคำสั่งใหม่ลงในเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับการแทรกคำสั่ง int |
| type | int | ประเภทของคำสั่งสำหรับพฤติกรรมเอฟเฟกต์การเคลื่อนที่ของอนิเมชัน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | อาเรย์ของจุด android.graphics.PointF[] |
| ptsType | int | ประเภทของจุดในเส้นทางการเคลื่อนที่ของอนิเมชัน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | ระบุว่าจะใช้พิกัดสัมพัทธ์หรือไม่ boolean |
### clear() {#clear--}
```
public abstract void clear()
```

ลบคำสั่งทั้งหมดออกจากคอลเลกชัน.
### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

ลบคำสั่งที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | เส้นทางการเคลื่อนที่ที่จะลบ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบคำสั่งที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับการลบคำสั่ง int |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

คืนค่าคำสั่งที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**ผลลัพธ์:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - คำสั่งที่ตำแหน่งที่ระบุ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
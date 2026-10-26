---
title: MotionPath
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงเส้นทางการเคลื่อนที่.
type: docs
url: /th/com.aspose.slides/motionpath/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

แสดงเส้นทางการเคลื่อนที่.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | เพิ่มคำสั่งใหม่ไปยังเส้นทาง |
| [getCount()](#getCount--) | คืนจำนวนเส้นทางในคอลเลกชัน |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | แทรกคำสั่งใหม่ไปยังเส้นทาง |
| [clear()](#clear--) | ลบคำสั่งทั้งหมดออกจากคอลเลกชัน |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | ลบคำสั่งที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคำสั่งที่ตำแหน่งที่ระบุ |
| [get_Item(int index)](#get-Item-int-) | คืนคำสั่งที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


เพิ่มคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | อาร์เรย์ของจุด |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | บูลีนพิกัดสัมพัทธ์ |

**ผลลัพธ์:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


คืนจำนวนเส้นทางในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


แทรกคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ซึ่งจะทำการแทรกรายการ |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | อาร์เรย์ของจุด |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | บูลีนพิกัดสัมพัทธ์ |

### clear() {#clear--}
```
public final void clear()
```


ลบคำสั่งทั้งหมดออกจากคอลเลกชัน

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


ลบคำสั่งที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | เส้นทางการเคลื่อนที่ที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบคำสั่งที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคำสั่งที่ต้องการลบ |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


คืนคำสั่งที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**ผลลัพธ์:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - วัตถุ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


คืน enumerator ที่วนผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


คืน java iterator สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - An java.util.Iterator for the entire collection.
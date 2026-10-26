---
title: MotionPath
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: แสดงเส้นทางการเคลื่อนที่.
type: docs
url: /th/com.aspose.slides/motionpath/
---
**การสืบทอด:**  
java.lang.Object  

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)  
```
public class MotionPath implements IMotionPath
```

แสดงเส้นทางการเคลื่อนที่.  

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | เพิ่มคำสั่งใหม่ไปยังเส้นทาง |
| [getCount()](#getCount--) | ส่งคืนจำนวนเส้นทางในคอลเลกชัน |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | แทรกคำสั่งใหม่ไปยังเส้นทาง |
| [clear()](#clear--) | ลบคำสั่งทั้งหมดจากคอลเลกชัน |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | ลบคำสั่งที่ระบุจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคำสั่งที่ตำแหน่งที่ระบุ |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนคำสั่งที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | ส่งคืนตัววนซ้ำที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน iterator ของ Java สำหรับคอลเลกชันทั้งหมด |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

เพิ่มคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | อาร์เรย์ของจุด |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | ค่าบูลีนพิกัดสัมพันธ์ |

**ค่าที่ส่งคืน:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

ส่งคืนจำนวนเส้นทางในคอลเลกชัน แบบอ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**
int

### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

แทรกคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ที่ควรแทรกรายการ |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | อาร์เรย์ของจุด |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | ค่าบูลีนพิกัดสัมพันธ์ |

### clear() {#clear--}
```
public final void clear()
```

ลบคำสั่งทั้งหมดจากคอลเลกชัน

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

ลบคำสั่งที่ระบุจากคอลเลกชัน

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
| index | int | ดัชนีของคำสั่งที่ควรลบ |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

ส่งคืนคำสั่งที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**ค่าที่ส่งคืน:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) อ็อบเจ็กต์

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

ส่งคืนตัววนซ้ำที่วนซ้ำผ่านคอลเลกชัน

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

ส่งคืน iterator ของ Java สำหรับคอลเลกชันทั้งหมด

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - Iterator ของ java สำหรับคอลเลกชันทั้งหมด
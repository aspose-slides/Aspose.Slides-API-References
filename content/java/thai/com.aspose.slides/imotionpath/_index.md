---
title: IMotionPath
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงเส้นทางการเคลื่อนไหว.
type: docs
url: /th/com.aspose.slides/imotionpath/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

แสดงเส้นทางการเคลื่อนไหว.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | เพิ่มคำสั่งใหม่ไปยังเส้นทาง |
| [getCount()](#getCount--) |  |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | แทรกคำสั่งใหม่ไปยังเส้นทาง |
| [clear()](#clear--) |  |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) |  |
| [removeAt(int index)](#removeAt-int-) |  |
| [get_Item(int index)](#get-Item-int-) |  |

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

เพิ่มคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | int | ประเภทของคำสั่งสำหรับพฤติกรรมการเคลื่อนไหวของแอนิเมชัน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | อาเรย์ของจุด java.awt.geom.Point2D.Float[] |
| ptsType | int | ประเภทของจุดในเส้นทางการเคลื่อนไหวของแอนิเมชัน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | บ่งบอกว่าจะใช้พิกัดสัมพันธ์หรือไม่ boolean |

**คืนค่า:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - คำสั่งของเส้นทาง [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public abstract int getCount()
```

คืนค่าจำนวนเส้นทางในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

แทรกคำสั่งใหม่ไปยังเส้นทาง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับการแทรกคำสั่ง int |
| type | int | ประเภทของคำสั่งสำหรับพฤติกรรมการเคลื่อนไหวของแอนิเมชัน [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | อาเรย์ของจุด java.awt.geom.Point2D.Float[] |
| ptsType | int | ประเภทของจุดในเส้นทางการเคลื่อนไหวของแอนิเมชัน [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | บ่งบอกว่าจะใช้พิกัดสัมพันธ์หรือไม่ boolean |

### clear() {#clear--}
```
public abstract void clear()
```

ลบคำสั่งทั้งหมดจากคอลเลกชัน

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

ลบคำสั่งที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | เส้นทางการเคลื่อนไหวที่จะลบ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบคำสั่งที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีสำหรับการลบคำสั่ง int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

คืนค่าคำสั่งที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**คืนค่า:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - คำสั่งที่ดัชนีที่ระบุ [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
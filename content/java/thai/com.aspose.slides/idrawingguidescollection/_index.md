---
title: IDrawingGuidesCollection
second_title: อ้างอิง API Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของไกด์การวาดที่ปรับได้.
type: docs
url: /th/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

เป็นคอลเลกชันของไกด์การวาดที่ปรับได้.
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคู่มือการวาดโดยดัชนี. |
| [add(byte orientation, float position)](#add-byte-float-) | เพิ่มคู่มือการวาดที่ท้ายคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบคู่มือการวาดที่ดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบทุกองค์ประกอบจากคอลเลกชัน. |
| [getCount()](#getCount--) | รับจำนวนของทุกองค์ประกอบในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```

คืนค่าคู่มือการวาดโดยดัชนี. อ่านอย่างเดียว [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```

เพิ่มคู่มือการวาดที่ท้ายคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| orientation | byte | ทิศทางของคู่มือการวาด. |
| position | float | ตำแหน่งของคู่มือการวาดเป็นจุด. |

**ผลลัพธ์:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบคู่มือการวาดที่ดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคู่มือการวาดที่ต้องการลบ. |

### clear() {#clear--}
```
public abstract void clear()
```

ลบทุกองค์ประกอบจากคอลเลกชัน.

### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนของทุกองค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
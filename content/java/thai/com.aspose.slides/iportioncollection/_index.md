---
title: IPortionCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของส่วน
type: docs
url: /th/com.aspose.slides/iportioncollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

เป็นคอลเลกชันของส่วน
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | รับจำนวนของอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | เพิ่ม Portion ไปยังส่วนท้ายของคอลเลกชัน |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | กำหนดดัชนีของ Portion เฉพาะในคอลเลกชัน |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | แทรก Portion ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบอิลิเมนต์ทั้งหมดออกจากคอลเลกชัน |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่เฉพาะหรือไม่ |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |
| [removeAt(int index)](#removeAt-int-) | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

รับอิลิเมนต์ที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนของอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน. Read-only int.

**ผลลัพธ์:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

เพิ่ม Portion ไปยังส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่จะเพิ่มลงในส่วนท้ายของคอลเลกชัน |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

กำหนดดัชนีของ Portion เฉพาะในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portion ที่ต้องการค้นหาในคอลเลกชัน |
**ผลลัพธ์:**
int - The index of item if found in the collection; otherwise, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

แทรก Portion ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ที่ Portion ควรแทรก |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion ที่ต้องการแทรก |
### clear() {#clear--}
```
public abstract void clear()
```

ลบอิลิเมนต์ทั้งหมดออกจากคอลเลกชัน
### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

กำหนดว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่เฉพาะหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |
**ผลลัพธ์:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); ไม่เช่นนั้น false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

ลบการเกิดครั้งแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | อ็อบเจกต์ที่ต้องการลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |
**ผลลัพธ์:**
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); ไม่เช่นนั้น false. วิธีนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ของอิลิเมนต์ที่ต้องการลบ |

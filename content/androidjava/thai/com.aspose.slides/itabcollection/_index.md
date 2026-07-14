---
title: ITabCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของแท็บ.
type: docs
url: /th/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**  
com.aspose.slides.IGenericCollection  
```
public interface ITabCollection extends IGenericCollection<ITab>
```

แสดงถึงคอลเลกชันของแท็บ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งอินเด็กซ์ที่ระบุ. |
| [add(double position, int align)](#add-double-int-) | เพิ่มแท็บลงในคอลเลกชัน. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | เพิ่มแท็บลงในคอลเลกชัน. |
| [clear()](#clear--) | ลบองค์ประกอบทั้งหมดจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบองค์ประกอบที่ตำแหน่งอินเด็กซ์ที่ระบุจากคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งอินเด็กซ์ที่ระบุ. อ่านอย่างเดียว [ITab](../../com.aspose.slides/itab).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

เพิ่มแท็บลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | double | ตำแหน่งของแท็บ. |
| align | int | การจัดตำแหน่งของแท็บ. |

**ผลลัพธ์:**
[ITab](../../com.aspose.slides/itab) - แท็บที่เพิ่ม.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

เพิ่มแท็บลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | อ็อบเจ็กต์ Tab ที่จะถูกเพิ่มไปยังส่วนท้ายของคอลเลกชัน. |

**ผลลัพธ์:**
int - อินเด็กซ์ที่แท็บถูกเพิ่ม.
### clear() {#clear--}
```
public abstract void clear()
```

ลบองค์ประกอบทั้งหมดจากคอลเลกชัน.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบองค์ประกอบที่ตำแหน่งอินเด็กซ์ที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | อินเด็กซ์เริ่มต้นจากศูนย์ขององค์ประกอบที่จะลบ. |
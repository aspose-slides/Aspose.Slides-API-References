---
title: ITabCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นคอลเลกชันของแท็บ.
type: docs
url: /th/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

แทนคอลเลกชันของแท็บ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [add(double position, int align)](#add-double-int-) | เพิ่ม Tab ไปยังคอลเลกชัน. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | เพิ่ม Tab ไปยังคอลเลกชัน. |
| [clear()](#clear--) | ลบอิลิเมนต์ทั้งหมดจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

รับอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ITab](../../com.aspose.slides/itab).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

เพิ่ม Tab ไปยังคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| position | double | ตำแหน่งของ Tab. |
| align | int | การจัดเรียงของ Tab. |

**คืนค่า:**
[ITab](../../com.aspose.slides/itab) - แท็บที่เพิ่ม.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

เพิ่ม Tab ไปยังคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | อ็อบเจ็กต์ Tab ที่จะเพิ่มที่ท้ายของคอลเลกชัน. |

**คืนค่า:**
int - ดัชนีที่แท็บถูกเพิ่ม.
### clear() {#clear--}
```
public abstract void clear()
```

ลบอิลิเมนต์ทั้งหมดจากคอลเลกชัน.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบอิลิเมนต์ที่ตำแหน่งที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีที่เริ่มจากศูนย์ของอิลิเมนต์ที่จะลบ. |
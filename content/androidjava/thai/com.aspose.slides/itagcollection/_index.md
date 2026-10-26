---
title: ITagCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของแท็กที่เป็นคู่ของสตริงที่ผู้ใช้กำหนด
type: docs
url: /th/com.aspose.slides/itagcollection/
---
**ส่วนต่อประสานทั้งหมดที่ใช้งาน:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

แสดงถึงคอลเลกชันของแท็ก (คู่ของสตริงที่ผู้ใช้กำหนด)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มแท็กใหม่เข้าไปในคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบแท็กที่มีชื่อระบุออกจากคอลเลกชัน |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | ส่งคืนตำแหน่งเชิงศูนย์ของคีย์ที่ระบุในคอลเลกชัน |
| [contains(String name)](#contains-java.lang.String-) | ตรวจสอบว่าคอลเลกชันมีชื่อเฉพาะหรือไม่ |
| [removeAt(int index)](#removeAt-int-) | ลบแท็กที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบแท็กทั้งหมดออกจากคอลเลกชัน |
| [getValueByIndex(int index)](#getValueByIndex-int-) | ส่งคืนค่าของแท็กที่ตำแหน่งที่ระบุ |
| [getNameByIndex(int index)](#getNameByIndex-int-) | ส่งคืนคีย์ของแท็กที่ตำแหน่งที่ระบุ |
| [getNamesOfTags()](#getNamesOfTags--) | ส่งคืนชื่อของแท็ก |
| [get_Item(String name)](#get-Item-java.lang.String-) | ส่งคืนหรือกำหนดค่าคู่คีย์และค่าของแท็ก |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ส่งคืนหรือกำหนดค่าคู่คีย์และค่าของแท็ก |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

เพิ่มแท็กใหม่เข้าไปในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็ก |
| value | java.lang.String | ค่าของแท็ก |

**ผลลัพธ์:**
int - ดัชนีของแท็กที่เพิ่ม
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

ลบแท็กที่มีชื่อระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็กที่ต้องการลบ |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

ส่งคืนตำแหน่งเชิงศูนย์ของคีย์ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อที่ต้องการค้นหาในคอลเลกชัน |

**ผลลัพธ์:**
int - ตำแหน่งเชิงศูนย์ของคีย์ หากพบคีย์ในคอลเลกชัน; มิฉะนั้น -1
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

ตรวจสอบว่าคอลเลกชันมีชื่อเฉพาะหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ที่ต้องการค้นหา |

**ผลลัพธ์:**
boolean - true หากคอลเลกชันมีแท็กที่มีคีย์ระบุ; มิฉะนั้น false
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งเชิงศูนย์ของแท็กที่ต้องการลบ |
### clear() {#clear--}
```
public abstract void clear()
```

ลบแท็กทั้งหมดออกจากคอลเลกชัน
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

ส่งคืนค่าของแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของแท็กที่ต้องการส่งค่ากลับ |

**ผลลัพธ์:**
java.lang.String - ค่าของแท็ก
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

ส่งคืนคีย์ของแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของแท็กที่ต้องการส่งคีย์กลับ |

**ผลลัพธ์:**
java.lang.String - คีย์ของแท็ก
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

ส่งคืนชื่อของแท็ก

**ผลลัพธ์:**
java.lang.String[] - รายชื่อของแท็ก
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

ส่งคืนหรือกำหนดค่าคู่คีย์และค่าของแท็ก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก |

**ผลลัพธ์:**
java.lang.String - ค่าของแท็ก
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

ส่งคืนหรือกำหนดค่าคู่คีย์และค่าของแท็ก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก |
| value | java.lang.String |  |
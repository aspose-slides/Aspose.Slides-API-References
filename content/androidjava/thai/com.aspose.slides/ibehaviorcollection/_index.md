---
title: IBehaviorCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: แสดงคอลเลกชันของเอฟเฟกต์พฤติกรรม
type: docs
url: /th/com.aspose.slides/ibehaviorcollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

แสดงถึงคอลเลกชันของเอฟเฟกต์พฤติกรรม
## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนพฤติกรรมที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | ส่งคืนพฤติกรรมที่ตำแหน่งที่ระบุ |
| [getCount()](#getCount--) | ส่งคืนจำนวนพฤติกรรมในคอลเลกชัน |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | เพิ่มพฤติกรรมใหม่ไปยังคอลเลกชัน |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | กำหนดตำแหน่งของรายการที่ระบุใน List |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | แทรกพฤติกรรมใหม่ในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | ลบพฤติกรรมที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบพฤติกรรมจากคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบพฤติกรรมทั้งหมดออกจากคอลเลกชัน |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

ส่งคืนพฤติกรรมที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่จะส่งคืน |

**คืนค่า:**
[IBehavior](../../com.aspose.slides/ibehavior) - พฤติกรรมแอนิเมชัน
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

ส่งคืนพฤติกรรมที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่จะส่งคืน |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### getCount() {#getCount--}
```
public abstract int getCount()
```

ส่งคืนจำนวนพฤติกรรมในคอลเลกชัน อ่านอย่างเดียว int

**คืนค่า:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

เพิ่มพฤติกรรมใหม่ไปยังคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะเพิ่ม |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

กำหนดตำแหน่งของรายการที่ระบุใน List

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน List |

**คืนค่า:**
int - ตำแหน่งของรายการหากพบในรายการ; หากไม่พบ ให้เป็น -1
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

แทรกพฤติกรรมใหม่ในคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งที่พฤติกรรมใหม่จะถูกแทรก |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะใส่เข้า |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

ลบพฤติกรรมที่ระบุออกจากคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะลบ |

**คืนค่า:**
boolean - true หากพฤติกรรมลบสำเร็จ boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบพฤติกรรมจากคอลเลกชันที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่จะลบ |
### clear() {#clear--}
```
public abstract void clear()
```

ลบพฤติกรรมทั้งหมดออกจากคอลเลกชัน
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

กำหนดว่าค่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**คืนค่า:**
boolean - true หากพบรายการใน [IGenericCollection](../../com.aspose.slides/igenericcollection); หากไม่พบ ให้เป็น false
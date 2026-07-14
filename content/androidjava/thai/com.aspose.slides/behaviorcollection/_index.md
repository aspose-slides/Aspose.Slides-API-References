---
title: BehaviorCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของเอฟเฟ็กต์พฤติกรรม.
type: docs
url: /th/com.aspose.slides/behaviorcollection/
---
**การสืบทอด:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

อธิบายถึงคอลเลกชันของพฤติกรรม

## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนพฤติกรรมในคอลเลกชัน |
| [isReadOnly()](#isReadOnly--) | คืนค่าบ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | เพิ่มพฤติกรรมใหม่ลงในคอลเลกชัน |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | กำหนดตำแหน่งของรายการเฉพาะใน List |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | แทรกพฤติกรรมใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์โดยเริ่มต้นที่ตำแหน่งอาเรย์ที่ระบุ |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | ลบพฤติกรรมที่ระบุออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบพฤติกรรมจากคอลเลกชันที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบพฤติกรรมทั้งหมดจากคอลเลกชัน |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [get_Item(int index)](#get-Item-int-) | คืนค่าพฤติกรรมที่ตำแหน่งที่ระบุ |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | ตั้งค่าพฤติกรรมที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### getCount() {#getCount--}
```
public final int getCount()
```

คืนค่าจำนวนพฤติกรรมในคอลเลกชัน อ่านอย่างเดียว int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

คืนค่าบ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว อ่านอย่างเดียว boolean.

**Returns:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; otherwise, false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```

เพิ่มพฤติกรรมใหม่ลงในคอลเลกชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะเพิ่ม |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```

กำหนดตำแหน่งของรายการเฉพาะใน List

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน List |

**Returns:**
int - ตำแหน่งของรายการหากพบในรายชื่อ; otherwise, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```

แทรกพฤติกรรมใหม่ลงในคอลเลกชันที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งที่พฤติกรรมใหม่จะถูกแทรก |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะแทรก |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์โดยเริ่มต้นที่ตำแหน่งอาเรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | อาเรย์มิติเดียวที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). อาเรย์ต้องใช้การจัดทำดัชนีเริ่มที่ 0 |
| arrayIndex | int | ดัชนีเริ่มที่ 0 ในอาเรย์ที่การคัดลอกเริ่มต้น |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```

ลบพฤติกรรมที่ระบุออกจากคอลเลกชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | พฤติกรรมที่จะลบ |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบพฤติกรรมจากคอลเลกชันที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่จะลบ |
### clear() {#clear--}
```
public final void clear()
```

ลบพฤติกรรมทั้งหมดจากคอลเลกชัน
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```

ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | วัตถุที่จะค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**Returns:**
boolean - true หากพบรายการใน [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
```

คืนค่าพฤติกรรมที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่ต้องการคืนค่า |

**Returns:**
[IBehavior](../../com.aspose.slides/ibehavior) - พฤติกรรมการเคลื่อนไหว
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public final void set_Item(int index, IBehavior value)
```

ตั้งค่าพฤติกรรมที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ตำแหน่งของพฤติกรรมที่ต้องการตั้งค่า |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - IGenericEnumerator ที่ใช้วนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
---
title: VbaReferenceCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นคอลเลกชันของการอ้างอิงโครงการ VBA
type: docs
url: /th/com.aspose.slides/vbareferencecollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IVbaReferenceCollection](../../com.aspose.slides/ivbareferencecollection)
```
public class VbaReferenceCollection implements IVbaReferenceCollection
```

เป็นคอลเลกชันของการอ้างอิงโครงการ VBA
## วิธีการ

| เมธอด | รายละเอียด |
| --- | --- |
| [size()](#size--) | รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. |
| [add(IVbaReference value)](#add-com.aspose.slides.IVbaReference-) | เพิ่มการอ้างอิงใหม่เข้าไปในคอลเลกชันของการอ้างอิง. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) หรือไม่. |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์. |
### size() {#size--}
```
public final int size()
```

รับจำนวนขององค์ประกอบที่อยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### add(IVbaReference value) {#add-com.aspose.slides.IVbaReference-}
```
public final void add(IVbaReference value)
```

เพิ่มการอ้างอิงใหม่เข้าไปในคอลเลกชันของการอ้างอิง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IVbaReference](../../com.aspose.slides/ivbareference) |  |

### get_Item(int index) {#get-Item-int-}
```
public final IVbaReference get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IVbaReference](../../com.aspose.slides/ivbareference)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iterator()
```

คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - A IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaReference> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaReference> - An java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
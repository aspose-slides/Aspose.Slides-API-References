---
title: SequenceCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของลำดับโต้ตอบ.
type: docs
url: /th/com.aspose.slides/sequencecollection/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

เป็นตัวแทนของคอลเลกชันของลำดับโต้ตอบ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | ส่งคืนจำนวนของสมาชิกในคอลเลกชัน อ่านอย่างเดียว int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | เพิ่มลำดับโต้ตอบใหม่. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | ลบลำดับที่ระบุออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลำดับที่ตำแหน่งที่ระบุออก. |
| [clear()](#clear--) | ลบลำดับทั้งหมดออกจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนลำดับที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | ส่งคืนอะแนเมอเรเตอร์ที่วนรอบคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืนอ็อคเตอร์ของ Java สำหรับคอลเลกชันทั้งหมด. |
### getCount() {#getCount--}
```
public final int getCount()
```


ส่งคืนจำนวนของสมาชิกในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


เพิ่มลำดับโต้ตอบใหม่. อ่าน/เขียน [Sequence](../../com.aspose.slides/sequence).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**คืนค่า:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


ลบลำดับที่ระบุออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | ลำดับที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


ลบลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของลำดับที่ต้องการลบ. |

### clear() {#clear--}
```
public final void clear()
```


ลบลำดับทั้งหมดออกจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


ส่งคืนลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบ. |

**คืนค่า:**
[ISequence](../../com.aspose.slides/isequence) - วัตถุ [ISequence](../../com.aspose.slides/isequence)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


ส่งคืนอะแนเมอเรเตอร์ที่วนรอบคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


ส่งคืนอ็อคเตอร์ของ Java สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - An java.util.Iterator for the entire collection.
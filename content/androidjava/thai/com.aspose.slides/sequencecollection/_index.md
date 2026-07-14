---
title: SequenceCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคอลเลกชันของลำดับโต้ตอบ.
type: docs
url: /th/com.aspose.slides/sequencecollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

แสดงคอลเลกชันของลำดับโต้ตอบ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | เพิ่มลำดับโต้ตอบใหม่. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | ลบลำดับที่ระบุจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลำดับที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบลำดับทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าลำดับที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
### getCount() {#getCount--}
```
public final int getCount()
```

คืนค่าจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```

เพิ่มลำดับโต้ตอบใหม่. อ่าน/เขียน [Sequence](../../com.aspose.slides/sequence).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**ผลลัพธ์:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```

ลบลำดับที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | ลำดับที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของลำดับที่ควรลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบลำดับทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```

คืนค่าลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งขององค์ประกอบ. |

**ผลลัพธ์:**
[ISequence](../../com.aspose.slides/isequence) - อ็อบเจ็กต์ [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
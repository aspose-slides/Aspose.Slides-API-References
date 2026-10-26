---
title: ISequenceCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของคอลเลกชันของลำดับโต้ตอบ.
type: docs
url: /th/com.aspose.slides/isequencecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

เป็นตัวแทนของคอลเล็กชันของลำดับโต้ตอบ.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนขององค์ประกอบในคอลเล็กชัน อ่านอย่างเดียว int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | เพิ่มลำดับโต้ตอบใหม่. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | ลบลำดับที่ระบุออกจากคอลเล็กชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลำดับที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบลำดับทั้งหมดออกจากคอลเล็กชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าลำดับที่ตำแหน่งที่ระบุ. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


คืนค่าจำนวนขององค์ประกอบในคอลเล็กชัน อ่านอย่างเดียว int.

**Returns:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


เพิ่มลำดับโต้ตอบใหม่.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์ Shape [IShape](../../com.aspose.slides/ishape) |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - New sequence [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


ลบลำดับที่ระบุออกจากคอลเล็กชัน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | ลำดับที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


ลบลำดับที่ตำแหน่งที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบในคอลเล็กชัน int |

### clear() {#clear--}
```
public abstract void clear()
```


ลบลำดับทั้งหมดออกจากคอลเล็กชัน.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


คืนค่าลำดับที่ตำแหน่งที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**Returns:**
[ISequence](../../com.aspose.slides/isequence) - อ็อบเจ็กต์ [ISequence](../../com.aspose.slides/isequence)
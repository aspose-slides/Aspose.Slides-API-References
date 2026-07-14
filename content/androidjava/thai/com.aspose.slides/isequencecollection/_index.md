---
title: ISequenceCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java เอกสารอ้างอิง API
description: เป็นตัวแทนของคอลเลกชันของลำดับเชิงโต้ตอบ.
type: docs
url: /th/com.aspose.slides/isequencecollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

เป็นตัวแทนของคอลเลกชันของลำดับเชิงโต้ตอบ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | เพิ่มลำดับเชิงโต้ตอบใหม่. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | ลบลำดับที่ระบุจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบลำดับที่ตำแหน่งที่ระบุ. |
| [clear()](#clear--) | ลบลำดับทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนลำดับที่ตำแหน่งที่ระบุ. |
### getCount() {#getCount--}
```
public abstract int getCount()
```

ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int.

**ส่งคืน:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```

เพิ่มลำดับเชิงโต้ตอบใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | อ็อบเจ็กต์ Shape [IShape](../../com.aspose.slides/ishape) |

**ส่งคืน:**
[ISequence](../../com.aspose.slides/isequence) - ลำดับใหม่ [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```

ลบลำดับที่ระบุจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sequence ที่ต้องการลบ. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบในคอลเลกชัน int |

### clear() {#clear--}
```
public abstract void clear()
```

ลบลำดับทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```

ส่งคืนลำดับที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**ส่งคืน:**
[ISequence](../../com.aspose.slides/isequence) - วัตถุ [ISequence](../../com.aspose.slides/isequence).
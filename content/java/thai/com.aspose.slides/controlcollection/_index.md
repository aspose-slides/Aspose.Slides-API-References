---
title: ControlCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คอลเลกชันของคอนโทรล ActiveX.
type: docs
url: /th/com.aspose.slides/controlcollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

คอลเลกชันของคอนโทรล ActiveX.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนของอ็อบเจกต์ในคอลเลกชัน |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | สร้างและเพิ่มคอนโทรลใหม่ลงในคอลเลกชัน |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | ลบคอนโทรล ActiveX ออกจากคอลเลกชัน |
| [removeAt(int index)](#removeAt-int-) | ลบคอนโทรล ActiveX ที่จัดเก็บไว้ที่ตำแหน่งที่กำหนดออกจากคอลเลกชัน |
| [clear()](#clear--) | ลบคอนโทรลทั้งหมดออกจากคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนคอนโทรลที่ตำแหน่งที่กำหนด |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนของอ็อบเจกต์ในคอลเลกชัน อ่านอย่างเดียว int.

**ส่งคืน:**
int
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

สร้างและเพิ่มคอนโทรลใหม่ลงในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| controlType | int | ประเภทของคอนโทรลที่จะเพิ่ม |
| x | float | พิกัด X ของด้านซ้ายของเฟรมรูปร่าง |
| y | float | พิกัด Y ของด้านบนของเฟรมรูปร่าง |
| width | float | ความกว้างของเฟรมรูปร่าง |
| height | float | ความสูงของเฟรมรูปร่าง |

**ส่งคืน:**
[IControl](../../com.aspose.slides/icontrol) - คอนโทรลที่สร้าง
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

ลบคอนโทรล ActiveX ออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | คอนโทรลที่จะลบ |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบคอนโทรล ActiveX ที่จัดเก็บไว้ที่ตำแหน่งที่กำหนดออกจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรลที่จะลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบคอนโทรลทั้งหมดออกจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

ส่งคืนคอนโทรลที่ตำแหน่งที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรล |

**ส่งคืน:**
[IControl](../../com.aspose.slides/icontrol)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

ส่งคืน enumerator ที่ทำการวนซ้ำผ่านคอลเลกชัน.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**ส่งคืน:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject
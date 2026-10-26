---
title: ControlCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คอลเลกชันของคอนโทรล ActiveX.
type: docs
url: /th/com.aspose.slides/controlcollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject  
```
public class ControlCollection implements IControlCollection, IDOMObject
```

คอลเล็กชันของคอนโทรล ActiveX.

## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนของอ็อบเจ็กต์ในคอลเลกชัน. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | สร้างและเพิ่มคอนโทรลใหม่ไปยังคอลเลกชัน. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | ลบคอนโทรล ActiveX ออกจากคอลเลกชัน. |
| [removeAt(int index)](#removeAt-int-) | ลบคอนโทรล ActiveX ที่เก็บไว้ที่ตำแหน่งที่ระบุจากคอลเลกชัน. |
| [clear()](#clear--) | ลบคอนโทรลทั้งหมดจากคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | คืนค่าคอนโทรลที่ตำแหน่งที่ระบุ. |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันได้ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนของอ็อบเจ็กต์ในคอลเลกชัน. อ่านอย่างเดียว int.

**Returns:**  
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

สร้างและเพิ่มคอนโทรลใหม่ไปยังคอลเลกชัน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| controlType | int | ประเภทของคอนโทรลที่จะเพิ่ม. |
| x | float | พิกัด X ของด้านซ้ายของกรอบรูป. |
| y | float | พิกัด Y ของด้านบนของกรอบรูป. |
| width | float | ความกว้างของกรอบรูป. |
| height | float | ความสูงของกรอบรูป. |

**Returns:**  
[IControl](../../com.aspose.slides/icontrol) - คอนโทรลที่สร้าง.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

ลบคอนโทรล ActiveX ออกจากคอลเลกชัน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | คอนโทรลที่จะลบ. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบคอนโทรล ActiveX ที่เก็บไว้ที่ตำแหน่งที่ระบุจากคอลเลกชัน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรลที่จะลบ. |

### clear() {#clear--}
```
public final void clear()
```

ลบคอนโทรลทั้งหมดจากคอลเลกชัน.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

คืนค่าคอนโทรลที่ตำแหน่งที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของคอนโทรล. |

**Returns:**  
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**Returns:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาเรย์ที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันได้ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**Returns:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root. อ่านอย่างเดียว Object.

**Returns:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject
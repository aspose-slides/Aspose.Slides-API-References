---
title: LayoutSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เค้าโครง
type: docs
url: /th/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**  
การสืบทอด:

java.lang.Object

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ใช้งานทั้งหมด:  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เค้าโครง  
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | คืนค่าจำนวนสไลด์เค้าโครงในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนค่าสไลด์เค้าโครงตามดัชนี |
| [getByType(byte type)](#getByType-byte-) | คืนค่าสไลด์เค้าโครงแรกของประเภทที่ระบุ |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | ลบเค้าโครงออกจากคอลเลกชัน |
| [removeUnused()](#removeUnused--) | ลบสไลด์เค้าโครงที่ไม่ได้ใช้ (สไลด์เค้าโครงที่ HasDependingSlides เป็น false) |
| [iterator()](#iterator--) | คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า synchronization root |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

คืนค่าจำนวนสไลด์เค้าโครงในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

คืนค่าสไลด์เค้าโครงตามดัชนี. อ่านอย่างเดียว [LayoutSlide](../../com.aspose.slides/layoutslide).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

คืนค่าสไลด์เค้าโครงแรกของประเภทที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | ประเภทของสไลด์เค้าโครงที่จะค้นหา |

**ผลลัพธ์:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) ที่มีประเภทที่ระบุหรือ null หากไม่พบเค้าโครง
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

ลบเค้าโครงออกจากคอลเลกชัน

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์เค้าโครงที่ต้องการลบออกจากคอลเลกชัน

--------------------

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเค้าโครงก่อน 2) คุณสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

ลบสไลด์เค้าโครงที่ไม่ได้ใช้ (สไลด์เค้าโครงที่ HasDependingSlides เป็น false)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

คืนค่า enumerator ที่ทำการวนผ่านคอลเลกชัน

**ผลลัพธ์:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชันได้
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (thread-safe) อ่านอย่างเดียว boolean.

**ผลลัพธ์:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า synchronization root อ่านอย่างเดียว Object.

**ผลลัพธ์:**  
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**  
com.aspose.slides.IDOMObject
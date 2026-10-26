---
title: LayoutSlideCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เลย์เอาท์
type: docs
url: /th/com.aspose.slides/layoutslidecollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject  
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

เป็นคลาสฐานสำหรับคอลเลกชันของสไลด์เลย์เอาท์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนสไลด์เลย์เอาท์ในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนสไลด์เลย์เอาท์ตามดัชนี |
| [getByType(byte type)](#getByType-byte-) | ส่งคืนสไลด์เลย์เอาท์แรกของประเภทที่ระบุ |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | ลบเลย์เอาท์ออกจากคอลเลกชัน |
| [removeUnused()](#removeUnused--) | ลบสไลด์เลย์เอาท์ที่ไม่ได้ใช้ (สไลด์เลย์เอาท์ที่ HasDependingSlides เป็น false) |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนสไลด์เลย์เอาท์ในคอลเลกชัน. อ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**  
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

ส่งคืนสไลด์เลย์เอาท์ตามดัชนี. อ่านอย่างเดียว [LayoutSlide](../../com.aspose.slides/layoutslide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

ส่งคืนสไลด์เลย์เอาท์แรกของประเภทที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | byte | ประเภทของสไลด์เลย์เอาท์ที่ต้องการค้นหา |

**ค่าที่ส่งคืน:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) ที่มีประเภทที่ระบุหรือ null หากไม่พบเลย์เอาท์

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

ลบเลย์เอาท์ออกจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | สไลด์เลย์เอาท์ที่ต้องการลบออกจากคอลเลกชัน |

--------------------

1) เพื่อหลีกเลี่ยงการโยน PptxEditException ให้ตรวจสอบคุณสมบัติ HasDependingSlides ของเลย์เอาท์ก่อน. 2) คุณยังสามารถใช้เมธอด [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) เพื่อทำให้โค้ดง่ายขึ้น

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

ลบสไลด์เลย์เอาท์ที่ไม่ได้ใช้ (สไลด์เลย์เอาท์ที่ HasDependingSlides เป็น false)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**ค่าที่ส่งคืน:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**ค่าที่ส่งคืน:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่ระบุว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean

**ค่าที่ส่งคืน:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object

**ค่าที่ส่งคืน:**  
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate อ่านอย่างเดียว IDOMObject

**ค่าที่ส่งคืน:**  
com.aspose.slides.IDOMObject
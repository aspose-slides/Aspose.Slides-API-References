---
title: SectionCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงคอลเลกชันของส่วน.
type: docs
url: /th/com.aspose.slides/sectioncollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)  
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

แสดงถึงคอลเลกชันของส่วน  
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลเมนต์ที่ตำแหน่งที่ระบุ |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | เพิ่มส่วนสไลด์ที่เริ่มจากสไลด์เฉพาะ |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | เพิ่มส่วนเปล่าที่ส่วนท้ายของคอลเลกชัน |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | เพิ่มส่วนเปล่าไปยังตำแหน่งที่ระบุของคอลเลกชัน |
| [size()](#size--) | ดึงจำนวนอิลเมนต์ที่มีอยู่จริงในคอลเลกชัน |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | คืนค่าดัชนีของส่วนที่ระบุในคอลเลกชัน |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | ลบส่วนและสไลด์ที่อยู่ในส่วน |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | ลบส่วน |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบส่วนทั้งหมดจากคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่า root สำหรับการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

ดึงอิลเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISection](../../com.aspose.slides/isection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

เพิ่มส่วนสไลด์ที่เริ่มจากสไลด์เฉพาะ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | สไลด์แรกของส่วน |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่มแล้ว.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

เพิ่มส่วนเปล่าที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่มแล้ว.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

เพิ่มส่วนเปล่าไปยังตำแหน่งที่ระบุของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของส่วน |
| index | int | ดัชนีของส่วนใหม่ |

**คืนค่า:**
[ISection](../../com.aspose.slides/isection) - ส่วนที่เพิ่มแล้ว.
### size() {#size--}
```
public final int size()
```

ดึงจำนวนอิลเมนต์ที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

คืนค่าดัชนีของส่วนที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการค้นหา |

**คืนค่า:**
int - ดัชนีของส่วนหรือ -1 หากส่วนไม่อยู่ในคอลเลกชันนี้
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

ลบส่วนและสไลด์ที่อยู่ในส่วน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบออกจากคอลเลกชัน |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

ลบส่วน. สไลด์ที่อยู่ในส่วนจะถูกรวมเข้ากับส่วนก่อนหน้า

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ต้องการลบออกจากคอลเลกชัน |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

ย้ายส่วนและสไลด์ของมันจากคอลเลกชันไปยังตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ส่วนที่ย้าย |
| index | int | ดัชนีเป้าหมาย |
### clear() {#clear--}
```
public final void clear()
```

ลบส่วนทั้งหมดจากคอลเลกชัน
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีในอาร์เรย์เป้าหมาย |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนี้เป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่า root สำหรับการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
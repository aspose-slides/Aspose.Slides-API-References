---
title: SectionSlideCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของสไลด์ในส่วน
type: docs
url: /th/com.aspose.slides/sectionslidecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**Implemented Interfaces ทั้งหมด:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

แสดงถึงคอลเลกชันของสไลด์ในส่วน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. |
| [size()](#size--) | ดึงจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | คืนค่าแสดงว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | คืนรากการซิงโครไนซ์. |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

ดึงจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าแสดงว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator ที่สามารถใช้เพื่อวนซ้ำผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
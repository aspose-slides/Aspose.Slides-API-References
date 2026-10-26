---
title: SectionSlideCollection
second_title: Aspose.Slides สำหรับ Android ผ่านเอกสารอ้างอิง Java API
description: แสดงถึงคอลเลกชันของสไลด์ในส่วนนี้.
type: docs
url: /th/com.aspose.slides/sectionslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

แสดงถึงคอลเลกชันของสไลด์ในส่วนนี้.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [size()](#size--) | ดึงจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกคอลเลกชันทั้งหมดไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนั้นซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


ดึงอิลิเมนต์ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่คืน:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```


ดึงจำนวนอิลิเมนต์ที่มีอยู่จริงในคอลเลกชัน อ่านอย่างเดียว int.

**ค่าที่คืน:**
int
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


คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันนั้นซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**ค่าที่คืน:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนค่ารากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**ค่าที่คืน:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


คืนค่า enumerator ที่วนผ่านคอลเลกชัน

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**ค่าที่คืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - An java.util.Iterator for the entire collection.
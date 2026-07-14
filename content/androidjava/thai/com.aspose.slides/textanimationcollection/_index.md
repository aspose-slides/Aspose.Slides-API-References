---
title: TextAnimationCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของการเคลื่อนไหวข้อความ.
type: docs
url: /th/com.aspose.slides/textanimationcollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

เป็นคอลเลกชันของการเคลื่อนไหวข้อความ
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน. |
| [add()](#add--) | เพิ่มการเคลื่อนไหวข้อความใหม่เข้าสู่คอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบตามดัชนี. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | ส่งคืนทุกองค์ประกอบ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่ทำการวนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืน synchronization root. |
### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```


### size() {#size--}
```
public final int size()
```


ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**
int
### add() {#add--}
```
public final TextAnimation add()
```


เพิ่มการเคลื่อนไหวข้อความใหม่เข้าสู่คอลเลกชัน.

**ค่าที่ส่งคืน:**
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)
### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```


ส่งคืนองค์ประกอบตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```


ส่งคืนทุกองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) เพื่อลบ. |

**ค่าที่ส่งคืน:**
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```


ส่งคืน enumerator ที่ทำการวนผ่านคอลเลกชัน.

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```


ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array to fill. |
| index | int | Starting position in target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**ค่าที่ส่งคืน:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ส่งคืน synchronization root อ่านอย่างเดียว Object.

**ค่าที่ส่งคืน:**
java.lang.Object
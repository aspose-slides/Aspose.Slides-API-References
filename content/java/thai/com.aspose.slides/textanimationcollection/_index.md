---
title: TextAnimationCollection
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: เป็นตัวแทนของคอลเลกชันของการเคลื่อนไหวของข้อความ.
type: docs
url: /th/com.aspose.slides/textanimationcollection/
---
**Inheritance:**  
การสืบทอด:

**All Implemented Interfaces:**  
ทุกอินเทอร์เฟซที่ทำการนำเข้ามา:
[com.aspose.slides.ITextAnimationCollection](../../com.aspose.slides/itextanimationcollection)
```
public class TextAnimationCollection implements ITextAnimationCollection
```

เป็นตัวแทนของคอลเลกชันของการเคลื่อนไหวของข้อความ.
## Constructors

| Constructor | Description |
| --- | --- |
| [TextAnimationCollection()](#TextAnimationCollection--) |  |

## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน. |
| [add()](#add--) | เพิ่มการเคลื่อนไหวของข้อความใหม่ลงในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบตามดัชนี. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | ส่งคืนทุกองค์ประกอบ |
| [iterator()](#iterator--) | ส่งคืนอีเทอเรเตอร์ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืนอิเทอเรเตอร์ของ Java สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าแสดงว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์. |

### TextAnimationCollection() {#TextAnimationCollection--}
```
public TextAnimationCollection()
```

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน. อ่านอย่างเดียว int.

**ส่งคืน:**  
int

### add() {#add--}
```
public final TextAnimation add()
```

เพิ่มการเคลื่อนไหวของข้อความใหม่ลงในคอลเลกชัน.

**ส่งคืน:**  
[TextAnimation](../../com.aspose.slides/textanimation) - Added [TextAnimation](../../com.aspose.slides/textanimation)

### get_Item(int index) {#get-Item-int-}
```
public final ITextAnimation get_Item(int index)
```

ส่งคืนองค์ประกอบตามดัชนี.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ส่งคืน:**  
[ITextAnimation](../../com.aspose.slides/itextanimation)

### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public final ITextAnimation[] get_Item(IShape shape)
```

ส่งคืนทุกองค์ประกอบ

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) เพื่อเอาออก. |

**ส่งคืน:**  
com.aspose.slides.ITextAnimation[] - Array of [ITextAnimation](../../com.aspose.slides/itextanimation)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iterator()
```

ส่งคืนอีเทอเรเตอร์ที่วนผ่านคอลเลกชัน.

**ส่งคืน:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITextAnimation> iteratorJava()
```

ส่งคืนอิเทอเรเตอร์ของ Java สำหรับคอลเลกชันทั้งหมด.

**ส่งคืน:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITextAnimation> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่จะเติม. |
| index | int | ตำแหน่งเริ่มต้นในอาเรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่แสดงว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**ส่งคืน:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**ส่งคืน:**  
java.lang.Object
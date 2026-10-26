---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของชุดสีเพิ่มเติม
type: docs
url: /th/com.aspose.slides/extracolorschemecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

เป็นคอลเลกชันของชุดสีเพิ่มเติม
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนชุดสีโดยระบุดัชนี |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | ส่งคืนตัววนซ้ำที่ทำการ iterates ผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดของคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึง ArrayList ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนอ็อบเจกต์ที่ใช้ซิงโครไนซ์การเข้าถึงคอลเลกชัน |

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนขององค์ประกอบในคอลเลกชัน อ่านอย่างเดียว int.

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

ส่งคืนชุดสีโดยระบุดัชนี อ่านอย่างเดียว [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent\_Immediate อ่านอย่างเดียว IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

ส่งคืนตัววนซ้ำที่ทำการ iterates ผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดของคอลเลกชันไปยังอาเรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์ |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึง ArrayList ถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนอ็อบเจกต์ที่ใช้ซิงโครไนซ์การเข้าถึงคอลเลกชัน อ่านอย่างเดียว Object.

ส่งคืนรากการซิงโครไนซ์ อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object
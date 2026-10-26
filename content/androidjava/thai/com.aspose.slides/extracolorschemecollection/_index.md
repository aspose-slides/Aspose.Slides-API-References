---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงคอลเลกชันของโครงร่างสีเพิ่มเติม.
type: docs
url: /th/com.aspose.slides/extracolorschemecollection/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

แสดงคอลเลกชันของโครงร่างสีเพิ่มเติม
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนขององค์ประกอบในคอลเลกชันเป็น int. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนโครงร่างสีตามดัชนี. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบของคอลเลกชันไปยังอาเรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่ระบุว่าการเข้าถึง ArrayList มีการซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนอ็อบเจ็กต์ที่สามารถใช้ในการซิงโครไนซ์การเข้าถึงคอลเลกชัน. |
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนขององค์ประกอบในคอลเลกชันเป็น int. อ่านอย่างเดียว int.

**ส่งคืน:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

ส่งคืนโครงร่างสีตามดัชนี. อ่านอย่างเดียว [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ส่งคืน:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบของคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาเรย์. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่ระบุว่าการเข้าถึง ArrayList มีการซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนอ็อบเจ็กต์ที่สามารถใช้ในการซิงโครไนซ์การเข้าถึงคอลเลกชัน. อ่านอย่างเดียว Object.

ส่งคืนรากการซิงโครไนซ์. อ่านอย่างเดียว Object.

**ส่งคืน:**
java.lang.Object
---
title: GradientStopCollectionEffectiveData
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเลกชันของอ็อบเจ็กต์ GradientStopData
type: docs
url: /th/com.aspose.slides/gradientstopcollectioneffectivedata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopCollectionEffectiveData](../../com.aspose.slides/igradientstopcollectioneffectivedata)
```
public class GradientStopCollectionEffectiveData implements IEffectiveData, IGradientStopCollectionEffectiveData
```

แสดงถึงคอลเลกชันของวัตถุ GradientStopData objects.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนจำนวนจุดไล่สีในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | คืนจุดไล่สีตามดัชนี |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน iterator ของ Java สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนรากของการซิงโครไนซ์ |
### size() {#size--}
```
public final int size()
```

คืนจำนวนจุดไล่สีในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStopEffectiveData get_Item(int index)
```

คืนจุดไล่สีตามดัชนี

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStopEffectiveData> iteratorJava()
```

คืน iterator ของ Java สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStopEffectiveData> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
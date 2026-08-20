---
title: AdjustValueCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของคอลเลกชันของการปรับค่าของรูปร่าง
type: docs
url: /th/com.aspose.slides/adjustvaluecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดที่ดำเนินการโดยอินเทอร์เฟซ:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

เป็นตัวแทนของคอลเลกชันของการปรับค่า shape
## เมธอด

| Method | Description |
| --- | --- |
| [size()](#size--) | คืนจำนวนการปรับค่า |
| [get_Item(int index)](#get-Item-int-) | คืนการปรับค่าตามดัชนี |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนรากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืนอีเทอเรเตอร์สำหรับคอลเลกชันทั้งหมด |
### size() {#size--}
```
public final int size()
```


คืนจำนวนการปรับค่า อ่านอย่างเดียว int.

**Returns:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```


คืนการปรับค่าตามดัชนี

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ดัชนีของการปรับค่า |

**Returns:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาเรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


คืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```


คืนอีเทอเรเตอร์สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.IEnumerator
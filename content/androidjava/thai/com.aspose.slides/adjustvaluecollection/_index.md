---
title: AdjustValueCollection
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: เป็นคอลเลกชันของการปรับค่ารูปร่าง
type: docs
url: /th/com.aspose.slides/adjustvaluecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

เป็นคอลเลกชันของการปรับค่ารูปร่าง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนการปรับค่า. |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนการปรับค่าตามดัชนี. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ. |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์. |
| [iterator()](#iterator--) | ส่งคืนตัววนซ้ำสำหรับคอลเลกชันทั้งหมด. |
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนการปรับค่า. อ่านอย่างเดียว int.

**ผลลัพธ์:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

ส่งคืนการปรับค่าตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของการปรับค่า. |

**ผลลัพธ์:**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**ผลลัพธ์:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**ผลลัพธ์:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

ส่งคืนตัววนซ้ำสำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**
com.aspose.ms.System.Collections.IEnumerator
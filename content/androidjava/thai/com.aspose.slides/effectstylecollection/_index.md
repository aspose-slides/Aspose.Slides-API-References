---
title: EffectStyleCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: แสดงคอลเลกชันของสไตล์เอฟเฟกต์.
type: docs
url: /th/com.aspose.slides/effectstylecollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**ทั้งหมดของอินเทอร์เฟซที่ใช้งาน:**
[com.aspose.slides.IEffectStyleCollection](../../com.aspose.slides/ieffectstylecollection)
```
public final class EffectStyleCollection extends DomObject<FormatScheme> implements IEffectStyleCollection
```

แสดงคอลเลกชันของสไตล์เอฟเฟกต์
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนอิลิเมนต์ที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [size()](#size--) | ส่งคืนจำนวนอิลิเมนต์ในคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันมีการซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
### get_Item(int index) {#get-Item-int-}
```
public final IEffectStyle get_Item(int index)
```

ส่งคืนอิลิเมนต์ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [EffectStyle](../../com.aspose.slides/effectstyle).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ตำแหน่งของอิลิเมนต์. |

**คืนค่า:**
[IEffectStyle](../../com.aspose.slides/ieffectstyle) - อิลิเมนต์ที่ตำแหน่งที่ระบุ.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iterator()
```

ส่งคืน enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IEffectStyle> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IEffectStyle> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนอิลิเมนต์ในคอลเลกชัน. อ่านอย่างเดียว int, อ่านอย่างเดียว int.

**คืนค่า:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกอิลิเมนต์ทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย. |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันมีการซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object
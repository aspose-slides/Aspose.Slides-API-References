---
title: FontSubstRuleCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นคอลเลกชันของการแทนที่ฟอนต์.
type: docs
url: /th/com.aspose.slides/fontsubstrulecollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

เป็นคอลเลกชันของการแทนที่ฟอนต์
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | เพิ่มกฎการแทนที่ฟอนต์ใหม่ลงในคอลเลกชัน |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | ลบการเกิดของวัตถุเฉพาะครั้งแรกออกจากคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | ดึงองค์ประกอบที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนค่ารากของการซิงโครไนซ์ |

### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

เพิ่มกฎการแทนที่ฟอนต์ใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

ลบการเกิดของวัตถุเฉพาะครั้งแรกออกจากคอลเลกชัน

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | กฎการแทนที่ฟอนต์ที่จะลบออกจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

ดึงองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์เป้าหมาย |
| index | int | ดัชนีเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนค่ารากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object
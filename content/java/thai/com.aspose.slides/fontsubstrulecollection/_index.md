---
title: FontSubstRuleCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นคอลเลกชันของการแทนที่ฟอนต์
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

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | คืนจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | เพิ่มกฎการแทนที่ฟอนต์ใหม่ลงในคอลเลกชัน |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | ลบการเกิดขึ้นแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ |
| [iterator()](#iterator--) | คืนตัววนซ้ำที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบประสาน (ปลอดภัยจากเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนรากของการประสาน |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

คืนจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน อ่านอย่างเดียว int.

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

ลบการเกิดขึ้นแรกของอ็อบเจกต์ที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | กฎการแทนที่ฟอนต์ที่จะลบออกจากคอลเลกชัน |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ

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

คืนตัววนซ้ำที่วนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

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
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the target array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันนั้นเป็นแบบประสาน (ปลอดภัยจากเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากของการประสาน อ่านอย่างเดียว Object.

**คืนค่า:**  
java.lang.Object
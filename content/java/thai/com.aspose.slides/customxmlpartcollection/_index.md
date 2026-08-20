---
title: CustomXmlPartCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงคอลเล็กชันของส่วน XML ที่กำหนดเอง.
type: docs
url: /th/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**  
การสืบทอด

**All Implemented Interfaces:**  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

แสดงถึงคอลเล็กชันของส่วน XML ที่กำหนดเอง
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบที่ตำแหน่งที่ระบุ |
| [size()](#size--) | ส่งคืนจำนวนของส่วน XML ที่กำหนดเองในคอลเล็กชัน |
| [add(String xmlString)](#add-java.lang.String-) | เพิ่มส่วน XML ที่กำหนดเองใหม่ |
| [add(byte[] xmlData)](#add-byte---) | เพิ่มส่วน XML ที่กำหนดเองใหม่ |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | เพิ่มส่วน XML ที่กำหนดเองใหม่ |
| [removeAt(int index)](#removeAt-int-) | ลบส่วน XML ที่กำหนดเองที่ตำแหน่งที่ระบุ |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเล็กชัน |
| [clear()](#clear--) | ลบทุกรายการจากคอลเล็กชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งค่าที่บ่งชี้ว่าการเข้าถึงคอลเล็กชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | ส่งคืนอีเทเรเตอร์ที่วนผ่านคอลเล็กชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืนอีเทเรเตอร์ Java สำหรับคอลเล็กชันทั้งหมด |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

ส่งคืนองค์ประกอบที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | อินเด็กซ์ศูนย์ฐานขององค์ประกอบที่ต้องการรับ |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - องค์ประกอบที่ตำแหน่งที่ระบุ
### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนของส่วน XML ที่กำหนดเองในคอลเล็กชัน อ่านอย่างเดียว int

**Returns:**
int
### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

เพิ่มส่วน XML ที่กำหนดเองใหม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlString | java.lang.String | สตริง XML ของส่วนใหม่ที่ต้องการเพิ่ม |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML ที่กำหนดเองที่สร้างขึ้น
### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

เพิ่มส่วน XML ที่กำหนดเองใหม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xmlData | byte[] | ข้อมูล XML ของส่วนใหม่ที่ต้องการเพิ่ม |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML ที่กำหนดเองที่สร้างขึ้น
### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

เพิ่มส่วน XML ที่กำหนดเองใหม่

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | InputStream ที่มีข้อมูล XML ของส่วนใหม่ที่ต้องการเพิ่ม |

**Returns:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน XML ที่กำหนดเองที่สร้างขึ้น
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบส่วน XML ที่กำหนดเองที่ตำแหน่งที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | อินเด็กซ์ศูนย์ฐานขององค์ประกอบที่ต้องการลบ |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

ลบการปรากฏครั้งแรกของอ็อบเจ็กต์ที่ระบุจากคอลเล็กชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | ส่วน XML ที่กำหนดเองที่ต้องการลบ |

**Returns:**
boolean - true หาก item ถูกลบสำเร็จ; มิฉะนั้น false
### clear() {#clear--}
```
public final void clear()
```

ลบทุกรายการจากคอลเล็กชัน
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกไปยังอาร์เรย์ที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์ที่ต้องการคัดลอกไป |
| index | int | อินเด็กซ์เริ่มต้นการคัดลอก |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งค่าที่บ่งชี้ว่าการเข้าถึงคอลเล็กชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) หรือไม่ อ่านอย่างเดียว boolean

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object

**Returns:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

ส่งคืนอีเทเรเตอร์ที่วนผ่านคอลเลิกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเล็กชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

ส่งคืนอีเทเรเตอร์ Java สำหรับคอลเล็กชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator สำหรับคอลเล็กชันทั้งหมด
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject

**Returns:**
com.aspose.slides.IDOMObject
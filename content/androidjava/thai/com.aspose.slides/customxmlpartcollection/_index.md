---
title: CustomXmlPartCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API
description: แสดงถึงคอลเลกชันของส่วน xml แบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/customxmlpartcollection/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object

**All Implemented Interfaces:**  
ส่วนต่อประสานที่นำไปใช้ทั้งหมด:  
[com.aspose.slides.ICustomXmlPartCollection](../../com.aspose.slides/icustomxmlpartcollection), com.aspose.slides.IDOMObject  
```
public class CustomXmlPartCollection implements ICustomXmlPartCollection, IDOMObject
```

แสดงถึงคอลเลกชันของส่วน xml แบบกำหนดเอง.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืนองค์ประกอบที่ตำแหน่งที่ระบุ |
| [size()](#size--) | ส่งคืนจำนวนส่วน xml แบบกำหนดเองในคอลเลกชัน |
| [add(String xmlString)](#add-java.lang.String-) | เพิ่มส่วน xml แบบกำหนดใหม่ |
| [add(byte[] xmlData)](#add-byte---) | เพิ่มส่วน xml แบบกำหนดใหม่ |
| [add(InputStream inputStream)](#add-java.io.InputStream-) | เพิ่มส่วน xml แบบกำหนดใหม่ |
| [removeAt(int index)](#removeAt-int-) | ลบส่วน xml แบบกำหนดที่ตำแหน่งที่ระบุ |
| [remove(ICustomXmlPart item)](#remove-com.aspose.slides.ICustomXmlPart-) | ลบการปรากฏครั้งแรกของออบเจกต์เฉพาะจากคอลเลกชัน |
| [clear()](#clear--) | ลบทั้งหมดจากคอลเลกชัน |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากฐานการซิงโครไนซ์ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### get_Item(int index) {#get-Item-int-}
```
public final ICustomXmlPart get_Item(int index)
```

ส่งคืนองค์ประกอบที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ขององค์ประกอบที่ต้องการรับ |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - องค์ประกอบที่ตำแหน่งที่ระบุ

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนส่วน xml แบบกำหนดเองในคอลเลกชัน อ่านอย่างเดียว int

**ผลลัพธ์:**
int

### add(String xmlString) {#add-java.lang.String-}
```
public final ICustomXmlPart add(String xmlString)
```

เพิ่มส่วน xml แบบกำหนดใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlString | java.lang.String | สตริง xml ของส่วนใหม่ที่ต้องการเพิ่ม |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml แบบกำหนดที่สร้างขึ้น

### add(byte[] xmlData) {#add-byte---}
```
public final ICustomXmlPart add(byte[] xmlData)
```

เพิ่มส่วน xml แบบกำหนดใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| xmlData | byte[] | ข้อมูล xml ของส่วนใหม่ที่ต้องการเพิ่ม |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml แบบกำหนดที่สร้างขึ้น

### add(InputStream inputStream) {#add-java.io.InputStream-}
```
public final ICustomXmlPart add(InputStream inputStream)
```

เพิ่มส่วน xml แบบกำหนดใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| inputStream | java.io.InputStream | สตรีมข้อมูลที่มี xml ของส่วนใหม่ที่ต้องการเพิ่ม |

**ผลลัพธ์:**
[ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) - ส่วน xml แบบกำหนดที่สร้างขึ้น

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบส่วน xml แบบกำหนดที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ขององค์ประกอบที่ต้องการลบ |

### remove(ICustomXmlPart item) {#remove-com.aspose.slides.ICustomXmlPart-}
```
public final boolean remove(ICustomXmlPart item)
```

ลบการปรากฏครั้งแรกของออบเจกต์เฉพาะจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [ICustomXmlPart](../../com.aspose.slides/icustomxmlpart) | ส่วน xml แบบกำหนดที่ต้องการลบ |

**ผลลัพธ์:**
boolean - true หากลบรายการสำเร็จ; มิฉะนั้น false

### clear() {#clear--}
```
public final void clear()
```

ลบทั้งหมดจากคอลเลกชัน

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกไปยังอาเรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่จะคัดลอกไป |
| index | int | ดัชนีเริ่มต้นสำหรับการคัดลอก |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งบอกว่าการเข้าถึงคอลเลกชันถูกซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean

**ผลลัพธ์:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากฐานการซิงโครไนซ์ อ่านอย่างเดียว Object

**ผลลัพธ์:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iterator()
```

ส่งคืน enumerator ที่วนผ่านคอลเลกชัน

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชันได้

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ICustomXmlPart> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICustomXmlPart> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนออบเจกต์ Parent_Immediate อ่านอย่างเดียว IDOMObject

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
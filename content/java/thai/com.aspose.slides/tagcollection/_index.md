---
title: TagCollection
second_title: Aspose.Slides สำหรับ Java อ้างอิง API
description: เป็นตัวแทนของคอลเลกชันของแท็กที่เป็นคู่สตริงที่ผู้ใช้กำหนด
type: docs
url: /th/com.aspose.slides/tagcollection/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)
```
public final class TagCollection implements ITagCollection
```

Represents the collection of tags (user defined pairs of strings)

--------------------

> ```
> The following example shows how to add a tag to a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ITagCollection tags = pres.getCustomData().getTags();
>      pres.getCustomData().getTags().add("MyTag", "My Tag Value");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [size()](#size--) | ส่งคืนจำนวนแท็กในคอลเลกชัน |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มแท็กใหม่ลงในคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบแท็กที่มีชื่อที่ระบุจากคอลเลกชัน |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | ส่งคืนดัชนีเริ่มต้นศูนย์ของคีย์ที่ระบุในคอลเลกชัน |
| [contains(String name)](#contains-java.lang.String-) | ตรวจสอบว่าคอลเลกชันมีชื่อเฉพาะหรือไม่ |
| [removeAt(int index)](#removeAt-int-) | ลบแท็กที่ตำแหน่งที่ระบุ |
| [clear()](#clear--) | ลบแท็กทั้งหมดจากคอลเลกชัน |
| [getValueByIndex(int index)](#getValueByIndex-int-) | ส่งคืนค่าของแท็กที่ตำแหน่งที่ระบุ |
| [getNameByIndex(int index)](#getNameByIndex-int-) | ส่งคืนคีย์ของแท็กที่ตำแหน่งที่ระบุ |
| [getNamesOfTags()](#getNamesOfTags--) | ส่งคืนชื่อของแท็ก |
| [get_Item(String name)](#get-Item-java.lang.String-) | ส่งคืนหรือกำหนดคู่คีย์และค่าของแท็ก |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ส่งคืนหรือกำหนดคู่คีย์และค่าของแท็ก |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | ส่งคืนรากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด |

### size() {#size--}
```
public final int size()
```

ส่งคืนจำนวนแท็กในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

เพิ่มแท็กใหม่ลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็ก |
| value | java.lang.String | ค่าของแท็ก |

**คืนค่า:**
int - ดัชนีของแท็กที่เพิ่ม

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

ลบแท็กที่มีชื่อที่ระบุจากคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็กที่ต้องการลบ |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

ส่งคืนดัชนีเริ่มต้นศูนย์ของคีย์ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อที่ต้องการค้นหาในคอลเลกชัน |

**คืนค่า:**
int - ดัชนีเริ่มต้นศูนย์ของคีย์ ถ้าพบคีย์ในคอลเลกชัน; มิฉะนั้น -1

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

ตรวจสอบว่าคอลเลกชันมีชื่อเฉพาะหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ที่ต้องการค้นหา |

**คืนค่า:**
boolean - true ถ้าคอลเลกชันมีแท็กที่มีคีย์ตามที่ระบุ; มิฉะนั้น false

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ของแท็กที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบแท็กทั้งหมดจากคอลเลกชัน

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

ส่งคืนค่าของแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่ต้องการส่งคืน |

**คืนค่า:**
java.lang.String - ค่าของแท็ก

### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

ส่งคืนคีย์ของแท็กที่ตำแหน่งที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่ต้องการส่งคืน |

**คืนค่า:**
java.lang.String - คีย์ของแท็ก

### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

ส่งคืนชื่อของแท็ก

**คืนค่า:**
java.lang.String[] - ชื่อของแท็ก

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

ส่งคืนหรือกำหนดคู่คีย์และค่า ของแท็ก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก |

**คืนค่า:**
java.lang.String - ค่าของแท็ก

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

ส่งคืนหรือกำหนดคู่คีย์และค่า ของแท็ก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกทุกองค์ประกอบจากคอลเลกชันไปยังอาร์เรย์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาร์เรย์ที่ต้องการเติม |
| index | int | ตำแหน่งเริ่มต้นในอาร์เรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

ส่งคืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ส่งคืนรากของการซิงโครไนซ์ อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

ส่งคืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - IGenericEnumerator ที่ใช้สำหรับวนซ้ำผ่านคอลเลกชัน

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

ส่งคืน java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด
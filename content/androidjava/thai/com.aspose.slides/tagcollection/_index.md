---
title: TagCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนชุดของแท็ก ซึ่งเป็นคู่ของสตริงที่กำหนดโดยผู้ใช้
type: docs
url: /th/com.aspose.slides/tagcollection/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.ITagCollection](../../com.aspose.slides/itagcollection)  
```
public final class TagCollection implements ITagCollection
```

แทนชุดของแท็ก (คู่ของสตริงที่กำหนดโดยผู้ใช้)

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
| [size()](#size--) | คืนจำนวนแท็กในคอลเลกชัน |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มแท็กใหม่ไปยังคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบแท็กที่มีชื่อกำหนดจากคอลเลกชัน |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | คืนดัชนีเริ่มต้นศูนย์ของคีย์ที่กำหนดในคอลเลกชัน |
| [contains(String name)](#contains-java.lang.String-) | กำหนดว่าคอลเลกชันมีชื่อนั้นหรือไม่ |
| [removeAt(int index)](#removeAt-int-) | ลบแท็กที่ตำแหน่งดัชนีที่กำหนด |
| [clear()](#clear--) | ลบแท็กทั้งหมดจากคอลเลกชัน |
| [getValueByIndex(int index)](#getValueByIndex-int-) | คืนค่าของแท็กที่ตำแหน่งดัชนีที่กำหนด |
| [getNameByIndex(int index)](#getNameByIndex-int-) | คืนคีย์ของแท็กที่ตำแหน่งดัชนีที่กำหนด |
| [getNamesOfTags()](#getNamesOfTags--) | คืนชื่อของแท็ก |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนหรือกำหนดคู่คีย์และค่าของแท็ก |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | คืนหรือกำหนดคู่คีย์และค่าของแท็ก |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | คัดลอกองค์ประกอบทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ |
| [isSynchronized()](#isSynchronized--) | คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด) |
| [getSyncRoot()](#getSyncRoot--) | คืนรากของการซิงโครไนซ์ |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |

### size() {#size--}
```
public final int size()
```

คืนจำนวนแท็กในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final int add(String name, String value)
```

เพิ่มแท็กใหม่ไปยังคอลเลกชัน.

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

ลบแท็กที่มีชื่อกำหนดจากคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็กที่ต้องการลบ |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public final int indexOfName(String name)
```

คืนดัชนีเริ่มต้นศูนย์ของคีย์ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อที่ต้องการค้นหาในคอลเลกชัน |

**คืนค่า:**
int - ดัชนีเริ่มต้นศูนย์ของคีย์ หากพบคีย์ในคอลเลกชัน; ถ้าไม่พบ, -1

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```

กำหนดว่าคอลเลกชันมีชื่อเฉพาะหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ที่ต้องการค้นหา |

**คืนค่า:**
boolean - true หากคอลเลกชันมีแท็กที่มีคีย์ที่ระบุ; มิฉะนั้น false

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบแท็กที่ตำแหน่งดัชนีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มต้นศูนย์ของแท็กที่ต้องการลบ |

### clear() {#clear--}
```
public final void clear()
```

ลบแท็กทั้งหมดจากคอลเลกชัน.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public final String getValueByIndex(int index)
```

คืนค่าของแท็กที่ตำแหน่งดัชนีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่จะคืนค่า |

**คืนค่า:**
java.lang.String - ค่าของแท็ก

### getNameByIndex(int index) {#getNameByIndex-int-}
```
public final String getNameByIndex(int index)
```

คืนคีย์ของแท็กที่ตำแหน่งดัชนีที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่จะคืนค่า |

**คืนค่า:**
java.lang.String - คีย์ของแท็ก

### getNamesOfTags() {#getNamesOfTags--}
```
public final String[] getNamesOfTags()
```

คืนชื่อของแท็ก.

**คืนค่า:**
java.lang.String[] - ชื่อของแท็ก

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

คืนหรือกำหนดคู่คีย์และค่าของแท็ก.

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

คืนหรือกำหนดคู่คีย์และค่าของแท็ก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก |
| value | java.lang.String |  |

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

คัดลอกรายการทั้งหมดจากคอลเลกชันไปยังอาเรย์ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | อาเรย์ที่จะเติม |
| index | int | ตำแหน่งเริ่มต้นในอาเรย์เป้าหมาย |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

คืนค่าที่บ่งชี้ว่าการเข้าถึงคอลเลกชันเป็นแบบซิงโครไนซ์ (ปลอดภัยต่อเธรด). อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

คืนรากของการซิงโครไนซ์. อ่านอย่างเดียว Object.

**คืนค่า:**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
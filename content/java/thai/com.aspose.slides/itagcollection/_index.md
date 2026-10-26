---
title: ITagCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงคอลเลกชันของแท็กที่เป็นคู่สตริงที่ผู้ใช้กำหนด
type: docs
url: /th/com.aspose.slides/itagcollection/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Represents the collection of tags (user defined pairs of strings)
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มแท็กใหม่ไปยังคอลเล็กชัน. |
| [remove(String name)](#remove-java.lang.String-) | ลบแท็กที่มีชื่อกำหนดจากคอลเล็กชัน. |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | คืนค่าดัชนีเริ่มต้นจากศูนย์ของคีย์ที่ระบุในคอลเล็กชัน. |
| [contains(String name)](#contains-java.lang.String-) | กำหนดว่าคอลเล็กชันมีชื่อเฉพาะหรือไม่. |
| [removeAt(int index)](#removeAt-int-) | ลบแท็กที่ตำแหน่งดัชนีที่ระบุ. |
| [clear()](#clear--) | ลบแท็กทั้งหมดจากคอลเล็กชัน. |
| [getValueByIndex(int index)](#getValueByIndex-int-) | คืนค่าของแท็กที่ตำแหน่งดัชนีที่ระบุ. |
| [getNameByIndex(int index)](#getNameByIndex-int-) | คืนคีย์ของแท็กที่ตำแหน่งดัชนีที่ระบุ. |
| [getNamesOfTags()](#getNamesOfTags--) | คืนชื่อของแท็ก. |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่า หรือ ตั้งค่าคู่คีย์และค่า ของแท็ก. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | คืนค่า หรือ ตั้งค่าคู่คีย์และค่า ของแท็ก. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```


Adds a new tag to collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็ก. |
| value | java.lang.String | ค่าของแท็ก. |

**คืนค่า:**
int - ดัชนีของแท็กที่เพิ่ม.
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Removes the tag with a specified name from the collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของแท็กที่จะลบ. |

### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```


Returns the zero-based index of the specified key in the collection.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อที่จะค้นหาในคอลเล็กชัน. |

**คืนค่า:**
int - ดัชนีเริ่มจากศูนย์ของคีย์ หากพบคีย์ในคอลเล็กชัน; ถ้าไม่พบ จะเป็น -1.
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```


Determines whether the collection contains a specific name.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ที่จะค้นหา. |

**คืนค่า:**
boolean - true หากคอลเล็กชันมีแท็กที่มีคีย์ที่ระบุ; ถ้าไม่ใช่ จะเป็น false.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the tag at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีเริ่มจากศูนย์ของแท็กที่จะลบ. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all tags from the collection.

### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```


Returns value of a tag at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่ต้องการคืนค่า. |

**คืนค่า:**
java.lang.String - ค่าของแท็ก.
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```


Returns key of a tag at the specified index.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแท็กที่ต้องการคืนค่า. |

**คืนค่า:**
java.lang.String - คีย์ของแท็ก.
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```


Returns names of tags.

**คืนค่า:**
java.lang.String[] - ชื่อของแท็ก.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


Returns or sets a key and a value pair of a tag.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก. |

**คืนค่า:**
java.lang.String - ค่าของแท็ก.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


Returns or sets a key and a value pair of a tag.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | คีย์ของแท็ก. |
| value | java.lang.String |  |
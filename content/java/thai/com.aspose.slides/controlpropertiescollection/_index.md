---
title: ControlPropertiesCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: คอลเลกชันของคุณสมบัติ AcitveX.
type: docs
url: /th/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

คอลเลกชันของคุณสมบัติ AcitveX

## Methods

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มคุณสมบัติเข้าไปในคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบคุณสมบัติที่มีชื่อที่ระบุ |
| [get_Item(String name)](#get-Item-java.lang.String-) | คืนค่า หรือ ตั้งค่าคุณสมบัติ |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | คืนค่า หรือ ตั้งค่าคุณสมบัติ |
| [getNamesOfProperties()](#getNamesOfProperties--) | คืนคอลเลกชันของชื่อคุณสมบัติ |
| [clear()](#clear--) | ลบคุณสมบัติตทั้งหมด |
| [getCount()](#getCount--) | คืนจำนวนคุณสมบัติในคอลเลกชัน |
| [iterator()](#iterator--) | คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

เพิ่มคุณสมบัติเข้าไปในคอลเลกชัน

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String | ค่า ของคุณสมบัติ |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

ลบคุณสมบัติที่มีชื่อที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติเพื่อลบ |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

คืนค่า หรือ ตั้งค่าคุณสมบัติ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |

**Returns:**
java.lang.String - Property.

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

คืนค่า หรือ ตั้งค่าคุณสมบัติ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

คืนคอลเลกชันของชื่อคุณสมบัติ อ่านอย่างเดียว [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

ลบคุณสมบัติตทั้งหมด

### getCount() {#getCount--}
```
public final int getCount()
```

คืนจำนวนคุณสมบัติในคอลเลกชัน int แบบอ่านอย่างเดียว

**Returns:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

คืน enumerator ที่วนซ้ำผ่านคอลเลกชัน

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
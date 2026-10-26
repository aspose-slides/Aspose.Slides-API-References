---
title: ControlPropertiesCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
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
## เมธอด

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มคุณสมบัติลงในคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบคุณสมบัติที่มีชื่อที่ระบุ |
| [get_Item(String name)](#get-Item-java.lang.String-) | รับหรือกำหนดคุณสมบัติ |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | รับหรือกำหนดคุณสมบัติ |
| [getNamesOfProperties()](#getNamesOfProperties--) | รับคอลเลกชันของชื่อคุณสมบัติ |
| [clear()](#clear--) | ลบคุณสมบัติทั้งหมด |
| [getCount()](#getCount--) | รับจำนวนของคุณสมบัติในคอลเลกชัน |
| [iterator()](#iterator--) | รับตัววนซ้ำที่ทำการวนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | รับ java iterator สำหรับคอลเลกชันทั้งหมด |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

เพิ่มคุณสมบัติลงในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String | ค่าของคุณสมบัติ |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

ลบคุณสมบัติที่มีชื่อที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติที่จะลบ |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

รับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |

**คืนค่า:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

รับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

รับคอลเลกชันของชื่อคุณสมบัติ อ่านอย่างเดียว [IGenericCollection](../../com.aspose.slides/igenericcollection).

**คืนค่า:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```

ลบคุณสมบัติทั้งหมด

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนของคุณสมบัติในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

รับตัววนซ้ำที่ทำการวนผ่านคอลเลกชัน

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

รับ java iterator สำหรับคอลเลกชันทั้งหมด

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
---
title: IControlPropertiesCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คอลเลกชันของควบคุม ActiveX
type: docs
url: /th/com.aspose.slides/icontrolpropertiescollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

คอลเลกชันของควบคุม ActiveX.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCount()](#getCount--) | คืนค่าจำนวนของคุณสมบัติในคอลเลกชัน |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มคุณสมบัติเข้ากอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบคุณสมบัติที่มีชื่อที่ระบุ |
| [get_Item(String name)](#get-Item-java.lang.String-) | รับหรือกำหนดคุณสมบัติ |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | รับหรือกำหนดคุณสมบัติ |
| [getNamesOfProperties()](#getNamesOfProperties--) | คืนค่าจำนวนของคุณสมบัติในคอลเลกชัน |
| [clear()](#clear--) | ลบคุณสมบัติทั้งหมด |
### getCount() {#getCount--}
```
public abstract int getCount()
```


คืนค่าจำนวนของคุณสมบัติในคอลเลกชัน อ่านอย่างเดียว int.

**คืนค่า:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


เพิ่มคุณสมบัติเข้ากอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String | ค่าของคุณสมบัติ |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


ลบคุณสมบัติที่มีชื่อที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติที่จะลบ |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```


รับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |

**คืนค่า:**
java.lang.String - คุณสมบัติ.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```


รับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


คืนค่าจำนวนของคุณสมบัติในคอลเลกชัน อ่านอย่างเดียว [IGenericCollection](../../com.aspose.slides/igenericcollection).

**คืนค่า:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


ลบคุณสมัติทั้งหมด.
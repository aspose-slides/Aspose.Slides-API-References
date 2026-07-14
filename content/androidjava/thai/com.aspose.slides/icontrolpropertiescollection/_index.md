---
title: IControlPropertiesCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: คอลเลกชันของควบคุม ActiveX.
type: docs
url: /th/com.aspose.slides/icontrolpropertiescollection/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

คอลเลกชันของควบคุม ActiveX.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getCount()](#getCount--) | ส่งกลับจำนวนของคุณสมบัติในคอลเลกชัน |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | เพิ่มคุณสมบัติในคอลเลกชัน |
| [remove(String name)](#remove-java.lang.String-) | ลบคุณสมบัติที่มีชื่อระบุ |
| [get_Item(String name)](#get-Item-java.lang.String-) | ส่งกลับหรือกำหนดคุณสมบัติ |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | ส่งกลับหรือกำหนดคุณสมบัติ |
| [getNamesOfProperties()](#getNamesOfProperties--) | ส่งกลับจำนวนของคุณสมบัติในคอลเลกชัน |
| [clear()](#clear--) | ลบคุณสมบัติทั้งหมด |
### getCount() {#getCount--}
```
public abstract int getCount()
```

ส่งกลับจำนวนของคุณสมบัติในคอลเลกชัน แบบอ่านอย่างเดียว int

**ผลลัพธ์:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

เพิ่มคุณสมบัติในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String | ค่าของคุณสมบัติ |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

ลบคุณสมบัติที่มีชื่อระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติที่จะลบ |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

ส่งกลับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |

**ผลลัพธ์:**
java.lang.String - คุณสมบัติ
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

ส่งกลับหรือกำหนดคุณสมบัติ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| name | java.lang.String | ชื่อของคุณสมบัติ |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

ส่งกลับจำนวนของคุณสมบัติในคอลเลกชัน แบบอ่านอย่างเดียว [IGenericCollection](../../com.aspose.slides/igenericcollection)

**ผลลัพธ์:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

ลบคุณสมัติทั้งหมด
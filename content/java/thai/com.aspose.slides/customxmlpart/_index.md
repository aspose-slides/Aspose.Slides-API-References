---
title: CustomXmlPart
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: เป็นตัวแทนของส่วน XML แบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/customxmlpart/
---
**สืบทอด:**  
java.lang.Object

**อินเตอร์เฟสที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)
```
public class CustomXmlPart implements ICustomXmlPart
```

แทนส่วน XML แบบกำหนดเอง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXmlData()](#getXmlData--) | คืนค่าหรือกำหนดข้อมูล XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | คืนค่าหรือกำหนดข้อมูล XML. |
| [getXmlAsString()](#getXmlAsString--) | คืนค่าหรือกำหนดข้อมูล XML เป็นสตริง UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | คืนค่าหรือกำหนดข้อมูล XML เป็นสตริง UTF-8. |
| [getItemId()](#getItemId--) | ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML แบบกำหนดเองเดียวอย่างไม่ซ้ำกันภายในเอกสาร Office Open XML. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML แบบกำหนดเองเดียวอย่างไม่ซ้ำกันภายในเอกสาร Office Open XML. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | คืนคอลเลกชันของสกีม XML ที่เชื่อมโยงกับส่วน XML แบบกำหนดเอง. |
| [remove()](#remove--) | ลบส่วน XML แบบกำหนดเองออกจากงานนำเสนอ. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```


คืนค่าหรือกำหนดข้อมูล XML. อ่าน/เขียน byte[].

**คืนค่า:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```


คืนค่า或กำหนดข้อมูล XML. อ่าน/เขียน byte[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |

### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```


คืนค่า或กำหนดข้อมูล XML เป็นสตริง UTF-8. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```


คืนค่า或กำหนดข้อมูล XML เป็นสตริง UTF-8. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getItemId() {#getItemId--}
```
public final UUID getItemId()
```


ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML แบบกำหนดเองเดียวอย่างไม่ซ้ำกันภายในเอกสาร Office Open XML. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```


ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML แบบกำหนดเองเดียวอย่างไม่ซ้ำกันภายในเอกสาร Office Open XML. อ่านอย่างเดียว java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```


คืนคอลเลกชันของสกีม XML ที่เชื่อมโยงกับส่วน XML แบบกำหนดเอง. อ่านอย่างเดียว String[].

**คืนค่า:**
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```


ลบส่วน XML แบบกำหนดเองออกจากงานนำเสนอ.
---
title: CustomXmlPart
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แทนส่วน xml แบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/customxmlpart/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ใช้งานทั้งหมด:  
[com.aspose.slides.ICustomXmlPart](../../com.aspose.slides/icustomxmlpart)  
```
public class CustomXmlPart implements ICustomXmlPart
```

แทนส่วน xml แบบกำหนดเอง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXmlData()](#getXmlData--) | คืนค่า หรือ ตั้งข้อมูล xml. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | คืนค่า หรือ ตั้งข้อมูล xml. |
| [getXmlAsString()](#getXmlAsString--) | คืนค่า หรือ ตั้งข้อมูล xml เป็นสตริง UTF-8. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | คืนค่า หรือ ตั้งข้อมูล xml เป็นสตริง UTF-8. |
| [getItemId()](#getItemId--) | ระบุตัวระบุที่ไม่ซ้ำกันทั่วโลก (GUID) ที่ระบุส่วน XML แบบกำหนดเองหนึ่งส่วนในเอกสาร Office Open XML อย่างเฉพาะเจาะจง. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | ระบุตัวระบุที่ไม่ซ้ำกันทั่วโลก (GUID) ที่ระบุส่วน XML แบบกำหนดเองหนึ่งส่วนในเอกสาร Office Open XML อย่างเฉพาะเจาะจง. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | คืนค่าสะสมของ XML schemas ที่เชื่อมโยงกับส่วน XML แบบกำหนดเอง. |
| [remove()](#remove--) | ลบส่วน xml แบบกำหนดเองออกจากงานนำเสนอ. |
### getXmlData() {#getXmlData--}
```
public final byte[] getXmlData()
```

คืนค่า หรือ ตั้งข้อมูล xml. อ่าน/เขียน byte[].

**คืนค่า:**  
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public final void setXmlData(byte[] value)
```

คืนค่า หรือ ตั้งข้อมูล xml. อ่าน/เขียน byte[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |
### getXmlAsString() {#getXmlAsString--}
```
public final String getXmlAsString()
```

คืนค่า หรือ ตั้งข้อมูล xml เป็นสตริง UTF-8. อ่าน/เขียน String.

**คืนค่า:**  
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public final void setXmlAsString(String value)
```

คืนค่า หรือ ตั้งข้อมูล xml เป็นสตริง UTF-8. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getItemId() {#getItemId--}
```
public final UUID getItemId()
```

ระบุตัวระบุที่ไม่ซ้ำกันทั่วโลก (GUID) ที่ระบุส่วน XML แบบกำหนดเองหนึ่งส่วนในเอกสาร Office Open XML อย่างเฉพาะเจาะจง. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**  
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public final void setItemId(UUID value)
```

ระบุตัวระบุที่ไม่ซ้ำกันทั่วโลก (GUID) ที่ระบุส่วน XML แบบกำหนดเองหนึ่งส่วนในเอกสาร Office Open XML อย่างเฉพาะเจาะจง. อ่านอย่างเดียว java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public final String[] getNamespaceSchemas()
```

คืนค่าสะสมของ XML schemas ที่เชื่อมโยงกับส่วน XML แบบกำหนดเอง. อ่านอย่างเดียว String[].

**คืนค่า:**  
java.lang.String[]
### remove() {#remove--}
```
public final void remove()
```

ลบส่วน xml แบบกำหนดเองออกจากงานนำเสนอ.
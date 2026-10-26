---
title: ICustomXmlPart
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงส่วน XML ที่กำหนดเอง
type: docs
url: /th/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

แสดงส่วน XML ที่กำหนดเอง
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | คืนค่า หรือกำหนดข้อมูล XML เป็นสตริง UTF-8 อ่าน/เขียน String. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | คืนค่า หรือกำหนดข้อมูล XML เป็นสตริง UTF-8 อ่าน/เขียน String. |
| [getXmlData()](#getXmlData--) | คืนค่า หรือกำหนดข้อมูล XML. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | คืนค่า หรือกำหนดข้อมูล XML. |
| [getItemId()](#getItemId--) | ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML ที่กำหนดเองแบบเดี่ยวภายในเอกสาร Office Open XML อย่างเป็นเอกลักษณ์. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML ที่กำหนดเองแบบเดี่ยวภายในเอกสาร Office Open XML อย่างเป็นเอกลักษณ์. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | คืนคอลเลกชันของ XML schemas ที่เช关联กับส่วน XML ที่กำหนดเอง. |
| [remove()](#remove--) | ลบส่วน XML ที่กำหนดเองออกจากงานนำเสนอ. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

คืนค่า หรือกำหนดข้อมูล XML เป็นสตริง UTF-8 อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

คืนค่า หรือกำหนดข้อมูล XML เป็นสตริง UTF-8 อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

คืนค่า หรือกำหนดข้อมูล XML อ่าน/เขียน byte[].

**คืนค่า:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

คืนค่า หรือกำหนดข้อมูล XML อ่าน/เขียน byte[].

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |

### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML ที่กำหนดเองแบบเดี่ยวภายในเอกสาร Office Open XML อย่างเป็นเอกลักษณ์. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

ระบุ GUID (ตัวระบุที่ไม่ซ้ำกันทั่วโลก) ที่ระบุส่วน XML ที่กำหนดเองแบบเดี่ยวภายในเอกสาร Office Open XML อย่างเป็นเอกลักษณ์. อ่านอย่างเดียว java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |

### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

คืนคอลเลกชันของ XML schemas ที่เช关联กับส่วน XML ที่กำหนดเอง. อ่านอย่างเดียว String[].

**คืนค่า:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

ลบส่วน XML ที่กำหนดเองออกจากงานนำเสนอ.
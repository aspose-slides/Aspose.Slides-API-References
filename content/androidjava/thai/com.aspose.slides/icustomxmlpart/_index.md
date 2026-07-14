---
title: ICustomXmlPart
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงส่วน XML แบบกำหนดเอง.
type: docs
url: /th/com.aspose.slides/icustomxmlpart/
---```
public interface ICustomXmlPart
```

แสดงส่วน XML แบบกำหนดเอง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getXmlAsString()](#getXmlAsString--) | Returns or sets xml data as UTF-8 string. |
| [setXmlAsString(String value)](#setXmlAsString-java.lang.String-) | Returns or sets xml data as UTF-8 string. |
| [getXmlData()](#getXmlData--) | Returns or sets xml data. |
| [setXmlData(byte[] value)](#setXmlData-byte---) | Returns or sets xml data. |
| [getItemId()](#getItemId--) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [setItemId(UUID value)](#setItemId-java.util.UUID-) | Specifies a globally unique identifier (GUID) that uniquely identifies a single custom XML part within an Office Open XML document. |
| [getNamespaceSchemas()](#getNamespaceSchemas--) | Returns the collection XML schemas that are associated with the custom XML part. |
| [remove()](#remove--) | Removes the custom xml part from the presentation. |
### getXmlAsString() {#getXmlAsString--}
```
public abstract String getXmlAsString()
```

คืนค่า หรือกำหนดข้อมูล xml เป็นสตริง UTF-8. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setXmlAsString(String value) {#setXmlAsString-java.lang.String-}
```
public abstract void setXmlAsString(String value)
```

คืนค่า หรือกำหนดข้อมูล xml เป็นสตริง UTF-8. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getXmlData() {#getXmlData--}
```
public abstract byte[] getXmlData()
```

คืนค่า หรือกำหนดข้อมูล xml. อ่าน/เขียน byte[].

**คืนค่า:**
byte[]
### setXmlData(byte[] value) {#setXmlData-byte---}
```
public abstract void setXmlData(byte[] value)
```

คืนค่า หรือกำหนดข้อมูล xml. อ่าน/เขียน byte[].

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |
### getItemId() {#getItemId--}
```
public abstract UUID getItemId()
```

ระบุ GUID ที่เป็นตัวระบุตัวเดียวที่ไม่ซ้ำกันทั่วโลก ซึ่งระบุส่วน XML แบบกำหนดเองที่เป็นเอกลักษณ์หนึ่งภายในเอกสาร Office Open XML. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### setItemId(UUID value) {#setItemId-java.util.UUID-}
```
public abstract void setItemId(UUID value)
```

ระบุ GUID ที่เป็นตัวระบุตัวเดียวที่ไม่ซ้ำกันทั่วโลก ซึ่งระบุส่วน XML แบบกำหนดเองที่เป็นเอกลักษณ์หนึ่งภายในเอกสาร Office Open XML. อ่านอย่างเดียว java.util.UUID.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |
### getNamespaceSchemas() {#getNamespaceSchemas--}
```
public abstract String[] getNamespaceSchemas()
```

คืนค่าคอลเลกชันของสคีมา XML ที่เชื่อมโยงกับส่วน XML แบบกำหนดเอง. อ่านอย่างเดียว String[].

**คืนค่า:**
java.lang.String[]
### remove() {#remove--}
```
public abstract void remove()
```

ลบส่วน xml แบบกำหนดเองออกจากงานนำเสนอ.
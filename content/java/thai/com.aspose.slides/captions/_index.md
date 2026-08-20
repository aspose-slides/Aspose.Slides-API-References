---
title: Captions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนค่าคำบรรยายปิดของ WebVTT.
type: docs
url: /th/com.aspose.slides/captions/
---
**สืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

แทนค่าคำบรรยายปิดของ WebVTT.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | คืนค่า GUID (Globally Unique Identifier) ของคำบรรยายปิด. |
| [getLabel()](#getLabel--) | คืนค่า หรือ ตั้งค่าป้ายชื่อของคำบรรยายปิด. |
| [setLabel(String value)](#setLabel-java.lang.String-) | คืนค่า หรือ ตั้งค่าป้ายชื่อของคำบรรณยายปิด. |
| [getBinaryData()](#getBinaryData--) | คืนค่าข้อมูลไบต์ของคำบรรยายปิด. |
| [getDataAsString()](#getDataAsString--) | คืนค่าข้อมูลคำบรรยายปิดเป็นสตริงที่เข้ารหัส UTF-8 อ่านอย่างเดียว String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

คืนค่า GUID (Globally Unique Identifier) ของคำบรรยายปิด. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```

คืนค่า หรือ ตั้งค่าป้ายชื่อของคำบรรยายปิด. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

คืนค่า หรือ ตั้งค่าป้ายชื่อของคำบรรยายปิด. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

คืนค่าข้อมูลไบต์ของคำบรรยายปิด. อ่านอย่างเดียว byte[] .

**คืนค่า:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

คืนค่าข้อมูลคำบรรยายปิดเป็นสตริงที่เข้ารหัส UTF-8 อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
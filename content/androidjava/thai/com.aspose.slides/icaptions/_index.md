---
title: ICaptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นการแทนคำบรรยายปิดแบบ WebVTT
type: docs
url: /th/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

เป็นการแทนคำบรรยายปิดแบบ WebVTT
## Methods

| Method | Description |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | คืนค่าตัวระบุที่เป็นเอกลักษณ์ทั่วโลก (GUID) ของคำบรรยายปิด |
| [getLabel()](#getLabel--) | คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด |
| [setLabel(String value)](#setLabel-java.lang.String-) | คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด |
| [getBinaryData()](#getBinaryData--) | คืนค่าข้อมูลไบนารีของคำบรรยายปิด |
| [getDataAsString()](#getDataAsString--) | คืนค่าข้อมูลคำบรรยายที่ปิดเป็นสตริงที่เข้ารหัส UTF-8 แบบอ่านอย่างเดียว String |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

คืนค่าตัวระบุที่เป็นเอกลักษณ์ทั่วโลก (GUID) ของคำบรรยายปิด แบบอ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด แบบอ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด แบบอ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

คืนค่าข้อมูลไบนารีของคำบรรยายปิด แบบอ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

คืนค่าข้อมูลคำบรรยายที่ปิดเป็นสตริงที่เข้ารหัส UTF-8 แบบอ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
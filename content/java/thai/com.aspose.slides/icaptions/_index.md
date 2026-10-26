---
title: ICaptions
second_title: Aspose.Slides for Java API Reference
description: แทนค่าคำบรรยายปิดแบบ WebVTT.
type: docs
url: /th/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

แทนค่าคำบรรยายปิดแบบ WebVTT.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | Returns the globally unique identifier (GUID) of the closed captions. |
| [getLabel()](#getLabel--) | Returns or sets the label of the closed captions. |
| [setLabel(String value)](#setLabel-java.lang.String-) | Returns or sets the label of the closed captions. |
| [getBinaryData()](#getBinaryData--) | Returns the binary data of the closed captions. |
| [getDataAsString()](#getDataAsString--) | Returns the closed captions data as UTF-8 encoded string Read-only String. |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```

คืนค่า GUID ที่เป็นตัวระบุแบบเอกลักษณ์ทั่วโลกของคำบรรยายปิด. อ่านอย่างเดียว java.util.UUID.

**คืนค่า:**
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```

คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```

คืนค่าหรือกำหนดป้ายกำกับของคำบรรยายปิด. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

คืนค่าข้อมูลไบนารีของคำบรรยายปิด. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```

คืนค่าข้อมูลคำบรรยายปิดเป็นสตริงที่เข้ารหัส UTF-8. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
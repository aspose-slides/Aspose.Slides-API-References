---
title: Captions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของคำบรรยายแบบปิด WebVTT.
type: docs
url: /th/com.aspose.slides/captions/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)
```
public class Captions implements ICaptions
```

เป็นตัวแทนของคำบรรยายแบบปิด WebVTT.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ทั่วโลก (GUID) ของคำบรรยายแบบปิด. |
| [getLabel()](#getLabel--) | ส่งคืนหรือกำหนดป้ายกำกับของคำบรรยายแบบปิด. |
| [setLabel(String value)](#setLabel-java.lang.String-) | ส่งคืนหรือกำหนดป้ายกำกับของคำบรรยายแบบปิด. |
| [getBinaryData()](#getBinaryData--) | ส่งคืนข้อมูลไบนารีของคำบรรยายแบบปิด. |
| [getDataAsString()](#getDataAsString--) | ส่งคืนข้อมูลคำบรรยายแบบปิดเป็นสตริงที่เข้ารหัส UTF-8 อ่านอย่างเดียว String. |
### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```


ส่งคืนตัวระบุที่เป็นเอกลักษณ์ทั่วโลก (GUID) ของคำบรรยายแบบปิด. อ่านอย่างเดียว java.util.UUID.

**ผลลัพธ์:**
java.util.UUID
### getLabel() {#getLabel--}
```
public final String getLabel()
```


ส่งคืนหรือกำหนดป้ายกำกับของคำบรรยายแบบปิด. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```


ส่งคืนหรือกำหนดป้ายกำกับของคำบรรยายแบบปิด. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


ส่งคืนข้อมูลไบนารีของคำบรรยายแบบปิด. อ่านอย่างเดียว byte[] .

**ผลลัพธ์:**
byte[]
### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```


ส่งคืนข้อมูลคำบรรยายแบบปิดเป็นสตริงที่เข้ารหัส UTF-8 อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String
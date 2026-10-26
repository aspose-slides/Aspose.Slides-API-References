---
title: Audio
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงไฟล์เสียงที่ฝังอยู่.
type: docs
url: /th/com.aspose.slides/audio/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

แสดงถึงไฟล์เสียงที่ฝังอยู่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContentType()](#getContentType--) | ส่งคืนประเภท MIME ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | ส่งคืนประเภท MIME ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | ส่งคืนสำเนาของข้อมูลไฟล์เสียง. |
| [getStream()](#getStream--) | ส่งคืน Stream สำหรับการอ่าน. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

ส่งคืนประเภท MIME ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**คืนค่า:**  
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

ส่งคืนประเภท MIME ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

ส่งคืนสำเนาของข้อมูลไฟล์เสียง. ในกรณีที่ข้อมูลมีขนาดใหญ่ ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลไฟล์เสียงเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException. อ่านอย่างเดียว byte[].

**คืนค่า:**  
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```

ส่งคืน Stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังการใช้งาน.

**คืนค่า:**  
java.io.InputStream - Stream สำหรับการอ่าน.
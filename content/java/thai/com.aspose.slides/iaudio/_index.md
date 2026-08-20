---
title: IAudio
second_title: Aspose.Slides for Java API Reference
description: Represents an embedded audio file.
type: docs
url: /th/com.aspose.slides/iaudio/
---```
public interface IAudio
```

แสดงถึงไฟล์เสียงที่ฝังอยู่.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContentType()](#getContentType--) | คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | คืนสำเนาข้อมูลของไฟล์เสียง. |
| [getStream()](#getStream--) | คืน Stream stream สำหรับการอ่าน. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData) String แบบอ่านอย่างเดียว.

**คืนค่า:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

คืนสำเนาข้อมูลของไฟล์เสียง. ในกรณีที่ข้อมูลมีขนาดใหญ่ ควรใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลไฟล์เสียงเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException. byte[] แบบอ่านอย่างเดียว.

**คืนค่า:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

คืน Stream stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังจากใช้งาน.

**คืนค่า:**
java.io.InputStream - Stream สำหรับการอ่าน.
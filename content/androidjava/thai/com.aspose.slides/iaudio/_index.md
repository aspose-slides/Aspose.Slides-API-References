---
title: IAudio
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนไฟล์เสียงที่ฝังอยู่.
type: docs
url: /th/com.aspose.slides/iaudio/
---```
public interface IAudio
```

แทนไฟล์เสียงที่ฝังอยู่.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContentType()](#getContentType--) | คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | คืนค่าสำเนาของข้อมูลไฟล์เสียง. |
| [getStream()](#getStream--) | คืนค่า Stream stream สำหรับการอ่าน. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). String ที่อ่านได้เท่านั้น.

**คืนค่า:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

คืนค่าสำเนาของข้อมูลไฟล์เสียง. ในกรณีที่มีข้อมูลจำนวนมาก ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลไฟล์เสียงเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException. byte[] ที่อ่านได้เท่านั้น.

**คืนค่า:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```

คืนค่า Stream stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังใช้.

**คืนค่า:**
java.io.InputStream - Stream สำหรับการอ่าน.
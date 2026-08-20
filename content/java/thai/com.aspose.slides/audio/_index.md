---
title: Audio
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของไฟล์เสียงที่ฝังอยู่.
type: docs
url: /th/com.aspose.slides/audio/
---
**การสืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IAudio](../../com.aspose.slides/iaudio)  
```
public class Audio extends DomObject<AudioCollection> implements IAudio
```

เป็นตัวแทนของไฟล์เสียงที่ฝังอยู่.

## เมธอด

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [setContentType(String value)](#setContentType-java.lang.String-) | คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | คืนสำเนาข้อมูลของไฟล์เสียง. |
| [getStream()](#getStream--) | คืน Stream สำหรับการอ่าน. |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**คืนค่า:**  
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

คืนค่า MIME type ของไฟล์เสียงที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

คืนสำเนาข้อมูลของไฟล์เสียง. ในกรณีที่ข้อมูลมีขนาดใหญ่ ควรใช้เมธอด \#getStream.getStream เพื่อลดการโหลดข้อมูลไฟล์เสียงเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้แต่เกิด OutOfMemoryException. อ่านอย่างเดียว byte[].

**คืนค่า:**  
byte[]

### getStream() {#getStream--}
```
public final InputStream getStream()
```

คืน Stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังการใช้งาน.

**คืนค่า:**  
java.io.InputStream - Stream สำหรับการอ่าน.
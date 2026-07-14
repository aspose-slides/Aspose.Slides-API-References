---
title: Video
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนภาพที่ฝังไว้ในงานพรีเซนเทชัน.
type: docs
url: /th/com.aspose.slides/video/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject  
```
public class Video implements IVideo, IDOMObject
```

แทนภาพที่ฝังไว้ในงานพรีเซนเทชัน  

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContentType()](#getContentType--) | ส่งคืนชนิด MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | ส่งคืนสำเนาของข้อมูลเสียง. |
| [getStream()](#getStream--) | ส่งคืน Stream สำหรับการอ่าน. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

ส่งคืนชนิด MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**ส่งคืน:**  
java.lang.String  

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

ส่งคืนสำเนาของข้อมูลเสียง. ในกรณีที่ข้อมูลมีขนาดใหญ่ ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลวิดีโอเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException. อ่านอย่างเดียว byte[].

**ส่งคืน:**  
byte[]  

### getStream() {#getStream--}
```
public final InputStream getStream()
```

ส่งคืน Stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังการใช้งาน.

**ส่งคืน:**  
java.io.InputStream - Stream สำหรับการอ่าน.  

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**  
com.aspose.slides.IDOMObject
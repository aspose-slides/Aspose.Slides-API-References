---
title: Video
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: เป็นการแสดงภาพที่ฝังไว้ในงานนำเสนอ.
type: docs
url: /th/com.aspose.slides/video/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IVideo](../../com.aspose.slides/ivideo), com.aspose.slides.IDOMObject
```
public class Video implements IVideo, IDOMObject
```

เป็นการแสดงภาพที่ฝังไว้ในงานนำเสนอ.
## เมธอด

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


ส่งคืนชนิด MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). String ที่อ่านอย่างเดียว.

**ส่งคืน:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


ส่งคืนสำเนาของข้อมูลเสียง. ในกรณีที่มีข้อมูลจำนวนมาก ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลวิดีโอเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้กระทั่ง OutOfMemoryException. byte[] ที่อ่านอย่างเดียว.

**ส่งคืน:**
byte[]
### getStream() {#getStream--}
```
public final InputStream getStream()
```


ส่งคืน Stream สำหรับการอ่าน ใช้ 'using' หรือปิด stream หลังการใช้.

**ส่งคืน:**
java.io.InputStream - Stream สำหรับการอ่าน.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


ส่งคืนอ็อบเจกต์ Parent_Immediate. IDOMObject ที่อ่านอย่างเดียว.

**ส่งคืน:**
com.aspose.slides.IDOMObject
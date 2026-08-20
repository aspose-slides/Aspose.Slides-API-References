---
title: IVideo
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงวิดีโอที่ฝังไว้ในงานนำเสนอ
type: docs
url: /th/com.aspose.slides/ivideo/
---```
public interface IVideo
```

แสดงถึงวิดีโอที่ฝังไว้ในงานนำเสนอ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getContentType()](#getContentType--) | ส่งคืนประเภท MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | ส่งคืนสำเนาข้อมูลของออดิโอ. |
| [getStream()](#getStream--) | ส่งคืนสตรีม Stream สำหรับการอ่าน. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


ส่งคืนประเภท MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData) อ่านอย่างเดียว String.

**ผลลัพธ์:**
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


ส่งคืนสำเนาข้อมูลของออดิโอ. ในกรณีที่มีปริมาณข้อมูลมาก ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลของวิดีโอเข้าสู่หน่วยความจำโดยไม่จำเป็นหรือแม้แต่ OutOfMemoryException. อ่านอย่างเดียว byte[].

**ผลลัพธ์:**
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


ส่งคืนสตรีม Stream สำหรับการอ่าน. ใช้ 'using' หรือปิดสตรีมหลังจากการใช้.

**ผลลัพธ์:**
java.io.InputStream - สตรีมสำหรับการอ่าน.
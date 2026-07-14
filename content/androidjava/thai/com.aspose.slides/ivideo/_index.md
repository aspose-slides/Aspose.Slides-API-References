---
title: IVideo
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a video embedded into a presentation.
type: docs
url: /th/com.aspose.slides/ivideo/
---```
public interface IVideo
```

แสดงถึงวิดีโอที่ฝังอยู่ในงานนำเสนอ.
## เมธอด

| Method | Description |
| --- | --- |
| [getContentType()](#getContentType--) | คืนค่าประเภท MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). |
| [getBinaryData()](#getBinaryData--) | คืนค่าสำเนาของข้อมูลเสียง. |
| [getStream()](#getStream--) | คืนค่า Stream สำหรับการอ่าน. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


คืนค่าประเภท MIME ของวิดีโอที่เข้ารหัสใน (\#getBinaryData.getBinaryData). อ่านอย่างเดียว String.

**คืนค่า:**  
java.lang.String
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


คืนค่าสำเนาของข้อมูลเสียง. ในกรณีที่มีข้อมูลจำนวนมาก ควรพิจารณาใช้เมธอด \#getStream.getStream เพื่อป้องกันการโหลดข้อมูลวิดีโอเข้าสู่หน่วยความจำโดยไม่จำเป็น หรือแม้กระทั่ง OutOfMemoryException. อ่านอย่างเดียว byte[].

**คืนค่า:**  
byte[]
### getStream() {#getStream--}
```
public abstract InputStream getStream()
```


คืนค่า Stream สำหรับการอ่าน. ใช้ 'using' หรือปิด stream หลังจากใช้เสร็จ.

**คืนค่า:**  
java.io.InputStream - Stream สำหรับการอ่าน.
---
title: ILinkEmbedController
second_title: Aspose.Slides for Android via Java API Reference
description: Callback interface used to determine how object should be processed during saving.
type: docs
url: /th/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

ส่วนต่อประสานแบบเรียกกลับที่ใช้เพื่อกำหนดว่าควรประมวลผลวัตถุอย่างไรระหว่างการบันทึก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | ระบุที่เก็บวัตถุว่าอยู่ที่ไหน |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | คืนค่า URL ไปยังวัตถุภายนอก |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | บันทึกวัตถุภายนอก |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


ระบุว่าควรเก็บวัตถุไว้ที่ไหน เมธอดนี้เรียกหนึ่งครั้งต่อแต่ละรหัสวัตถุ ไม่ได้รับประกันว่าจะไม่มีวัตุสองรายการที่มีข้อมูลเดียวกัน semanticName และ contentType แต่มีรหัสต่างกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | รหัสวัตถุ รหัสนี้เป็นค่าเฉพาะทั่วการดำเนินการบันทึก |
| entityData | byte[] | ข้อมูลไบนารีของวัตถุ พารามิเตอร์นี้อาจเป็น null หากข้อมูลไบนารีของวัตถุยังไม่ได้สร้าง |
| semanticName | java.lang.String | ข้อความสั้น ๆ ที่อธิบายความหมายของวัตถุ คอนโทรลเลอร์อาจใช้เป็นส่วนหนึ่งของชื่อวัตถุภายนอก แต่การที่ชื่อจะต้องเป็นเอกลักษณ์และมีเฉพาะอักขระที่อนุญาตเป็นหน้าที่ของ dispatcher |
| contentType | java.lang.String | ประเภท MIME ของวัตถุ |
| recomendedExtension | java.lang.String | ส่วนต่อท้ายของชื่อไฟล์ที่แนะนำสำหรับประเภท MIME นี้ |

**คืนค่า:**
int - การตัดสินใจ
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


คืนค่า URL ไปยังวัตถุภายนอก เมธอดนี้จะถูกเรียกเสมอหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) และอาจถูกเรียกหาก \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) แต่ไม่สามารถฝังได้ สามารถเรียกหลายครั้งสำหรับรหัสวัตถุเดียวกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | รหัสวัตถุ รหัสนี้เป็นค่าเฉพาะทั่วการดำเนินการบันทึก |
| referrer | int | รหัสของวัตถุที่อ้างอิงหรือ 0 หากวัตถุถูกอ้างอิงโดยเอกสารราก อาจใช้เพื่อสร้างลิงก์สัมพันธ์ |

**คืนค่า:**
java.lang.String - URL ของวัตถุภายนอก หรือ null หากควรละเว้นวัตถุนี้
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


บันทึกวัตถุภายนอก.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | รหัสวัตถุ รหัสนี้เป็นค่าเฉพาะทั่วการดำเนินการบันทึก |
| entityData | byte[] | ข้อมูลไบนารีของวัตถุ พารามิเตอร์นี้ไม่สามารถเป็น null ได้ |
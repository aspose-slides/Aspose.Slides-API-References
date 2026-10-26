---
title: ILinkEmbedController
second_title: Aspose.Slides for Java API Reference
description: ส่วนต่อประสานการเรียกกลับที่ใช้เพื่อกำหนดวิธีการประมวลผลวัตถุระหว่างการบันทึก.
type: docs
url: /th/com.aspose.slides/ilinkembedcontroller/
---```
public interface ILinkEmbedController
```

ส่วนต่อประสานการเรียกกลับที่ใช้เพื่อกำหนดวิธีการประมวลผลวัตถุระหว่างการบันทึก.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) | กำหนดตำแหน่งที่วัตถุจะถูกจัดเก็บ |
| [getUrl(int id, int referrer)](#getUrl-int-int-) | คืนค่า URL ของวัตถุภายนอก |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) | บันทึกวัตถุภายนอก |
### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public abstract int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


กำหนดตำแหน่งที่วัตถุจะถูกจัดเก็บ เมธอดนี้จะถูกเรียกหนึ่งครั้งต่อแต่ละ ID ของวัตถุ ไม่ได้รับประกันว่าจะไม่มีวัตถุสองรายการที่มีข้อมูล, semanticName และ contentType เดียวกันแต่มี ID ต่างกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | ID ของวัตถุ ID นี้เป็นค่าเฉพาะสำหรับการดำเนินการบันทึกทั้งหมด |
| entityData | byte[] | ข้อมูลไบนารีของวัตถุ พารามิเตอร์นี้สามารถเป็น null ได้ หากข้อมูลไบนารีของวัตถุยังไม่ถูกสร้าง |
| semanticName | java.lang.String | ข้อความสั้น ๆ ที่อธิบายความหมายของวัตถุ ตัวควบคุมอาจใช้เป็นส่วนหนึ่งของชื่อวัตถุภายนอก แต่การรับประกันว่าชื่อจะเป็นเอกลักษณ์และมีเฉพาะอักขระที่อนุญาตอยู่ที่ผู้จัดการการกระจาย |
| contentType | java.lang.String | ประเภท MIME ของวัตถุ |
| recomendedExtension | java.lang.String | ส่วนขยายของชื่อไฟล์ที่แนะนำสำหรับประเภท MIME นี้ |

**ผลลัพธ์:**
int - การตัดสินใจ
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public abstract String getUrl(int id, int referrer)
```


คืนค่า URL ของวัตถุภายนอก เมธอดนี้จะถูกเรียกเสมอหาก #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) และอาจถูกเรียกหาก #getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) คืนค่า [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) แต่ไม่สามารถฝังได้ สามารถเรียกหลายครั้งสำหรับ ID ของวัตถุเดียวกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | ID ของวัตถุ ID นี้เป็นค่าเฉพาะสำหรับการดำเนินการบันทึกทั้งหมด |
| referrer | int | ID ของวัตถุอ้างอิงหรือ 0 หากวัตถุถูกอ้างอิงโดยเอกสารราก อาจใช้เพื่อสร้างลิงก์สัมพันธ์ |

**ผลลัพธ์:**
java.lang.String - URL ของวัตถุภายนอกหรือ null หากควรละเว้นวัตถุนี้
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public abstract void saveExternal(int id, byte[] entityData)
```


บันทึกวัตถุภายนอก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| id | int | ID ของวัตถุ ID นี้เป็นค่าเฉพาะสำหรับการดำเนินการบันทึกทั้งหมด |
| entityData | byte[] | ข้อมูลไบนารีของวัตถุ พารามิเตอร์นี้ไม่สามารถเป็น null ได้ |
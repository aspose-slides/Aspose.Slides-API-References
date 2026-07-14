---
title: PptxReadException
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนข้อยกเว้นที่ถูกโยนเมื่อเกิดข้อผิดพลาดในการอ่านการนำเสนอ
type: docs
url: /th/com.aspose.slides/pptxreadexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception)
```
public class PptxReadException extends PptxException
```

แทนข้อยกเว้นที่ถูกโยนเมื่อเกิดข้อผิดพลาดในการอ่านการนำเสนอ
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [PptxReadException()](#PptxReadException--) | ตัวสร้างเริ่มต้น. |
| [PptxReadException(String message)](#PptxReadException-java.lang.String-) | ตัวสร้างที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้. |
| [PptxReadException(String message, RuntimeException exception)](#PptxReadException-java.lang.String-java.lang.RuntimeException-) | ตัวสร้างสำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่. |
### PptxReadException() {#PptxReadException--}
```
public PptxReadException()
```


ตัวสร้างเริ่มต้น.

### PptxReadException(String message) {#PptxReadException-java.lang.String-}
```
public PptxReadException(String message)
```


ตัวสร้างที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | ข้อความ |

### PptxReadException(String message, RuntimeException exception) {#PptxReadException-java.lang.String-java.lang.RuntimeException-}
```
public PptxReadException(String message, RuntimeException exception)
```


ตัวสร้างสำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่.

**Parameters:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | ข้อความ |
| exception | java.lang.RuntimeException | ข้อยกเว้นต้นฉบับ |
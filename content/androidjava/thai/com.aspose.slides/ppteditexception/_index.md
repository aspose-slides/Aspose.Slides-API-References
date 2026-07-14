---
title: PptEditException
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงข้อยกเว้นที่ถูกโยนเมื่อพบข้อผิดพลาดในการแก้ไขการนำเสนอ
type: docs
url: /th/com.aspose.slides/ppteditexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.PptException](../../com.aspose.slides/pptexception)
```
public class PptEditException extends PptException
```

แสดงถึงข้อยกเว้นที่เกิดขึ้นเมื่อพบข้อผิดพลาดในการแก้ไขการนำเสนอ

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PptEditException()](#PptEditException--) | คอนสตรัคเตอร์เริ่มต้น |
| [PptEditException(String message)](#PptEditException-java.lang.String-) | คอนสตรัคเตอร์ที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้ |
| [PptEditException(String message, RuntimeException exception)](#PptEditException-java.lang.String-java.lang.RuntimeException-) | คอนสตรัคเตอร์สำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่ |

### PptEditException() {#PptEditException--}
```
public PptEditException()
```

คอนสตรัคเตอร์เริ่มต้น

### PptEditException(String message) {#PptEditException-java.lang.String-}
```
public PptEditException(String message)
```

คอนสตรัคเตอร์ที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | ข้อความ |

### PptEditException(String message, RuntimeException exception) {#PptEditException-java.lang.String-java.lang.RuntimeException-}
```
public PptEditException(String message, RuntimeException exception)
```

คอนสตรัคเตอร์สำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | ข้อความ |
| exception | java.lang.RuntimeException | ข้อยกเว้นเดิม |
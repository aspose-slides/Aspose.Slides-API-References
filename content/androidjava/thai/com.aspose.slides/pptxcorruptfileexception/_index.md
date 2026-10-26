---
title: PptxCorruptFileException
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: ข้อยกเว้นที่ถูกโยนเมื่อไฟล์งานนำเสนออาจเสียหาย.
type: docs
url: /th/com.aspose.slides/pptxcorruptfileexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxReadException](../../com.aspose.slides/pptxreadexception)
```
public class PptxCorruptFileException extends PptxReadException
```

Exception which thrown when presentation file is probably corrupt.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PptxCorruptFileException()](#PptxCorruptFileException--) | คอนสตรัคเตอร์เริ่มต้น. |
| [PptxCorruptFileException(String message)](#PptxCorruptFileException-java.lang.String-) | คอนสตรัคเตอร์ที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้. |
| [PptxCorruptFileException(String message, RuntimeException exception)](#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-) | คอนสตรัคเตอร์สำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่. |
### PptxCorruptFileException() {#PptxCorruptFileException--}
```
public PptxCorruptFileException()
```


คอนสตรัคเตอร์เริ่มต้น.

### PptxCorruptFileException(String message) {#PptxCorruptFileException-java.lang.String-}
```
public PptxCorruptFileException(String message)
```


คอนสตรัคเตอร์ที่อนุญาตให้เพิ่มข้อความไปยังข้อยกเว้นนี้.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | message |

### PptxCorruptFileException(String message, RuntimeException exception) {#PptxCorruptFileException-java.lang.String-java.lang.RuntimeException-}
```
public PptxCorruptFileException(String message, RuntimeException exception)
```


คอนสตรัคเตอร์สำหรับข้อยกเว้นที่มีข้อความและข้อยกเว้นที่ฝังอยู่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | message |
| exception | java.lang.RuntimeException | original exception |
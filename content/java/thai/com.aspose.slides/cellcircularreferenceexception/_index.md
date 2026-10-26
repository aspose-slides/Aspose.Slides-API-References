---
title: CellCircularReferenceException
second_title: Aspose.Slides สำหรับ Java API Reference
description: ข้อยกเว้นที่ถูกโยนขึ้นเมื่อพบการอ้างอิงแบบวงกลมหนึ่งหรือหลายรายการ โดยสูตรอ้างอิงถึงเซลล์ของตนเองโดยตรงหรือโดยอ้อม
type: docs
url: /th/com.aspose.slides/cellcircularreferenceexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellCircularReferenceException extends PptxEditException
```

ข้อยกเว้นที่ถูกโยนเมื่อพบการอ้างอิงแบบวงกลมหนึ่งหรือหลายรายการที่สูตรอ้างอิงถึงเซลล์ของตนเองโดยตรงหรือโดยอ้อม.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [CellCircularReferenceException()](#CellCircularReferenceException--) | สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) |
| [CellCircularReferenceException(String message)](#CellCircularReferenceException-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุ |
| [CellCircularReferenceException(String message, RuntimeException innerException)](#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุและการอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้ |
| [CellCircularReferenceException(String message, String reference)](#CellCircularReferenceException-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุและการอ้างอิงเซลล์แบบวงกลม |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getReference()](#getReference--) | รับการอ้างอิงเซลล์แบบวงกลม |
### CellCircularReferenceException() {#CellCircularReferenceException--}
```
public CellCircularReferenceException()
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception).

### CellCircularReferenceException(String message) {#CellCircularReferenceException-java.lang.String-}
```
public CellCircularReferenceException(String message)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |

### CellCircularReferenceException(String message, RuntimeException innerException) {#CellCircularReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellCircularReferenceException(String message, RuntimeException innerException)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุและการอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| innerException | java.lang.RuntimeException | ข้อยกเว้นที่เป็นสาเหตุของข้อยกเว้นปัจจุบัน |

### CellCircularReferenceException(String message, String reference) {#CellCircularReferenceException-java.lang.String-java.lang.String-}
```
public CellCircularReferenceException(String message, String reference)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความแสดงข้อผิดพลาดที่ระบุและการอ้างอิงเซลล์แบบวงกลม.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| reference | java.lang.String | การอ้างอิงเซลล์แบบวงกลม |

### getReference() {#getReference--}
```
public final String getReference()
```

รับการอ้างอิงเซลล์แบบวงกลม.

**ส่งกลับ:**
java.lang.String
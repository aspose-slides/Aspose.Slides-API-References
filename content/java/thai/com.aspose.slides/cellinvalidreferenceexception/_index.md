---
title: CellInvalidReferenceException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ข้อยกเว้นที่เกิดขึ้นเมื่อพบการอ้างอิงเซลล์ที่ไม่ถูกต้อง
type: docs
url: /th/com.aspose.slides/cellinvalidreferenceexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidReferenceException extends PptxEditException
```

ข้อยกเว้นที่เกิดขึ้นเมื่อพบการอ้างอิงเซลล์ที่ไม่ถูกต้อง
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [CellInvalidReferenceException()](#CellInvalidReferenceException--) | สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) |
| [CellInvalidReferenceException(String message)](#CellInvalidReferenceException-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุ |
| [CellInvalidReferenceException(String message, RuntimeException innerException)](#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้ |
| [CellInvalidReferenceException(String message, String reference)](#CellInvalidReferenceException-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุและการอ้างอิงเซลล์ที่ไม่ถูกต้อง |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getReference()](#getReference--) | รับการอ้างอิงเซลล์ที่ไม่ถูกต้อง |
### CellInvalidReferenceException() {#CellInvalidReferenceException--}
```
public CellInvalidReferenceException()
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception)

### CellInvalidReferenceException(String message) {#CellInvalidReferenceException-java.lang.String-}
```
public CellInvalidReferenceException(String message)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |

### CellInvalidReferenceException(String message, RuntimeException innerException) {#CellInvalidReferenceException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidReferenceException(String message, RuntimeException innerException)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidReferenceException](../../com.aspose.slides/cellinvalidreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| innerException | java.lang.RuntimeException | ข้อยกเว้นที่เป็นสาเหตุของข้อยกเว้นปัจจุบัน |

### CellInvalidReferenceException(String message, String reference) {#CellInvalidReferenceException-java.lang.String-java.lang.String-}
```
public CellInvalidReferenceException(String message, String reference)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellCircularReferenceException](../../com.aspose.slides/cellcircularreferenceexception) พร้อมข้อความข้อผิดพลาดที่ระบุและการอ้างอิงเซลล์ที่ไม่ถูกต้อง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| reference | java.lang.String | การอ้างอิงเซลล์ที่ไม่ถูกต้อง |

### getReference() {#getReference--}
```
public final String getReference()
```

รับการอ้างอิงเซลล์ที่ไม่ถูกต้อง

**คืนค่า:**
java.lang.String
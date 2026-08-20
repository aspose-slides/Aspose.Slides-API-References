---
title: CellInvalidFormulaException
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ข้อยกเว้นที่เกิดขึ้นเมื่อสูตรที่คำนวณได้ไม่ถูกต้องหรือไม่สามารถแยกวิเคราะห์ได้.
type: docs
url: /th/com.aspose.slides/cellinvalidformulaexception/
---
**การสืบทอด:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.slides.OOXMLException](../../com.aspose.slides/ooxmlexception), [com.aspose.slides.PptxException](../../com.aspose.slides/pptxexception), [com.aspose.slides.PptxEditException](../../com.aspose.slides/pptxeditexception)
```
public class CellInvalidFormulaException extends PptxEditException
```

ข้อยกเว้นที่เกิดขึ้นเมื่อสูตรที่คำนวณได้ไม่ถูกต้องหรือไม่สามารถแยกวิเคราะห์ได้.
## คอนสตรัคเตอร์

| Constructor | Description |
| --- | --- |
| [CellInvalidFormulaException()](#CellInvalidFormulaException--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) |
| [CellInvalidFormulaException(String message)](#CellInvalidFormulaException-java.lang.String-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุ |
| [CellInvalidFormulaException(String message, RuntimeException innerException)](#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้ |
| [CellInvalidFormulaException(String message, String reference)](#CellInvalidFormulaException-java.lang.String-java.lang.String-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงเซลล์ที่มีสูตรที่ไม่ถูกต้อง |

## เมธอด

| Method | Description |
| --- | --- |
| [getReference()](#getReference--) | รับอ้างอิงเซลล์ที่มีสูตรที่ไม่ถูกต้อง |

### CellInvalidFormulaException() {#CellInvalidFormulaException--}
```
public CellInvalidFormulaException()
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception).

### CellInvalidFormulaException(String message) {#CellInvalidFormulaException-java.lang.String-}
```
public CellInvalidFormulaException(String message)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |

### CellInvalidFormulaException(String message, RuntimeException innerException) {#CellInvalidFormulaException-java.lang.String-java.lang.RuntimeException-}
```
public CellInvalidFormulaException(String message, RuntimeException innerException)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงถึงข้อยกเว้นภายในที่เป็นสาเหตุของข้อยกเว้นนี้

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| innerException | java.lang.RuntimeException | ข้อยกเว้นที่เป็นสาเหตุของข้อยกเว้นปัจจุบัน |

### CellInvalidFormulaException(String message, String reference) {#CellInvalidFormulaException-java.lang.String-java.lang.String-}
```
public CellInvalidFormulaException(String message, String reference)
```

สร้างอินสแตนซ์ใหม่ของคลาส [CellInvalidFormulaException](../../com.aspose.slides/cellinvalidformulaexception) พร้อมข้อความข้อผิดพลาดที่ระบุและอ้างอิงเซลล์ที่มีสูตรที่ไม่ถูกต้อง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| message | java.lang.String | สตริงที่อธิบายข้อผิดพลาด |
| reference | java.lang.String | สตริงที่อธิบายอ้างอิงถึงข้อยกเว้นภายใน |

### getReference() {#getReference--}
```
public final String getReference()
```

รับอ้างอิงเซลล์ที่มีสูตรที่ไม่ถูกต้อง

**ผลลัพธ์:**
java.lang.String
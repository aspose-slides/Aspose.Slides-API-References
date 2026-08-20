---
title: MathematicalTextFactory
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อนุญาตให้สร้างองค์ประกอบ MathematicalText
type: docs
url: /th/com.aspose.slides/mathematicaltextfactory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำงานทั้งหมด:**  
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)  
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

อนุญาตให้สร้างองค์ประกอบ MathematicalText

--------------------

สำหรับความเข้ากันได้กับ COM  

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | สร้างองค์ประกอบข้อความคณิตศาสตร์ว่าง |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | สร้างองค์ประกอบข้อความคณิตศาสตร์ว่างด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | สร้างองค์ประกอบข้อความคณิตศาสตร์ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ |

### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

สร้างองค์ประกอบข้อความคณิตศาสตร์ว่าง  

**ผลลัพธ์:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text  

### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char | สัญลักษณ์เดียวที่ใช้เป็นค่าข้อความ |

**ผลลัพธ์:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text  

### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

สร้างองค์ประกอบข้อความคณิตศาสตร์ว่างด้วยค่าที่ระบุ  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |

**ผลลัพธ์:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text  

### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

สร้างองค์ประกอบข้อความคณิตศาสตร์ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ  

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | การตั้งค่ารูปแบบข้อความ |

**ผลลัพธ์:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text
---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: อนุญาตให้สร้างองค์ประกอบ MathematicalText
type: docs
url: /th/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

อนุญาตให้สร้างองค์ประกอบ MathematicalText

--------------------

เพื่อความเข้ากันได้กับ COM
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | สร้างองค์ประกอบ MathematicalText ว่าง |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | สร้างองค์ประกอบ MathematicalText ด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | สร้างองค์ประกอบ MathematicalText ว่างด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | สร้างองค์ประกอบ MathematicalText ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

สร้างองค์ประกอบ MathematicalText ว่าง

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

สร้างองค์ประกอบ MathematicalText ด้วยค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char | สัญลักษณ์เดี่ยวที่ใช้เป็นค่าของข้อความ |

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

สร้างองค์ประกอบ MathematicalText ว่างด้วยค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

สร้างองค์ประกอบ MathematicalText ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | การตั้งค่าการจัดรูปแบบข้อความ |

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
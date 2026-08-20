---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /th/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

อนุญาตให้สร้างส่วนประกอบ MathematicalText

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | สร้าง MathematicalText element ว่าง |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | สร้าง MathematicalText element ด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | สร้าง MathematicalText element ว่างด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | สร้าง MathematicalText element ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ |

### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


สร้าง MathematicalText element ว่าง

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text

### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


สร้าง MathematicalText element ด้วยค่าที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathSymbol | char | สัญลักษณ์เดี่ยวที่จะใช้เป็นค่าข้อความ |

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text

### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


สร้าง MathematicalText element ว่างด้วยค่าที่ระบุ

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


สร้าง MathematicalText element ว่างด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | การตั้งค่ารูปแบบข้อความ |

**ผลลัพธ์:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
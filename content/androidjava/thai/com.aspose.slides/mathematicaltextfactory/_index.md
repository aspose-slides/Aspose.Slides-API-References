---
title: MathematicalTextFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้างองค์ประกอบ MathematicalText
type: docs
url: /th/com.aspose.slides/mathematicaltextfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

อนุญาตให้สร้างองค์ประกอบ MathematicalText

--------------------

เพื่อความเข้ากันได้กับ COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุ |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่า

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


สร้างองค์ประกอบข้อความคณิตศาสตร์ด้วยค่าที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | สัญลักษณ์เดี่ยวที่ใช้เป็นค่าข้อความ |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


สร้างองค์ประกอบข้อความคณิตศาสตร์เปล่าด้วยค่าที่ระบุและคุณสมบัติการจัดรูปแบบ

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | ค่าข้อความ |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | การตั้งค่ารูปแบบข้อความ |

**Returns:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ใหม่ Mathematical Text
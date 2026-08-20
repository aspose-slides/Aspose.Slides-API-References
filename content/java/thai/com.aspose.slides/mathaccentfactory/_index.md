---
title: MathAccentFactory
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อนุญาตให้สร้างเครื่องหมายคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathaccentfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

อนุญาตให้สร้างเครื่องหมายคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักขระเครื่องหมายเริ่มต้น |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุโดยใช้ค่าตัวอักขระเครื่องหมายเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์เพื่อใช้กับเครื่องหมาย |

**ผลลัพธ์:**
[IMathAccent](../../com.aspose.slides/imathaccent) - เครื่องหมายคณิตศาสตร์ใหม่
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


สร้างเครื่องหมายคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์เพื่อใช้กับเครื่องหมาย |
| accentCharacter | char | ตัวอักขระเครื่องหมาย |

**ผลลัพธ์:**
[IMathAccent](../../com.aspose.slides/imathaccent) - เครื่องหมายคณิตศาสตร์ใหม่
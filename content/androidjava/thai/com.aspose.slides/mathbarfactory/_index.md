---
title: MathBarFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้างแถบคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathbarfactory/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IMathBarFactory](../../com.aspose.slides/imathbarfactory)
```
public class MathBarFactory implements IMathBarFactory
```

อนุญาตให้สร้างแถบคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathBarFactory()](#MathBarFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Create a math bar by applying to the element |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Create a math bar by applying to the element |
### MathBarFactory() {#MathBarFactory--}
```
public MathBarFactory()
```

### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public final IMathBar createMathBar(IMathElement element)
```

สร้างแถบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply bar |

**ผลลัพธ์:**
[IMathBar](../../com.aspose.slides/imathbar) - new math bar element
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public final IMathBar createMathBar(IMathElement element, int position)
```

สร้างแถบคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Math element to apply bar |
| position | int | Position of the bar |

**ผลลัพธ์:**
[IMathBar](../../com.aspose.slides/imathbar) - new math bar element
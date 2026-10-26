---
title: MathFunctionFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้างฟังก์ชันคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/mathfunctionfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

**อนุญาตให้สร้างฟังก์ชันคณิตศาสตร์**

--------------------

เพื่อความเข้ากันได้กับ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | อีลิเมนต์ที่ใช้เป็นชื่อฟังก์ชัน |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อีลิเมนต์ที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**การคืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณิตศาสตร์ใหม่
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | java.lang.String | Function name |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อีลิเมนต์ที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**การคืนค่า:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณิตศาสตร์ใหม่
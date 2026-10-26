---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: อนุญาตให้สร้างฟังก์ชันคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

อนุญาตให้สร้างฟังก์ชันคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | อิลเมนต์ที่ใช้เป็นชื่อฟังก์ชัน |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อิลเมนต์ที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณิตศาสตร์ใหม่
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| funcName | java.lang.String | ชื่อฟังก์ชัน |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อิลเมนต์ที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณาตศาสตร์ใหม่
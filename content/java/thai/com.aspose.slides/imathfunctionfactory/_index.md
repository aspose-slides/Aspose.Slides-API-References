---
title: IMathFunctionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math function
type: docs
url: /th/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

อนุญาตให้สร้างฟังก์ชันคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้ของ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้างฟังก์ชันคณิตศาสตร์ |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | สร้างฟังก์ชันคณิตศาสตร์ |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ใช้เป็นชื่อฟังก์ชัน |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณิตศาสตร์ใหม่
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


สร้างฟังก์ชันคณิตศาสตร์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| funcName | java.lang.String | ชื่อฟังก์ชัน |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบที่ใช้เป็นอาร์กิวเมนต์ของฟังก์ชัน |

**ผลลัพธ์:**
[IMathFunction](../../com.aspose.slides/imathfunction) - ฟังก์ชันคณิตศาสตร์ใหม่
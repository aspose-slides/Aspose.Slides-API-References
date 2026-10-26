---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android ผ่าน Java API Reference
description: อนุญาตให้สร้างตัวคั่นคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

อนุญาตให้สร้างตัวคั่นคณิตศาสตร์

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | สร้างตัวคั่นคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | สร้างตัวคั่นคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

สร้างตัวคั่นคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบคณิตศาสตร์ที่จะนำคั่น |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ตัวคั่นคณิตศาสตร์ใหม่
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

สร้างตัวคั่นคณิตศาสตร์โดยนำไปใช้กับองค์ประกอบ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | องค์ประกอบคณิตศาสตร์ที่จะนำคั่น |

**คืนค่า:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - ตัวคั่นคณิตศาสตร์ใหม่
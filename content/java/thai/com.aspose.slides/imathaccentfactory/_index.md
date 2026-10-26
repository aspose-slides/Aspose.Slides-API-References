---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้างการเน้นคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

อนุญาตให้สร้างการเน้นคณิตศาสตร์

--------------------

For COM comparibility
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

สร้างการเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุพร้อมค่าตัวอักษรการเน้นเริ่มต้น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |

**ผลลัพธ์:**
[IMathAccent](../../com.aspose.slides/imathaccent) - การเน้นคณิตศาสตร์ใหม่
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

สร้างการเน้นคณิตศาสตร์ที่ใช้กับองค์ประกอบคณิตศาสตร์ที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply accent |
| accentCharacter | char | accent character |

**ผลลัพธ์:**
[IMathAccent](../../com.aspose.slides/imathaccent) - การเน้นคณิตศาสตร์ใหม่
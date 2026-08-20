---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้าง IMathLimit
type: docs
url: /th/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

อนุญาตให้สร้าง IMathLimit

--------------------

สำหรับการเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

สร้าง IMathLimit

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้จำกัด |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบจำกัด |
| upperLimit | boolean | กำหนดตำแหน่งของจำกัดที่ด้านบน |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ตัวจำกัดคณิตศาสตร์ใหม่
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

สร้าง IMathLimit พร้อมจำกัดที่ด้านล่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้จำกัด |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบจำกัด |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ตัวจำกัดคณิตศาสตร์ใหม่
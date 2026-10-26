---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /th/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

อนุญาตให้สร้าง IMathLimit

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | สร้าง IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathLimit พร้อมลิมิตที่ด้านล่าง |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

สร้าง IMathLimit

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้ลิมิต |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบลิมิต |
| upperLimit | boolean | กำหนดตำแหน่งของลิมิตที่ด้านบน |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ลิมิตคณิตใหม่
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

สร้าง IMathLimit พร้อมลิมิตที่ด้านล่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้ลิมิต |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบลิมิต |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - ลิมิตคณิตใหม่
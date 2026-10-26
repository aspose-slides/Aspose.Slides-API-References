---
title: MathLimitFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้าง IMathLimit
type: docs
url: /th/com.aspose.slides/mathlimitfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

อนุญาตให้สร้าง IMathLimit

--------------------

สำหรับความเข้ากันได้ของ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | สร้าง IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathLimit พร้อมขีดจำกัดที่ด้านล่าง |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

สร้าง IMathLimit

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้กับขีดจำกัด |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบขีดจำกัด |
| upperLimit | boolean | กำหนดตำแหน่งของขีดจำกัดที่ด้านบน |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - จำกัดคณิตศาสตร์ใหม่
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

สร้าง IMathLimit พร้อมขีดจำกัดที่ด้านล่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้กับขีดจำกัด |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบขีดจำกัด |

**ผลลัพธ์:**
[IMathLimit](../../com.aspose.slides/imathlimit) - จำกัดคณิตศาสตร์ใหม่
---
title: MathLimitFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้าง IMathLimit
type: docs
url: /th/com.aspose.slides/mathlimitfactory/
---
**การสืบทอด:**  
java.lang.Object  

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```  

อนุญาตให้สร้าง IMathLimit  

--------------------

สำหรับความเข้ากันได้กับ COM  

## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | สร้าง IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathLimit พร้อมลิมิตที่ด้านล่าง |

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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์พื้นฐานเพื่อใช้ลิมิต |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ลิมิต |
| upperLimit | boolean | ตั้งตำแหน่งของลิมิตให้ด้านบน |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - math limit ใหม่

### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

สร้าง IMathLimit พร้อมลิมิตที่ด้านล่าง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์พื้นฐานเพื่อใช้ลิมิต |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ลิมิต |

**คืนค่า:**
[IMathLimit](../../com.aspose.slides/imathlimit) - math limit ใหม่
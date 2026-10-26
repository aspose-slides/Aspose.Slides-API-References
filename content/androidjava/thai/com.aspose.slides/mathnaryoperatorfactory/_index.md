---
title: MathNaryOperatorFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้าง IMathNaryOperator
type: docs
url: /th/com.aspose.slides/mathnaryoperatorfactory/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

อนุญาตให้สร้าง IMathNaryOperator

--------------------

สำหรับความเข้ากันได้ของ COM
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | เครื่องหมายตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานที่ใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบน |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | เครื่องหมายตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานที่ใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | เครื่องหมายตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานที่ใช้กับตัวดำเนินการ |

**ผลลัพธ์:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
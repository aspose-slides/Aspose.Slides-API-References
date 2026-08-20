---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: อนุญาตให้สร้าง IMathNaryOperator
type: docs
url: /th/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

อนุญาตให้สร้าง IMathNaryOperator

--------------------

สำหรับความเข้ากันได้กับ COM
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้ตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบน |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้ตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

สร้าง IMathNaryOperator

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้ตัวดำเนินการ |

**คืนค่า:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - IMathNaryOperator ใหม่
---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: อนุญาตให้สร้าง IMathNaryOperator
type: docs
url: /th/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

อนุญาตให้สร้าง IMathNaryOperator

--------------------

เพื่อความเข้ากันได้กับ COM
## Methods

| Method | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | สร้าง IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

สร้าง IMathNaryOperator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบน |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

สร้าง IMathNaryOperator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

สร้าง IMathNaryOperator

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ของตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานสำหรับใช้กับตัวดำเนินการ |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
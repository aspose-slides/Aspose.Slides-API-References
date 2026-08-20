---
title: MathNaryOperatorFactory
second_title: Aspose.Slides สำหรับ Java API Reference
description: อนุญาตให้สร้าง IMathNaryOperator
type: docs
url: /th/com.aspose.slides/mathnaryoperatorfactory/
---
**Inheritance:**  
การสืบทอด:
java.lang.Object

**All Implemented Interfaces:**  
อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

Allows to create IMathNaryOperator  
อนุญาตให้สร้าง IMathNaryOperator

--------------------

For COM comparibility  
เพื่อความเข้ากันได้กับ COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## Methods

| Method | Description |
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

Creates IMathNaryOperator  
สร้าง IMathNaryOperator

**Parameters:**  
พารามิเตอร์:
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบบน |

**Returns:**  
คืนค่า:
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

Creates IMathNaryOperator  
สร้าง IMathNaryOperator

**Parameters:**  
พารามิเตอร์:
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้กับตัวดำเนินการ |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | ขอบล่าง |

**Returns:**  
คืนค่า:
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

Creates IMathNaryOperator  
สร้าง IMathNaryOperator

**Parameters:**  
พารามิเตอร์:
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | สัญลักษณ์ตัวดำเนินการ |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | อาร์กิวเมนต์ฐานเพื่อใช้กับตัวดำเนินการ |

**Returns:**  
คืนค่า:
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
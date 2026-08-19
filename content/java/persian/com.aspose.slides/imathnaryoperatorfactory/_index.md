---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: امکان ایجاد IMathNaryOperator را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

امکان ایجاد IMathNaryOperator را فراهم می‌کند

--------------------

برای سازگاری COM
## Methods

| Method | Description |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

یک IMathNaryOperator ایجاد می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

یک IMathNaryOperator ایجاد می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

یک IMathNaryOperator ایجاد می‌کند

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |

**Returns:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
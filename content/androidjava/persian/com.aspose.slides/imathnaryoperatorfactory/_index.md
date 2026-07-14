---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: Allows to create IMathNaryOperator
type: docs
url: /fa/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

اجازه می‌دهد یک IMathNaryOperator ایجاد کنید

--------------------

برای سازگاری COM
## روش‌ها

| روش | توضیح |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | Creates IMathNaryOperator |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نشانگر عملیات |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**بازگرداندن:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نشانگر عملیات |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |

**بازگرداندن:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | نشانگر عملیات |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |

**بازگرداندن:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
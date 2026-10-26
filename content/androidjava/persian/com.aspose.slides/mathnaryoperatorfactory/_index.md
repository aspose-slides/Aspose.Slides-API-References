---
title: MathNaryOperatorFactory
second_title: مرجع API Java برای Aspose.Slides برای Android
description: اجازه می‌دهد IMathNaryOperator ایجاد شود
type: docs
url: /fa/com.aspose.slides/mathnaryoperatorfactory/
---
**ارث‌برداری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

اجازه می‌دهد IMathNaryOperator ایجاد شود

--------------------

برای سازگاری COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | یک IMathNaryOperator ایجاد می‌کند |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد بالا |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | حد پایین |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


یک IMathNaryOperator ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
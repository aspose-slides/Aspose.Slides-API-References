---
title: MathNaryOperatorFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: اجازه می‌دهد IMathNaryOperator ساخته شود
type: docs
url: /fa/com.aspose.slides/mathnaryoperatorfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

اجازه می‌دهد IMathNaryOperator ساخته شود

--------------------

برای سازگاری COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator می‌سازد |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathNaryOperator می‌سازد |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | یک IMathNaryOperator می‌سازد |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


یک IMathNaryOperator می‌سازد

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


یک IMathNaryOperator می‌سازد

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


یک IMathNaryOperator می‌سازد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operatorSymbol | char | علامت عملگر |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال عملگر |

**بازگشت:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - یک IMathNaryOperator جدید
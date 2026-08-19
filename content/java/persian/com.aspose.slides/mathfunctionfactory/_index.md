---
title: MathFunctionFactory
second_title: Aspose.Slides برای Java مرجع API
description: اجازه می‌دهد یک تابع ریاضی ایجاد کند
type: docs
url: /fa/com.aspose.slides/mathfunctionfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

اجازه می‌دهد یک تابع ریاضی ایجاد کند

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


یک تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان نام تابع استفاده می‌شود |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


یک تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | java.lang.String | نام تابع |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
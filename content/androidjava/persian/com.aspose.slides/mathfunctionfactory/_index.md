---
title: MathFunctionFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: قابلیت ایجاد یک تابع ریاضی را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/mathfunctionfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

قابلیت ایجاد یک تابع ریاضی را فراهم می‌کند

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | تابع ریاضی ایجاد می‌کند |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | تابع ریاضی ایجاد می‌کند |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان نام تابع استفاده می‌شود |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگرداندن:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | java.lang.String | نام تابع |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگرداندن:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
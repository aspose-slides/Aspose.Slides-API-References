---
title: IMathFunctionFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: به شما امکان ایجاد یک تابع ریاضی را می‌دهد
type: docs
url: /fa/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

به شما امکان ایجاد یک تابع ریاضی را می‌دهد

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک تابع ریاضی ایجاد می‌کند |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | یک تابع ریاضی ایجاد می‌کند |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
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
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


یک تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | java.lang.String | نام تابع |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
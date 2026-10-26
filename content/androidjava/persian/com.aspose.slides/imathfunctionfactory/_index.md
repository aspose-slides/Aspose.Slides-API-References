---
title: IMathFunctionFactory
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: اجازه می‌دهد تا یک تابع ریاضی ایجاد شود
type: docs
url: /fa/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

اجازه می‌دهد تا یک تابع ریاضی ایجاد شود

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | تابع ریاضی ایجاد می‌کند |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | تابع ریاضی ایجاد می‌کند |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

تابع ریاضی ایجاد می‌کند

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

تابع ریاضی ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| funcName | java.lang.String | نام تابع |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که به عنوان آرگومان تابع استفاده می‌شود |

**بازگشت:**
[IMathFunction](../../com.aspose.slides/imathfunction) - تابع ریاضی جدید
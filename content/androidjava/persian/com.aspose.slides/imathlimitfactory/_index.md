---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /fa/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

اجازه می‌دهد IMathLimit ایجاد شود

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit را ایجاد می‌کند |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathLimit را با محدودیت در پایین ایجاد می‌کند |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit را ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |
| upperLimit | boolean | محل قرارگیری محدودیت را در بالا تنظیم می‌کند |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد ریاضی جدید
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


IMathLimit را با محدودیت در پایین ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - حد ریاضی جدید
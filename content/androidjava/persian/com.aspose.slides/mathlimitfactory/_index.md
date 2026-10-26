---
title: MathLimitFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: امکان ایجاد IMathLimit را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/mathlimitfactory/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

امکان ایجاد IMathLimit را فراهم می‌کند

--------------------

برای سازگاری COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | یک IMathLimit ایجاد می‌کند |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | یک IMathLimit با محدودیت در پایین ایجاد می‌کند |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


یک IMathLimit ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |
| upperLimit | boolean | مکان‌گذاری محدودیت را در بالا تنظیم می‌کند |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - محدودیت ریاضی جدید
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


یک IMathLimit با محدودیت در پایین ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |

**بازگشت:**
[IMathLimit](../../com.aspose.slides/imathlimit) - محدودیت ریاضی جدید
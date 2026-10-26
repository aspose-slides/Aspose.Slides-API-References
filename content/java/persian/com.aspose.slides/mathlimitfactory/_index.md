---
title: MathLimitFactory
second_title: مرجع API Aspose.Slides برای جاوا
description: اجازه می‌دهد IMathLimit ایجاد شود
type: docs
url: /fa/com.aspose.slides/mathlimitfactory/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

اجازه می‌دهد IMathLimit ایجاد شود

--------------------

برای سازگاری COM
## سازنده‌ها

| Constructor | Description |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## متدها

| Method | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | ایجاد IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ایجاد IMathLimit با محدودیت در پایین |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


ایجاد IMathLimit

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |
| upperLimit | boolean | محل قرارگیری محدودیت را در بالا تنظیم می‌کند |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - محدودیت ریاضی جدید
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


ایجاد IMathLimit با محدودیت در پایین

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | آرگومان پایه برای اعمال محدودیت |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | عنصر محدودیت |

**Returns:**
[IMathLimit](../../com.aspose.slides/imathlimit) - محدودیت ریاضی جدید
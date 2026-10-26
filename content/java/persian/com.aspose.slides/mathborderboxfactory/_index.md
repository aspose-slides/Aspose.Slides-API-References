---
title: MathBorderBoxFactory
second_title: Aspose.Slides برای مرجع API جاوا
description: اجازه می‌دهد یک جعبه مرزی ریاضی ایجاد شود
type: docs
url: /fa/com.aspose.slides/mathborderboxfactory/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)  
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

اجازه می‌دهد یک جعبهٔ مرزی ریاضی ایجاد شود

--------------------

برای سازگاری با COM
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | یک جعبهٔ مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | یک جعبهٔ مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


یک جعبهٔ مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال جعبه مرزی |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر جدید جعبه مرزی
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


یک جعبهٔ مرزی ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال جعبه مرزی |
| hideTop | boolean | پنهان کردن لبهٔ بالا |
| hideBottom | boolean | پنهان کردن لبهٔ پایین |
| hideLeft | boolean | پنهان کردن لبهٔ چپ |
| hideRight | boolean | پنهان کردن لبهٔ راست |
| strikethroughHorizontal | boolean | خط‌خورده افقی جعبه مرزی |
| strikethroughVertical | boolean | خط‌خورده عمودی جعبه مرزی |
| strikethroughBottomLeftToTopRight | boolean | خط‌خورده جعبه مرزی از پایین-چپ به بالا-راست |
| strikethroughTopLeftToBottomRight | boolean | خط‌خورده جعبه مرزی از بالا-چپ به پایین-راست |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر جدید جعبه مرزی
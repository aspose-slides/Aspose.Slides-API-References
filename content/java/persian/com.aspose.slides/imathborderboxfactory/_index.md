---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
url: /fa/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

امکان ایجاد یک جعبه حاشیه ریاضی را می‌دهد

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

یک جعبه حاشیه ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال جعبه حاشیه |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر جعبه حاشیه جدید
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

یک جعبه حاشیه ریاضی را با اعمال بر روی عنصر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال جعبه حاشیه |
| hideTop | boolean | پنهان کردن لبه بالایی |
| hideBottom | boolean | پنهان کردن لبه پایینی |
| hideLeft | boolean | پنهان کردن لبه چپ |
| hideRight | boolean | پنهان کردن لبه راست |
| strikethroughHorizontal | boolean | خط‌خورده افقی جعبه حاشیه |
| strikethroughVertical | boolean | خط‌خورده عمودی جعبه حاشیه |
| strikethroughBottomLeftToTopRight | boolean | خط‌خورده جعبه حاشیه از پایین-چپ به بالا-راست |
| strikethroughTopLeftToBottomRight | boolean | خط‌خورده جعبه حاشیه از بالا-چپ به پایین-راست |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر جعبه حاشیه جدید
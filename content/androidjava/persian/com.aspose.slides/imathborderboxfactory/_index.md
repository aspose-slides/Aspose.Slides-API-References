---
title: IMathBorderBoxFactory
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: اجازه می‌دهد تا یک جعبه حاشیه ریاضی ایجاد شود
type: docs
url: /fa/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

اجازه می‌دهد تا یک جعبه حاشیه ریاضی ایجاد شود

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | یک جعبه حاشیه ریاضی را با اعمال بر روی عنصر ایجاد می‌کند |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | یک جعبه حاشیه ریاضی را با اعمال بر روی عنصر ایجاد می‌کند |
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
| hideTop | boolean | پنهان کردن لبه بالا |
| hideBottom | boolean | پنهان کردن لبه پایین |
| hideLeft | boolean | پنهان کردن لبه چپ |
| hideRight | boolean | پنهان کردن لبه راست |
| strikethroughHorizontal | boolean | خط‌کش افقی جعبه حاشیه |
| strikethroughVertical | boolean | خط‌کش عمودی جعبه حاشیه |
| strikethroughBottomLeftToTopRight | boolean | خط‌کش جعبه حاشیه از پایین چپ به بالا راست |
| strikethroughTopLeftToBottomRight | boolean | خط‌کش جعبه حاشیه از بالا چپ به پایین راست |

**بازگشت:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - عنصر جعبه حاشیه جدید
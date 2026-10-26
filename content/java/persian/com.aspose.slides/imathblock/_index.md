---
title: IMathBlock
second_title: مرجع API Aspose.Slides برای جاوا
description: یک نمونه از متن ریاضی را که در داخل MathParagraph قرار دارد و در خط جداگانه خود شروع می‌شود، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathblock/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

مشخص می‌کند که یک نمونه از متن ریاضی که در داخل یک MathParagraph قرار دارد و در خط جداگانه خود شروع می‌شود. تمام نواحی ریاضی، شامل معادلات، عبارات، آرایه‌های معادلات یا عبارات، و فرمول‌ها توسط بلوک ریاضی نمایان می‌شوند.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | تمام عناصر فرزند را با کاراکتر جداکننده (بدون پرانتز) محدود می‌کند |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | عناصر فرزند این بلوک را با کاراکترهای مشخص‌شده مانند پرانتز یا سایر به عنوان قاب محصور می‌کند و با کاراکتر جداکننده محدود می‌سازد |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | یک بلوک ریاضی دیگر را با این بلوک ترکیب می‌کند |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتوای این [IMathBlock](../../com.aspose.slides/imathblock) را به صورت MathML ذخیره می‌کند |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

تمام عناصر فرزند را با کاراکتر جداکننده (بدون پرانتز) محدود می‌کند

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | کاراکتری که به عنوان جداکننده استفاده می‌شود |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - نمونه‌ای از عنصر IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

عناصر فرزند این بلوک را با کاراکترهای مشخص‌شده مانند پرانتز یا سایر به عنوان قاب محصور می‌کند و با کاراکتر جداکننده محدود می‌سازد

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر شروع (معمولاً پرانتز چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً پرانتز راست) |
| separatorCharacter | char | کاراکتر جداکننده |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص به عنوان قاب و جداکننده است
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

یک بلوک ریاضی دیگر را با این بلوک ترکیب می‌کند

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک الحاقی |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - این بلوک ریاضی پس از الحاق
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

محتوای این [IMathBlock](../../com.aspose.slides/imathblock) را به صورت MathML ذخیره می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف
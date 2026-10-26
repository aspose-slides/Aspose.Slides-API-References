---
title: IMathBlock
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خود شروع می‌شود، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/imathblock/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خود شروع می‌شود، مشخص می‌کند. تمام نواحی ریاضی، از جمله معادلات، عبارات، آرایه‌های معادلات یا عبارات، و فرمول‌ها توسط بلاک ریاضی نمایش داده می‌شوند.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Methods

| Method | Description |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | تمام عناصر فرزند را با کاراکتر جداکننده (بدون کروشه‌ها) محدود می‌کند |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به عنوان قاب قرار می‌دهد و با کاراکتر جداکننده محدود می‌کند |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | یک بلاک ریاضی دیگر را به این بلاک پیوست می‌کند |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتوای این [IMathBlock](../../com.aspose.slides/imathblock) را به صورت MathML ذخیره می‌کند |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


تمام عناصر فرزند را با کاراکتر جداکننده (بدون کروشه‌ها) محدود می‌کند

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | کاراکتری که به عنوان جداکننده استفاده می‌شود |

**بازگرداندن:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - یک نمونه از عنصر IMathDelimiter

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا سایر کاراکترها به عنوان قاب قرار می‌دهد و با کاراکتر جداکننده محدود می‌کند

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر آغاز (معمولاً کروشهٔ چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً کروشهٔ راست) |
| separatorCharacter | char | کاراکتر جداکننده |

**بازگرداندن:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص‌شده به عنوان قاب و جداکننده است

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


یک بلاک ریاضی دیگر را به این بلاک پیوست می‌کند

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
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | بلاک پیوسته‌شونده |

**بازگرداندن:**
[IMathBlock](../../com.aspose.slides/imathblock) - این بلاک ریاضی پس از پیوست شدن

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


محتوای این [IMathBlock](../../com.aspose.slides/imathblock) را به صورت MathML ذخیره می‌کند

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
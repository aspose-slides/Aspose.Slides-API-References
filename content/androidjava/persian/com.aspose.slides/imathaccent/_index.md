---
title: IMathAccent
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملکرد لهجه را مشخص می‌کند که شامل یک پایه و یک علامت ترکیبی است. مثال ud835udc4eu0301
type: docs
url: /fa/com.aspose.slides/imathaccent/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

عملکرد لهجه را مشخص می‌کند که شامل یک پایه و یک علامت ترکیبی است. مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومانی که لهجه بر روی آن اعمال شده است |
| [getCharacter()](#getCharacter--) | کاراکتر لهجه؛ مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: ترکیبی کرسوفت (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر لهجه؛ مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: ترکیبی کرسوفت (U+0302) |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

آرگومانی که لهجه بر روی آن اعمال شده است

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**باز می‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

کاراکتر لهجه؛ مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: ترکیبی کرسوفت (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**باز می‌گرداند:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

کاراکتر لهجه؛ مقدار باید در بازهٔ (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد. مقدار پیش‌فرض: ترکیبی کرسوفت (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |
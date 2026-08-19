---
title: IMathAccent
second_title: مرجع API Aspose.Slides برای جاوا
description: عملکرد لهجه را مشخص می‌کند که شامل یک پایه و یک علامت ترکیبی است. مثال ud835udc4eu0301
type: docs
url: /fa/com.aspose.slides/imathaccent/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

مشخص می‌کند تابع لهجه، شامل پایه و علامت ترکیبی است. مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## روش‌ها

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | آرگومانی که لهجه روی آن اعمال شد |
| [getCharacter()](#getCharacter--) | کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


آرگومانی که لهجه روی آن اعمال شد

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**بازگشت:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


کاراکتر لهجه مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
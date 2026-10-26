---
title: MathAccent
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: عملکرد Accent را که شامل یک پایه و یک علامت دیاکریتیک ترکیبی است مشخص می‌کند. مثال ud835udc4eu0301
type: docs
url: /fa/com.aspose.slides/mathaccent/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

توابع Accent را مشخص می‌کند که شامل یک پایه و یک علامت دیاکری‌تیک ترکیبی است مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | یک MathAccent ایجاد می‌کند که به عنصر ریاضی مشخصی اعمال می‌شود با مقدار پیش‌فرض کاراکتر Accent |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | یک MathAccent ایجاد می‌کند که به عنصر ریاضی مشخصی اعمال می‌شود |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومانی که Accent به آن اعمال شده است |
| [getCharacter()](#getCharacter--) | کاراکتر Accent مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر Accent مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

یک MathAccent ایجاد می‌کند که به عنصر ریاضی مشخصی اعمال می‌شود با مقدار پیش‌فرض کاراکتر Accent

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال Accent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

یک MathAccent ایجاد می‌کند که به عنصر ریاضی مشخصی اعمال می‌شود

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای اعمال Accent |
| accentCharacter | char | کاراکتر Accent |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

آرگومانی که Accent به آن اعمال شده است

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
public final char getCharacter()
```

کاراکتر Accent مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302)

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
public final void setCharacter(char value)
```

کاراکتر Accent مقدار باید در بازه (U+0300\\u2013U+036F) یا (U+20D0\\u2013U+20EF) باشد مقدار پیش‌فرض: ترکیبی Circumflex Accent (U+0302)

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

ویژگی‌های کاراکتر کنترل

**بازگشت:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
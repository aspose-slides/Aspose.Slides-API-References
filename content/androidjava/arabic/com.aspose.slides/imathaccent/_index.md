---
title: IMathAccent
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد وظيفة التنوين التي تتكون من أساس وعلامة توضع فوق الحرف. مثال ud835udc4eu0301
type: docs
url: /ar/com.aspose.slides/imathaccent/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

يحدد وظيفة التنوين، التي تتكون من أساس وعلامة توضع فوق الحرف. مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | المعامل الذي تم تطبيق التنوين عليه |
| [getCharacter()](#getCharacter--) | حرف التنوين. يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF). القيمة الافتراضية: علامة الجمع المرفوعة (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | حرف التنوين. يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF). القيمة الافتراضية: علامة الجمع المرفوعة (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


المعامل الذي تم تطبيق التنوين عليه

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
>  ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


حرف التنوين. يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF). القيمة الافتراضية: علامة الجمع المرفوعة (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```

**الإرجاع:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


حرف التنوين. يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو (U+20D0\\u2013U+20EF). القيمة الافتراضية: علامة الجمع المرفوعة (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char |  |
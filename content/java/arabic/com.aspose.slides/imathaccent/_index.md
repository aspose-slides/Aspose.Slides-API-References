---
title: IMathAccent
second_title: مرجع API لـ Aspose.Slides for Java
description: يحدد دالة اللكنة المتكوّنة من قاعدة وعلامة تشكيل مركبة مثال ud835udc4eu0301
type: docs
url: /ar/com.aspose.slides/imathaccent/
---
**جميع الواجهات المُطبَّقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

يحدد دالة اللكنة، المكونة من قاعدة وعلامة تشكيل مركبة مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الحجة التي تم تطبيق اللكنة عليها |
| [getCharacter()](#getCharacter--) | حرف اللكنة يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو (U+20D0\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | حرف اللكنة يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو (U+20D0\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

الحجة التي تم تطبيق اللكنة عليها

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

حرف اللكنة يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو (U+20D0\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**القيمة المرجعة:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

حرف اللكنة يجب أن تكون القيمة ضمن النطاق (U+0300\u2013U+036F) أو (U+20D0\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**المعلمات:**
| معلمة | النوع | الوصف |
| --- | --- | --- |
| value | char |  |
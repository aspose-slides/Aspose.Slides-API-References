---
title: MathAccent
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد وظيفة اللكنة المكوّنة من أساس وعلامة توحيدية مثال ud835udc4eu0301
type: docs
url: /ar/com.aspose.slides/mathaccent/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

يحدد وظيفة اللكنة، المكوّنة من أساس وعلامة توحيدية مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
>  ```
## المنشئات

| Constructor | Description |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | إنشاء لكنة رياضية تُطبق على عنصر رياضي محدد باستخدام قيمة حرف اللكنة الافتراضية |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | إنشاء لكنة رياضية تُطبق على عنصر رياضي محدد |
## الطرق

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الذي تم تطبيق اللكنة عليه |
| [getCharacter()](#getCharacter--) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Get children elements |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


إنشاء لكنة رياضية تُطبق على عنصر رياضي محدد باستخدام قيمة حرف اللكنة الافتراضية

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق اللكنة عليه |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


إنشاء لكنة رياضية تُطبق على عنصر رياضي محدد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق اللكنة عليه |
| accentCharacter | char | حرف اللكنة |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


الوسيط الذي تم تطبيق اللكنة عليه

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
public final char getCharacter()
```


Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```

**القيمة المرجعة:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Accent Character The value should be within the range of (U+0300\\u2013U+036F) or(U+20D0\\u2013U+20EF) Default value: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
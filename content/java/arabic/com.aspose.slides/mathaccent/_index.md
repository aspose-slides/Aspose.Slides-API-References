---
title: MathAccent
second_title: Aspose.Slides لمرجع API لجافا
description: يحدد وظيفة التشديد المكوّنة من قاعدة وعلامة تشكيل مركبة مثال ud835udc4eu0301
type: docs
url: /ar/com.aspose.slides/mathaccent/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

يحدد وظيفة التشديد، المكوّن من قاعدة وعلامة تشكيل مركبة مثال: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد مع قيمة حرف التشديد الافتراضية |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الوسيط الذي تم تطبيق التشديد عليه |
| [getCharacter()](#getCharacter--) | حرف التشديد يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو(U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | حرف التشديد يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو(U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد مع قيمة حرف التشديد الافتراضية

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق التشديد |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر رياضي لتطبيق التشديد |
| accentCharacter | char | حرف التشديد |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


الوسيط الذي تم تطبيق التشديد عليه

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


حرف التشديد يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو(U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)

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
public final void setCharacter(char value)
```


حرف التشديد يجب أن تكون القيمة ضمن النطاق (U+0300\\u2013U+036F) أو(U+20D0\\u2013U+20EF) القيمة الافتراضية: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**المعاملات:**
| معامل | النوع | الوصف |
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
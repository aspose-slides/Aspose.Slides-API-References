---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يحدد كائن Sub-Superscript الذي يتكون من قاعدة ومؤشر سفلي ومؤشر علوي موضعين إلى يمين القاعدة.
type: docs
url: /ar/com.aspose.slides/imathrightsubsuperscriptelement/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

يحدد كائن Sub-Superscript، الذي يتكون من قاعدة ومؤشر سفلي ومؤشر علوي موضعين إلى يمين القاعدة.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | معامل المؤشر السفلي |
| [getSuperscript()](#getSuperscript--) | معامل المؤشر العلوي |
| [getAlignScripts()](#getAlignScripts--) | يحدد محاذاة المؤشر السفلي/العلوي. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | يحدد محاذاة المؤشر السفلي/العلوي. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

معامل القاعدة

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

معامل المؤشر السفلي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

معامل المؤشر العلوي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

يحدد محاذاة المؤشر السفلي/العلوي. عندما تكون true، يتم محاذاة المؤشر السفلي والعلوي أفقياً بالنسبة لبعضهما البعض. عندما تكون false، يتم تعديل المسافة وفقاً لشكل القاعدة. القيمة الافتراضية هي false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**القيمة المرجعة:** boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

يحدد محاذاة المؤشر السفلي/العلوي. عندما تكون true، يتم محاذاة المؤشر السفلي والعلوي أفقياً بالنسبة لبعضهما البعض. عندما تكون false، يتم تعديل المسافة وفقاً لشكل القاعدة. القيمة الافتراضية هي false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
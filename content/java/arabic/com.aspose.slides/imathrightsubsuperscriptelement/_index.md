---
title: IMathRightSubSuperscriptElement
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن الـ Sub-Superscript الذي يتكون من قاعدة ونص سفلي ونص علوي موضوعة إلى يمين القاعدة.
type: docs
url: /ar/com.aspose.slides/imathrightsubsuperscriptelement/
---
**جميع الواجهات المُطبقة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

يحدد كائن الـ Sub-Superscript، الذي يتكون من قاعدة ونص سفلي ونص علوي موضعة إلى يمين القاعدة.

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
> ```
## الطرق

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | معامل القاعدة |
| [getSubscript()](#getSubscript--) | معامل النص السفلي |
| [getSuperscript()](#getSuperscript--) | معامل النص العلوي |
| [getAlignScripts()](#getAlignScripts--) | يحدد محاذاة النص السفلي/العُلوي. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | يحدد محاذاة النص السفلي/العُلوي. |
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


معامل النص السفلي

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


معامل النص العلوي

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


يحدد محاذاة النص السفلي/العُلوي. عندما تكون true، يتم محاذاة النص السفلي والعُلوي أفقيًا معًا. عندما تكون false، يتم ضبطهما على شكل القاعدة. القيمة الافتراضية هي false.

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

**القيمة المرجعة:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


يحدد محاذاة النص السفلي/العُلوي. عندما تكون true، يتم محاذاة النص السفلي والعُلوي أفقيًا معًا. عندما تكون false، يتم ضبطهما على شكل القاعدة. القيمة الافتراضية هي false.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
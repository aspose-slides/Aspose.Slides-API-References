---
title: MathRightSubSuperscriptElement
second_title: مرجع API Aspose.Slides للغة جافا
description: يحدد كائن السوب-سوبسْكريبت الذي يتكوّن من أساس وسوبسكريبت وسوبرسكريبت موضعين إلى يمين الأساس.
type: docs
url: /ar/com.aspose.slides/mathrightsubsuperscriptelement/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

يحدد كائن السوب-سوبسْكريبت، الذي يتكوَّن من أساس وسوبسكريبت وسوبرسكريبت موضعين إلى يمين الأساس.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بتهيئة نسخة جديدة من الفئة MathRightSubSuperscriptElement. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubscript()](#getSubscript--) | معامل السوبسكريبت |
| [getSuperscript()](#getSuperscript--) | معامل السوبرسكريبت |
| [getAlignScripts()](#getAlignScripts--) | يحدد محاذاة السوبسكريبت/السوبرسكريبت. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | يحدد محاذاة السوبسكريبت/السوبرسكريبت. |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


يقوم بتهيئة نسخة جديدة من الفئة MathRightSubSuperscriptElement.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


معامل السوبسكريبت

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
public final IMathElement getSuperscript()
```


معامل السوبرسكريبت

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
public final boolean getAlignScripts()
```


يحدد محاذاة السوبسكريبت/السوبرسكريبت. عندما تكون true، يتم محاذاة السوبسكريبت والسوبرسكريبت أفقياً معًا. عندما تكون false، يُربطان بشكل يتناسب مع شكل الأساس. القيمة الافتراضية هي false.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
>  ```


**القيمة المرجعة:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


يحدد محاذاة السوبسكريبت/السوبرسكريبت. عندما تكون true، يتم محاذاة السوبسكريبت والسوبرسكريبت أفقياً معًا. عندما تكون false، يُربطان بشكل يتناسب مع شكل الأساس. القيمة الافتراضية هي false.

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
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


جلب عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
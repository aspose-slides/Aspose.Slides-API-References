---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كائن Sub-Superscript الذي يتكون من قاعدة وموضع سفلي وموضع علوي موضوع إلى يمين القاعدة.
type: docs
url: /ar/com.aspose.slides/mathrightsubsuperscriptelement/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**جميع الواجهات المطبقة:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

يحدد كائن Sub-Superscript، والذي يتكون من قاعدة وموضع أسفل النص وموضع فوق النص يتم وضعهما إلى يمين القاعدة.

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
> ```
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يُنشئ مثالًا جديدًا من الفئة MathRightSubSuperscriptElement. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubscript()](#getSubscript--) | متغير النص السفلي |
| [getSuperscript()](#getSuperscript--) | متغير النص الأعلى |
| [getAlignScripts()](#getAlignScripts--) | يحدد محاذاة النص السفلي/الأعلى. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | يحدد محاذاة النص السفلي/الأعلى. |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

يُنشئ مثالًا جديدًا من الفئة MathRightSubSuperscriptElement.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

متغير النص السفلي

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

متغير النص الأعلى

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

يحدد محاذاة النص السفلي/الأعلى. عندما تكون true، يتم محاذاة النص السفلي والنص الأعلى أفقيًا معًا. عندما تكون false، يتم تعديلهما لتتناسب مع شكل القاعدة. القيمة الافتراضية هي false.

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
public final void setAlignScripts(boolean value)
```

يحدد محاذاة النص السفلي/الأعلى. عندما تكون true، يتم محاذاة النص السفلي والنص الأعلى أفقيًا معًا. عندما تكون false، يتم تعديلهما لتتناسب مع شكل القاعدة. القيمة الافتراضية هي false.

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
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
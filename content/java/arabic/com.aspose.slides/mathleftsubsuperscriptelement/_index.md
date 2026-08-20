---
title: MathLeftSubSuperscriptElement
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن Sub-Superscript الذي يتكون من قاعدة وتحتية وعليا موضوعة إلى يسار القاعدة.
type: docs
url: /ar/com.aspose.slides/mathleftsubsuperscriptelement/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
```
public final class MathLeftSubSuperscriptElement extends BaseScript implements IMathLeftSubSuperscriptElement
```

يحدد كائن Sub-Superscript، الذي يتكون من قاعدة ومؤشر فرعي ومؤشر علوي موضعهما إلى يسار القاعدة.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بإنشاء نسخة جديدة من الصنف MathLeftSubSuperscriptElement. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubscript()](#getSubscript--) | المؤشر الفرعي |
| [getSuperscript()](#getSuperscript--) | المؤشر العلوي |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
### MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathLeftSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLeftSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```

يقوم بإنشاء نسخة جديدة من الصنف MathLeftSubSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

المؤشر الفرعي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = leftSubSuperscript.getSubscript();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

المؤشر العلوي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathLeftSubSuperscriptElement leftSubSuperscript = new MathLeftSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = leftSubSuperscript.getSuperscript();
> ```

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

جلب عناصر الأطفال

**الإرجاع:**
com.aspose.slides.IMathElement[]
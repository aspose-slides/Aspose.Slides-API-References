---
title: MathSuperscriptElement
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد كائن النص العلوي الذي يتكون من قاعدة ونص علوي بحجم مصغر موضعًا فوق اليمين
type: docs
url: /ar/com.aspose.slides/mathsuperscriptelement/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

يحدد كائن النص العلوي، الذي يتكون من قاعدة ونص علوي بحجم مصغر موضعًا فوق اليمين

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يُنشئ مثيلًا جديدًا من فئة MathSuperscriptElement. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | النص العلوي |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```

يُنشئ مثيلًا جديدًا من فئة MathSuperscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

النص العلوي

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
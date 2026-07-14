---
title: MathLimit
second_title: Aspose.Slides لـ Android عبر مرجع API Java
description: يحدد كائن Limit المكوّن من النص على الخط الأساسي والنص المصغر حجماً مباشرةً فوقه أو أسفله.
type: docs
url: /ar/com.aspose.slides/mathlimit/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathLimit](../../com.aspose.slides/imathlimit), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathLimit extends MathElementBase implements IMathLimit, IHasControlCharacterProperties
```

يحدد كائن Limit، يتكون من نص على الخط الأساسي ونص أصغر حجماً مباشرةً فوقه أو أسفله.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | يقوم بإنشاء نسخة جديدة من الفئة MathLimit. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بإنشاء نسخة جديدة من الفئة MathLimit مع الحد الأدنى |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | حجة القاعدة |
| [getLimit()](#getLimit--) | حجة الحد |
| [getUpperLimit()](#getUpperLimit--) | يحدد الحد الأعلى أو الأدنى |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | يحدد الحد الأعلى أو الأدنى |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


يقوم بإنشاء نسخة جديدة من الفئة MathLimit.

--------------------

> ```
> مثال:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"), false);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | boolean |  |

### MathLimit(IMathElement baseArg, IMathElement limit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLimit(IMathElement baseArg, IMathElement limit)
```


يقوم بإنشاء نسخة جديدة من الفئة MathLimit مع الحد الأدنى

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


حجة القاعدة

--------------------

> ```
> مثال:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public final IMathElement getLimit()
```


حجة الحد

--------------------

> ```
> مثال:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


يحدد الحد الأعلى أو الأدنى

--------------------

> ```
> مثال:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**القيمة المرجعة:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


يحدد الحد الأعلى أو الأدنى

--------------------

> ```
> مثال:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
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
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
---
title: MathSubscriptElement
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد كائن الفهرس السفلي الذي يتكون من قاعدة وفهرس فرعي بحجم مصغر موضع أسفل اليمين.
type: docs
url: /ar/com.aspose.slides/mathsubscriptelement/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

يحدد كائن الفهرس السفلي، الذي يتكون من قاعدة وفهرس فرعي بحجم مصغر موضع أسفل اليمين.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بتهيئة مثيل جديد من الفئة MathSubscriptElement. |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getSubscript()](#getSubscript--) | فهرس |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```


يقوم بتهيئة مثيل جديد من الفئة MathSubscriptElement.

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


فهرس

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


جلب عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
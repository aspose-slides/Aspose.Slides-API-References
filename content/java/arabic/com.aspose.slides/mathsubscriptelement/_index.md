---
title: MathSubscriptElement
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للـ Java
description: يحدد كائن الإشارة السفلية الذي يتكون من قاعدة وإشارة سفلية بحجم أصغر موضوعة أسفل وإلى اليمين.
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

يحدد كائن الإشارة السفلية، الذي يتكون من قاعدة وإشارة سفلية بحجم أصغر موضوعة أسفل وإلى اليمين.

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## المنشئات

| المنشىء | الوصف |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بإنشاء مثال جديد من الفئة MathSubscriptElement. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSubscript()](#getSubscript--) | الإشارة السفلية |
| [getChildren()](#getChildren--) | إحضار عناصر الأطفال |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

يقوم بإنشاء مثال جديد من الفئة MathSubscriptElement.

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

الإشارة السفلية

--------------------

> ```
> مثال:
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

إحضار عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
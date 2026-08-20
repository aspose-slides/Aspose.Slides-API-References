---
title: MathFraction
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: يحدد كائن الكسر المكوّن من البسط والمقام مفصولين بشريط كسر.
type: docs
url: /ar/com.aspose.slides/mathfraction/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

يحدد كائن الكسر، المكوّن من البسط والمقام مفصولين بشريط الكسر. يمكن أن يكون شريط الكسر أفقيًا أو مائلًا، اعتمادًا على خصائص الكسر. يُستخدم كائن الكسر أيضًا لتمثيل دالة التكدس، التي تضع عنصرًا فوق آخر دون شريط كسر.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | يقوم بتهيئة MathFraction باستخدام البسط والمقام والنوع المحددين |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بتهيئة MathFraction من النوع 'Bar' باستخدام البسط والمقام المحددين |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFractionType()](#getFractionType--) | نوع الكسر الافتراضي: Bar |
| [setFractionType(int value)](#setFractionType-int-) | نوع الكسر الافتراضي: Bar |
| [getNumerator()](#getNumerator--) | البسط |
| [getDenominator()](#getDenominator--) | المقام |
| [getChildren()](#getChildren--) | الحصول على العناصر الفرعية |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


يقوم بتهيئة MathFraction باستخدام البسط والمقام والنوع المحددين

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |
| fractionType | int | نوع الكسر |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


يقوم بتهيئة MathFraction من النوع 'Bar' باستخدام البسط والمقام المحددين

--------------------

> ```
> مثال:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | البسط |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | المقام |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


نوع الكسر الافتراضي: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**القيمة المرجعة:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


نوع الكسر الافتراضي: Bar

--------------------

> ```
> مثال:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


البسط

--------------------

> ```
> مثال:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


المقام

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


الحصول على العناصر الفرعية

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خصائص حرف التحكم

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
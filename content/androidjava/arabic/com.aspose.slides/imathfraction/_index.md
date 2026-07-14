---
title: IMathFraction
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يقوم بتحديد كائن الكسر المكوّن من البسط والمقام مفصولين بشريط الكسر.
type: docs
url: /ar/com.aspose.slides/imathfraction/
---
**جميع الواجهات المعتمدة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

يحدد كائن الكسر، المكوّن من البسط والمقام مفصولين بشريط الكسر. يمكن أن يكون شريط الكسر أفقيًا أو مائلًا، اعتمادًا على خصائص الكسر. يُستخدم كائن الكسر أيضًا لتمثيل وظيفة التكدس، التي تضع عنصرًا فوق آخر، دون شريط كسر.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFractionType()](#getFractionType--) | نوع الكسر الافتراضي: Bar |
| [setFractionType(int value)](#setFractionType-int-) | نوع الكسر الافتراضي: Bar |
| [getNumerator()](#getNumerator--) | البسط |
| [getDenominator()](#getDenominator--) | المقام |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
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
public abstract void setFractionType(int value)
```


نوع الكسر الافتراضي: Bar

--------------------

> ```
> Example:
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
public abstract IMathElement getNumerator()
```


البسط

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
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
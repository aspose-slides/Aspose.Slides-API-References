---
title: IMathFraction
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يحدد كائن الكسر المكوّن من البسط والمقام مفصولين بشريط الكسر.
type: docs
url: /ar/com.aspose.slides/imathfraction/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

يحدد كائن الكسر، المكوّن من البسط والمقام مفصولين بشريط الكسر. يمكن أن يكون شريط الكسر أفقيًا أو قطريًا، اعتمادًا على خصائص الكسر. يُستخدم كائن الكسر أيضًا لتمثيل دالة التكديس، التي تضع عنصرًا فوق آخر دون شريط كسر.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type Default: Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Fraction type Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
```

**الإرجاع:**  
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

Fraction type Default: Bar

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

Numerator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**الإرجاع:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```

Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**الإرجاع:**  
[IMathElement](../../com.aspose.slides/imathelement)
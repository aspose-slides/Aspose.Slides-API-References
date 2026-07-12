---
title: IMathFraction
second_title: Java API Referansı ile Android için Aspose.Slides
description: Bir kesir çubuğu ile ayrılmış pay ve paydadan oluşan kesir nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathfraction/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Bir pay ve payda bir kesir çubuğu ile ayrılmış olan kesir nesnesini belirtir. Kesir çubuğu, kesir özelliklerine bağlı olarak yatay veya diyagonal olabilir. Kesir nesnesi ayrıca, bir elemanı diğerinin üzerine yerleştiren ve kesir çubuğu olmayan istif fonksiyonunu temsil etmek için de kullanılır.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFractionType()](#getFractionType--) | Fraction type Varsayılan: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Fraction type Varsayılan: Bar |
| [getNumerator()](#getNumerator--) | Pay |
| [getDenominator()](#getDenominator--) | Payda |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

Fraction type Varsayılan: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```


**Döndürür:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

Fraction type Varsayılan: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```

Pay

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```

Payda

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
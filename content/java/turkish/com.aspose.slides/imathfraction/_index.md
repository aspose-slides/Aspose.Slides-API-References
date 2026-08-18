---
title: IMathFraction
second_title: Aspose.Slides Java API Referansı
description: Bir pay ve paydadan oluşan ve bir kesir çubuğu ile ayrılmış kesir nesnesini belirtir.
type: docs
url: /tr/com.aspose.slides/imathfraction/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Bir kesir çubuğu ile ayrılmış pay ve paydadan oluşan kesir nesnesini belirtir. Kesir çubuğu, kesir özelliklerine bağlı olarak yatay ya da diyagonal olabilir. Kesir nesnesi ayrıca, bir elemanı diğerinin üzerine yerleştiren ve kesir çubuğu olmayan yığın işlevini temsil etmek için de kullanılır.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Yöntemler

| Method | Description |
| --- | --- |
| [getFractionType()](#getFractionType--) | Kesir türü Varsayılan: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Kesir türü Varsayılan: Bar |
| [getNumerator()](#getNumerator--) | Pay |
| [getDenominator()](#getDenominator--) | Payda |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Kesir türü Varsayılan: Bar

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


Kesir türü Varsayılan: Bar

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
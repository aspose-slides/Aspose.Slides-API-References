---
title: IMathFraction
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan objek pecahan yang terdiri dari pembilang dan penyebut yang dipisahkan oleh batang pecahan.
type: docs
url: /id/com.aspose.slides/imathfraction/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Menentukan objek pecahan, yang terdiri dari pembilang dan penyebut yang dipisahkan oleh batang pecahan. Batang pecahan dapat berupa horizontal atau diagonal, tergantung pada properti pecahan. Objek pecahan juga digunakan untuk merepresentasikan fungsi stack, yang menempatkan satu elemen di atas elemen lain, tanpa batang pecahan.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```
## Metode

| Metode | Deskripsi |
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

**Mengembalikan:**
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
```

**Parameter:**
| Parameter | Tipe | Deskripsi |
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

**Mengembalikan:**
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

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
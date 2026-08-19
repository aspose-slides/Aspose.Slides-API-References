---
title: IMathFraction
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan objek pecahan yang terdiri dari pembilang dan penyebut yang dipisahkan oleh garis pecahan.
type: docs
url: /id/com.aspose.slides/imathfraction/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Menentukan objek pecahan, yang terdiri dari pembilang dan penyebut yang dipisahkan oleh garis pecahan. Garis pecahan dapat berupa horizontal atau diagonal, tergantung pada properti pecahan. Objek pecahan juga digunakan untuk merepresentasikan fungsi tumpukan, yang menempatkan satu elemen di atas elemen lain, tanpa garis pecahan.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipe pecahan Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipe pecahan Default: Bar |
| [getNumerator()](#getNumerator--) | Pembilang |
| [getDenominator()](#getDenominator--) | Penyebut |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Tipe pecahan Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Mengembalikan:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Tipe pecahan Default: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Pembilang

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


Penyebut

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
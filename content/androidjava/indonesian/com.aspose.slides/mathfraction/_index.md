---
title: MathFraction
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan objek pecahan yang terdiri dari pembilang dan penyebut yang dipisahkan oleh batang pecahan.
type: docs
url: /id/com.aspose.slides/mathfraction/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Menentukan objek pecahan, yang terdiri dari pembilang dan penyebut yang dipisahkan oleh batang pecahan. Batang pecahan dapat berupa horizontal atau diagonal, tergantung pada properti pecahan. Objek pecahan juga digunakan untuk merepresentasikan fungsi tumpukan, yang menempatkan satu elemen di atas elemen lain, tanpa batang pecahan.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Menginisialisasi MathFraction dengan pembilang, penyebut, dan tipe yang ditentukan |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Menginisialisasi MathFraction dengan tipe 'Bar' dengan pembilang dan penyebut yang ditentukan |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipe pecahan Default: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipe pecahan Default: Bar |
| [getNumerator()](#getNumerator--) | Pembilang |
| [getDenominator()](#getDenominator--) | Penyebut |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Menginisialisasi MathFraction dengan pembilang, penyebut, dan tipe yang ditentukan

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pembilang |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |
| fractionType | int | Tipe pecahan |
### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Menginisialisasi MathFraction dengan tipe 'Bar' dengan pembilang dan penyebut yang ditentukan

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Pembilang |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Penyebut |
### getFractionType() {#getFractionType--}
```
public final int getFractionType()
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
public final void setFractionType(int value)
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
public final IMathElement getNumerator()
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
public final IMathElement getDenominator()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
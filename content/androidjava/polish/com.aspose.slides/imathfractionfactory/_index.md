---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia tworzenie ułamka matematycznego
type: docs
url: /pl/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Umożliwia tworzenie ułamka matematycznego

--------------------

Dla kompatybilności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Tworzy ułamek matematyczny |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy ułamek matematyczny |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Tworzy ułamek matematyczny

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Licznik |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |
| fractionType | int | Typ ułamka |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nowy ułamek matematyczny [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Tworzy ułamek matematyczny

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Licznik |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Mianownik |

**Zwraca:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Nowy ułamek matematyczny [IMathFraction](../../com.aspose.slides/imathfraction)
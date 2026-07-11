---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Διευκολύνει τη δημιουργία ενός μαθηματικού κλάσματος
type: docs
url: /el/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Διευκολύνει τη δημιουργία ενός μαθηματικού κλάσματος

--------------------

Για συμβατότητα με COM
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Δημιουργεί ένα μαθηματικό κλάσμα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Αριθμητής |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρανομαστής |
| fractionType | int | Τύπος κλάσματος |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Νέο μαθηματικό κλάσμα [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Δημιουργεί ένα μαθηματικό κλάσμα

**Παράμετροι:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Αριθμητής |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Παρανομαστής |

**Επιστρέφει:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Νέο μαθηματικό κλάσμα [IMathFraction](../../com.aspose.slides/imathfraction)
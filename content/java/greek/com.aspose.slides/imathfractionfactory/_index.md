---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Επιτρέπει τη δημιουργία ενός μαθηματικού κλάσματος
type: docs
url: /el/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Επιτρέπει τη δημιουργία ενός μαθηματικού κλάσματος

--------------------

Για συμβατότητα με COM
## Methods

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Creates a math fraction

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - New math fraction [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Creates a math fraction

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

**Returns:**
[IMathFraction](../../com.aspose.slides/imathfraction) - New math fraction [IMathFraction](../../com.aspose.slides/imathfraction)
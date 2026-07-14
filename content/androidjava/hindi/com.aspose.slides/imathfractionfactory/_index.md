---
title: IMathFractionFactory
second_title: Aspose.Slides Android के लिए Java API Reference के माध्यम से
description: गणितीय भिन्न बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

गणितीय भिन्न बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | गणितीय भिन्न बनाता है |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | गणितीय भिन्न बनाता है |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

गणितीय भिन्न बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | अंश |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |
| fractionType | int | भिन्न प्रकार |

**वापसी:**
[IMathFraction](../../com.aspose.slides/imathfraction) - New math fraction [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

गणितीय भिन्न बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | अंश |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | हर |

**वापसी:**
[IMathFraction](../../com.aspose.slides/imathfraction) - New math fraction [IMathFraction](../../com.aspose.slides/imathfraction)
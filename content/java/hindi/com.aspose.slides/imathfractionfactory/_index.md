---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math fraction
type: docs
url: /hi/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

गणितीय भिन्न बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| मेथड | विवरण |
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

**रिटर्न:**
[IMathFraction](../../com.aspose.slides/imathfraction) - नया गणितीय भिन्न [IMathFraction](../../com.aspose.slides/imathfraction)
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

**रिटर्न:**
[IMathFraction](../../com.aspose.slides/imathfraction) - नया गणितीय भिन्न [IMathFraction](../../com.aspose.slides/imathfraction)
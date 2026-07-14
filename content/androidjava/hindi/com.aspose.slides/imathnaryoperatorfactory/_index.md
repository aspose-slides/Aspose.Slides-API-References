---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: IMathNaryOperator बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधाएँ

| मेथड | विवरण |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए आधार तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए आधार तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए आधार तर्क |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
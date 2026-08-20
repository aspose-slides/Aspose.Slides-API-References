---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Java API Reference
description: IMathNaryOperator बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## मेथड्स

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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**वापसी:**
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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |

**वापसी:**
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
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |

**वापसी:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
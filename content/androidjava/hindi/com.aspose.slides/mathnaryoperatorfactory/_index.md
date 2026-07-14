---
title: MathNaryOperatorFactory
second_title: Aspose.Slides Android के लिए Java API रेफ़रेंस के माध्यम से
description: IMathNaryOperator बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathnaryoperatorfactory/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)  
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

IMathNaryOperator बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator बनाता है |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```

### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर चिन्ह |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए मूल तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर चिन्ह |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए मूल तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर चिन्ह |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए मूल तर्क |

**रिटर्न:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
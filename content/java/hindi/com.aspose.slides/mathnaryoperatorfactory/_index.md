---
title: MathNaryOperatorFactory
second_title: Aspose.Slides for Java API संदर्भ
description: IMathNaryOperator बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathnaryoperatorfactory/
---
**विरासत:**  
java.lang.Object

**सभी लागू इंटरफेस:**  
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
## मेथड

| विधि | विवरण |
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

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | ऊपरी सीमा |

**वापसी:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator बनाता है

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | निचली सीमा |

**वापसी:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator बनाता है

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| operatorSymbol | char | ऑपरेटर संकेत |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ऑपरेटर लागू करने के लिए बेस तर्क |

**वापसी:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - नया IMathNaryOperator
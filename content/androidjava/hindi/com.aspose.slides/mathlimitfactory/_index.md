---
title: MathLimitFactory
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: IMathLimit बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathlimitfactory/
---
**विरासत:**  
java.lang.Object

**सभी लागू किए गए इंटरफ़ेस:**  
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)  
```
public class MathLimitFactory implements IMathLimitFactory
```

IMathLimit बनाने की अनुमति देता है

--------------------

COM संगतता के लिए  
## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit बनाता है |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | नीचे सीमा के साथ IMathLimit बनाता है |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```

### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

IMathLimit बनाता है

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए आधार तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |
| upperLimit | boolean | सीमा को ऊपर रखने की व्यवस्था सेट करता है |

**रिटर्न:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणित सीमा
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

नीचे सीमा के साथ IMathLimit बनाता है

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए आधार तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |

**रिटर्न:**  
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणित सीमा
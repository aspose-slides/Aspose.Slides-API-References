---
title: MathFunctionFactory
second_title: Java के लिए Aspose.Slides API संदर्भ
description: गणितीय फ़ंक्शन बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathfunctionfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

गणितीय फ़ंक्शन बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## विधियां

| विधि | विवरण |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | गणितीय फ़ंक्शन बनाता है |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | गणितीय फ़ंक्शन बनाता है |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


गणितीय फ़ंक्शन बनाता है

**पैरामीटर:**
| परिचर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम के रूप में उपयोग किया गया तत्व |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में उपयोग किया गया तत्व |

**रिटर्न:**
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणितीय फ़ंक्शन
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


गणितीय फ़ंक्शन बनाता है

**पैरामीटर:**
| परिचर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | java.lang.String | फ़ंक्शन नाम |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में उपयोग किया गया तत्व |

**रिटर्न:**
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणितीय फ़ंक्शन
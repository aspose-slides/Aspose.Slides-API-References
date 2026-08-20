---
title: IMathFunctionFactory
second_title: Aspose.Slides के लिए Java API संदर्भ
description: गणित फ़ंक्शन बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

गणित फ़ंक्शन बनाने की अनुमति देता है

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | गणित फ़ंक्शन बनाता है |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | गणित फ़ंक्शन बनाता है |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


गणित फ़ंक्शन बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम के रूप में उपयोग किया गया तत्व |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में उपयोग किया गया तत्व |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणित फ़ंक्शन
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


गणित फ़ंक्शन बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| funcName | java.lang.String | फ़ंक्शन नाम |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में उपयोग किया गया तत्व |

**रिटर्न:**  
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणित फ़ंक्शन
---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: गणितीय फ़ंक्शन बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

गणितीय फ़ंक्शन बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


गणितीय फ़ंक्शन बनाता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन नाम के रूप में प्रयुक्त तत्व |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में प्रयुक्त तत्व |

**वापसी मान:**
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणितीय फ़ंक्शन
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


गणितीय फ़ंक्शन बनाता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| funcName | java.lang.String | फ़ंक्शन नाम |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | फ़ंक्शन तर्क के रूप में प्रयुक्त तत्व |

**वापसी मान:**
[IMathFunction](../../com.aspose.slides/imathfunction) - नया गणितीय फ़ंक्शन
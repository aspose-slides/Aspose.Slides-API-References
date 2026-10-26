---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathLimit
type: docs
url: /hi/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

IMathLimit बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit बनाता है |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathLimit बनाता है जिसमें सीमा नीचे हो |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए मूल तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |
| upperLimit | boolean | सीमा को शीर्ष पर रखने की व्यवस्था निर्धारित करता है |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणितीय सीमा
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


सीमा नीचे के साथ IMathLimit बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए मूल तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |

**रिटर्न:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणितीय सीमा
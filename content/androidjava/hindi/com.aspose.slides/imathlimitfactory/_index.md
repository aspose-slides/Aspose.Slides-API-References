---
title: IMathLimitFactory
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: IMathLimit बनाने की अनुमति देता है
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
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | निचले हिस्से में सीमा के साथ IMathLimit बनाता है |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

IMathLimit बनाता है

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए आधार तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |
| upperLimit | boolean | सीमा को शीर्ष पर रखने की स्थिति सेट करता है |

**वापसी:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणितीय सीमा
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

निचले हिस्से में सीमा के साथ IMathLimit बनाता है

**परामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | सीमा लागू करने के लिए आधार तर्क |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | सीमा तत्व |

**वापसी:**
[IMathLimit](../../com.aspose.slides/imathlimit) - नया गणितीय सीमा
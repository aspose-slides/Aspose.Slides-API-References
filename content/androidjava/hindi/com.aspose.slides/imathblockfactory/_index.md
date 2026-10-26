---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: गणित ब्लॉक बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

गणित ब्लॉक बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

एक गणित ब्लॉक बनाएं

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - नया गणित ब्लॉक
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

एक गणित ब्लॉक बनाएं और उस में तत्व रखें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | एक गणित तत्व |

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - नया गणित ब्लॉक
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

एक गणित ब्लॉक बनाएं और उसमें तत्व रखें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | गणित तत्व |

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - नया गणित ब्लॉक
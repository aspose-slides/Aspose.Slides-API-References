---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: गणित ब्लॉक बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

गणित ब्लॉक बनाने की अनुमति देता है

--------------------

COM संगति के लिए
## विधियां

| मेथड | विवरण |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | गणित ब्लॉक बनाएं |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | गणित ब्लॉक बनाएं और तत्व को उसमें रखें |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | गणित ब्लॉक बनाएं और तत्वों को उसमें रखें |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

गणित ब्लॉक बनाता है

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - नया गणित ब्लॉक
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

गणित ब्लॉक बनाएं और तत्व को उसमें रखें

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

गणित ब्लॉक बनाएं और तत्वों को उसमें रखें

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | गणित तत्व |

**रिटर्न:**
[IMathBlock](../../com.aspose.slides/imathblock) - नया गणित ब्लॉक
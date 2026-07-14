---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math array
type: docs
url: /hi/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

math array बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


array में रखने के लिए निर्दिष्ट तत्व के साथ एक math array बनाता है

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | array में रखने के लिए math element |

**वापसी मान:**
[IMathArray](../../com.aspose.slides/imatharray) - नया math array
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


निर्दिष्ट तत्वों के साथ एक math array बनाता है

**परामीटर:**
| परामीटर | टाइप | विवरण |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | array में रखने के लिए math elements |

**वापसी मान:**
[IMathArray](../../com.aspose.slides/imatharray) - नया math array
---
title: IMathAccentFactory
second_title: Aspose.Slides for Java API संदर्भ
description: गणितात्मक एक्सेंट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

गणितात्मक एक्सेंट बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## विधियां

| विधि | विवरण |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


निर्दिष्ट गणितीय तत्व पर डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ लागू होने वाला गणित एक्सेंट बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Math element to apply accent |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणितीय एक्सेंट
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणित एक्सेंट बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Math element to apply accent |
| accentCharacter | char | accent character |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणितीय एक्सेंट
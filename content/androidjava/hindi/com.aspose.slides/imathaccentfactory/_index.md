---
title: IMathAccentFactory
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: गणित एक्सेंट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

गणित एक्सेंट बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | निर्दिष्ट गणित तत्व पर लागू होने वाला गणित एक्सेंट डिफ़ॉल्ट एक्सेंट कैरेक्टर वैल्यू के साथ बनाता है |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | निर्दिष्ट गणित तत्व पर लागू होने वाला गणित एक्सेंट बनाता है |
### createMathAccent(IMMathElement element) {#createMathAccent-com.aspose.slides.IMMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

निर्दिष्ट गणित तत्व पर लागू होने वाला गणित एक्सेंट डिफ़ॉल्ट एक्सेंट कैरेक्टर वैल्यू के साथ बनाता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए गणित तत्व |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणित एक्सेंट
### createMathAccent(IMMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

निर्दिष्ट गणित तत्व पर लागू होने वाला गणित एक्सेंट बनाता है

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए गणित तत्व |
| accentCharacter | char | एक्सेंट कैरेक्टर |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणित एक्सेंट
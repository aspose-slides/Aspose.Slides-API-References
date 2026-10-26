---
title: MathAccentFactory
second_title: Aspose.Slides के लिए जावा API रेफ़रेंस
description: मैथ एक्सेंट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathaccentfactory/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

मैथ एक्सेंट बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## निर्माताओं

| निर्माता | विवरण |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ निर्दिष्ट math element पर एक math accent बनाता है |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | निर्दिष्ट math element पर एक math accent बनाता है |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```

### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```

डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ निर्दिष्ट math element पर एक math accent बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element पर एक्सेंट लागू करने के लिए |

**रिटर्न:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - नया math accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

निर्दिष्ट math element पर एक math accent बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element पर एक्सेंट लागू करने के लिए |
| accentCharacter | char | एक्सेंट कैरेक्टर |

**रिटर्न:**  
[IMathAccent](../../com.aspose.slides/imathaccent) - नया math accent
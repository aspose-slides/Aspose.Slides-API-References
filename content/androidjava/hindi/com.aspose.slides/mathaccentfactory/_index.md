---
title: MathAccentFactory
second_title: Aspose.Slides for Android के माध्यम से Java API रेफ़रेंस
description: गणितीय एक्सेंट बनाने की अनुमति देता है
type: docs
url: /hi/com.aspose.slides/mathaccentfactory/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेसेज़:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

गणितीय एक्सेंट बनाने की अनुमति देता है

--------------------

COM संगतता के लिए
## निर्माताएँ

| निर्माता | विवरण |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए गणितीय तत्व |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणितीय एक्सेंट
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


निर्दिष्ट गणितीय तत्व पर एक गणितीय एक्सेंट बनाता है

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए गणितीय तत्व |
| accentCharacter | char | एक्सेंट कैरेक्टर |

**रिटर्न:**
[IMathAccent](../../com.aspose.slides/imathaccent) - नया गणितीय एक्सेंट
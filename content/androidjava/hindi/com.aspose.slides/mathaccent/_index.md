---
title: MathAccent
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक बेस और संयोजक डायाक्रिटिकल मार्क से बने एक्सेंट फ़ंक्शन को निर्दिष्ट करता है उदाहरण ud835udc4eu0301
type: docs
url: /hi/com.aspose.slides/mathaccent/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

एक्सेंट फ़ंक्शन निर्दिष्ट करता है, जिसमें एक बेस और एक संयोजक डायाक्रिटिकल मार्क होता है उदाहरण: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | निर्दिष्ट गणितीय तत्व पर लागू डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ एक गणितीय एक्सेंट बनाता है |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | निर्दिष्ट गणितीय तत्व पर लागू एक गणितीय एक्सेंट बनाता है |
## विधियां

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | वह तर्क जिससे एक्सेंट लागू किया गया था |
| [getCharacter()](#getCharacter--) | Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण कैरेक्टर गुण |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

निर्दिष्ट गणितीय तत्व पर लागू डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ एक गणितीय एक्सेंट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए एक गणितीय तत्व |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

निर्दिष्ट गणितीय तत्व पर लागू एक गणितीय एक्सेंट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लागू करने के लिए गणितीय तत्व |
| accentCharacter | char | एक्सेंट कैरेक्टर |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

वह तर्क जिससे एक्सेंट लागू किया गया था

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**रिटर्न:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चों के तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

नियंत्रण कैरेक्टर गुण

**रिटर्न:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
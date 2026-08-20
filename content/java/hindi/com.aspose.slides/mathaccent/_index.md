---
title: MathAccent
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक बेस और संयोजित डायाक्रिटिकल मार्क से बनी एक्सेंट फ़ंक्शन को निर्दिष्ट करता है उदाहरण ud835udc4eu0301
type: docs
url: /hi/com.aspose.slides/mathaccent/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

एक्सेंट फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और संयोजित दक्षिणी चिह्न शामिल होते हैं उदाहरण: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## निर्माता

| Constructor | Description |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | निर्दिष्ट गणित तत्व पर डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ एक गणित एक्सेंट बनाता है |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | निर्दिष्ट गणित तत्व पर एक गणित एक्सेंट बनाता है |
## विधियाँ

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | वह तर्क जिस पर एक्सेंट लागू किया गया था |
| [getCharacter()](#getCharacter--) | Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | बच्चों तत्वों को प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

निर्दिष्ट गणित तत्व पर डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ एक गणित एक्सेंट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लगाने के लिए एक गणित तत्व |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

निर्दिष्ट गणित तत्व पर एक गणित एक्सेंट बनाता है

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | एक्सेंट लगाने के लिए गणित तत्व |
| accentCharacter | char | एक्सेंट कैरेक्टर |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

वह तर्क जिस पर एक्सेंट लागू किया गया था

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

Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

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

Accent Character मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**पैरामीटर:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

बच्चों तत्वों को प्राप्त करें

**रिटर्न:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**रिटर्न:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
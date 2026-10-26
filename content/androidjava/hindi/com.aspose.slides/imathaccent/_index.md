---
title: IMathAccent
second_title: Java API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: एक बेस और एक संयोजनात्मक स्वरचिह्न से बनी एक्सेंट फ़ंक्शन को निर्दिष्ट करता है उदाहरण ud835udc4eu0301
type: docs
url: /hi/com.aspose.slides/imathaccent/
---
**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

एक्सेंट फ़ंक्शन को निर्दिष्ट करता है, जो एक बेस और एक संयोजनात्मक स्वरचिह्न से बना होता है उदाहरण: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | वह तर्क जिससे एक्सेंट लागू किया गया |
| [getCharacter()](#getCharacter--) | एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

वह तर्क जिससे एक्सेंट लागू किया गया

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
public abstract char getCharacter()
```

एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

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
public abstract void setCharacter(char value)
```

एक्सेंट कैरेक्टर मान (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) की सीमा में होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

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
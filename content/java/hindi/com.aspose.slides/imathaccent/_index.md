---
title: IMathAccent
second_title: Aspose.Slides for Java API संदर्भ
description: एक बेस और संयोजित डायक्रिटिकल मार्क से बना एक्सेंट फ़ंक्शन निर्दिष्ट करता है। उदाहरण ud835udc4eu0301
type: docs
url: /hi/com.aspose.slides/imathaccent/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

एक्सेंट फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और एक संयोजित डायक्रिटिकल मार्क शामिल है। उदाहरण: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | जिस तर्क पर एक्सेंट लागू किया गया |
| [getCharacter()](#getCharacter--) | Accent Character मान को (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character मान को (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


जिस तर्क पर एक्सेंट लागू किया गया

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


Accent Character मान को (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

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


Accent Character मान को (U+0300\\u2013U+036F) या (U+20D0\\u2013U+20EF) सीमा के भीतर होना चाहिए। डिफ़ॉल्ट मान: Combining Circumflex Accent (U+0302)

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
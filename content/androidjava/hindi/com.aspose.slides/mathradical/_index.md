---
title: MathRadical
second_title: Aspose.Slides for Android का Java API संदर्भ
description: एक बेस और वैकल्पिक डिग्री से मिलकर बनी मूल (रैडिकल) फ़ंक्शन को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathradical/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

एक मूल फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और एक वैकल्पिक डिग्री शामिल है। मूल वस्तु का उदाहरण है \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```
## निर्माता

| Constructor | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRadical क्लास का नया इंस्टेंस प्रारंभ करता है। |
## विधियाँ

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | आधार तर्क |
| [getDegree()](#getDegree--) | डिग्री तर्क |
| [getHideDegree()](#getHideDegree--) | Hide degree जब सत्य हो, डिग्री नहीं दिखायी देती, जैसे \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree जब सत्य हो, डिग्री नहीं दिखायी देती, जैसे \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | बच्चे तत्व प्राप्त करें |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


MathRadical क्लास का नया इंस्टेंस प्रारंभ करता है।

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | आधार |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | डिग्री |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


आधार तर्क

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


डिग्री तर्क

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Hide degree जब सत्य हो, डिग्री नहीं दिखायी देती, जैसे \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**वापसी:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Hide degree जब सत्य हो, डिग्री नहीं दिखायी देती, जैसे \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


बच्चे तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]
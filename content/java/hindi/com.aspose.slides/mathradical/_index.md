---
title: MathRadical
second_title: Aspose.Slides for Java API संदर्भ
description: एक बेस और वैकल्पिक डिग्री से बने रेडिकल फ़ंक्शन को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathradical/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

रेडिकल फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और एक वैकल्पिक डिग्री शामिल है। रेडिकल ऑब्जेक्ट का उदाहरण है \u221a\ud835\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## कंस्ट्रक्टर्स

| निर्माता | विवरण |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRadical क्लास का एक नया उदाहरण इनिशियलाइज़ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getDegree()](#getDegree--) | डिग्री तर्क |
| [getHideDegree()](#getHideDegree--) | जब true हो तो डिग्री छुपाएँ, डिग्री नहीं दिखायी देती, जैसे \u221a\ud835\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | जब true हो तो डिग्री छुपाएँ, डिग्री नहीं दिखायी देती, जैसे \u221a\ud835\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

MathRadical क्लास का एक नया उदाहरण इनिशियलाइज़ करता है।

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | बेस |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | डिग्री |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

बेस तर्क

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

जब true हो तो डिग्री छुपाएँ, डिग्री नहीं दिखायी देती, जैसे \u221a\ud835\udc65

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

जब true हो तो डिग्री छुपाएँ, डिग्री नहीं दिखायी देती, जैसे \u221a\ud835\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

कंट्रोल कैरेक्टर प्रॉपर्टीज़

**वापसी:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

संतान तत्व प्राप्त करें

**वापसी:**  
com.aspose.slides.IMathElement[]
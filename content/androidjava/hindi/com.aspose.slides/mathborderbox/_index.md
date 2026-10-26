---
title: MathBorderBox
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: IMathElement के चारों ओर आयताकार या अन्य प्रकार की सीमा बनाता है।
type: docs
url: /hi/com.aspose.slides/mathborderbox/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

IMathElement के चारों ओर एक आयताकार या अन्य प्रकार की सीमा बनाता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | आयताकार सीमा के साथ MathBorderBox तत्व बनाता है |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox तत्व बनाता है |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getHideTop()](#getHideTop--) | शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setHideTop(boolean value)](#setHideTop-boolean-) | शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getHideBottom()](#getHideBottom--) | नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के नीचे किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के नीचे किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getHideLeft()](#getHideLeft--) | बायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | बायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getHideRight()](#getHideRight--) | दायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setHideRight(boolean value)](#setHideRight-boolean-) | दायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | ऊर्ध्वाधर स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - ऊर्ध्वाधर स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | ऊर्ध्वाधर स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - ऊर्ध्वाधर स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | नियंत्रण अक्षर गुण |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


आयताकार सीमा के साथ MathBorderBox तत्व बनाता है

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस तत्व जिससे बॉर्डर बॉक्स लागू किया जाता है। null हो सकता है। |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


MathBorderBox तत्व बनाता है

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | वह बेस तत्व जिससे बॉर्डर बॉक्स लागू किया जाता है |
| hideTop | boolean | शीर्ष किनारा छिपाएँ |
| hideBottom | boolean | नीचे किनारा छिपाएँ |
| hideLeft | boolean | बायाँ किनारा छिपाएँ |
| hideRight | boolean | दायाँ किनारा छिपाएँ |
| strikethroughHorizontal | boolean | क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | ऊर्ध्वाधर स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


बेस तर्क

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**वापसी:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के नीचे किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**वापसी:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के नीचे किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


बायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**वापसी:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


बायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


दायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**वापसी:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


दायाँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**वापसी:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


ऊर्ध्वाधर स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - ऊर्ध्वाधर स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**वापसी:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


ऊर्ध्वाधर स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - ऊर्ध्वाधर स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के नीचे-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**वापसी:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के नीचे-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के ऊपर-बाएँ कोने से नीचे-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**वापसी:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के ऊपर-बाएँ कोने से नीचे-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू लाइन की छिपी या दिखाई देने वाली स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


संतान तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


नियंत्रण अक्षर गुण

**वापसी:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
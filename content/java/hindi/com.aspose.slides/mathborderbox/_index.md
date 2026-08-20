---
title: MathBorderBox
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: IMathElement के चारों ओर आयताकार या कोई अन्य सीमा बनाता है।
type: docs
url: /hi/com.aspose.slides/mathborderbox/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

IMathElement के चारों ओर आयताकार या अन्य कोई सीमा बनाता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | आयताकार सीमा के साथ MathBorderBox तत्व बनाता है |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | MathBorderBox तत्व बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getHideTop()](#getHideTop--) | शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setHideTop(boolean value)](#setHideTop-boolean-) | शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getHideBottom()](#getHideBottom--) | निचला किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के निचले किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | निचला किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के निचले किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getHideLeft()](#getHideLeft--) | बाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | बाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getHideRight()](#getHideRight--) | दाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setHideRight(boolean value)](#setHideRight-boolean-) | दाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | वर्टिकल स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - वर्टिकल स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | वर्टिकल स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - वर्टिकल स्ट्रिंकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | निचले-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | निचले-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | ऊपर-बाएँ से निचले-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | ऊपर-बाएँ से निचले-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | कंट्रोल कैरेक्टर प्रॉपर्टीज़ |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू किया जाने वाला बेस तत्व। null हो सकता है। |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | बॉर्डर बॉक्स लागू किया जाने वाला बेस तत्व |
| hideTop | boolean | शीर्ष किनारा छिपाएँ |
| hideBottom | boolean | निचला किनारा छिपाएँ |
| hideLeft | boolean | बाएँ किनारा छिपाएँ |
| hideRight | boolean | दाएँ किनारा छिपाएँ |
| strikethroughHorizontal | boolean | क्षैतिज स्ट्राइकथ्रू |
| strikethroughVertical | boolean | वर्टिकल स्ट्राइकथ्रू |
| strikethroughBottomLeftToTopRight | boolean | निचले-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू |
| strikethroughTopLeftToBottomRight | boolean | ऊपर-बाएँ से निचले-दाएँ स्ट्राइकथ्रू |

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

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**रिटर्न:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

शीर्ष किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के शीर्ष किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

निचला किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के निचले किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**रिटर्न:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

निचला किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के निचले किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

बाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**रिटर्न:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

बाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के बाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

दाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**रिटर्न:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

दाएँ किनारा छिपाएँ (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स के दाएँ किनारे की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

क्षैतिज स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

वर्टिकल स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - वर्टिकल स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

वर्टिकल स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - वर्टिकल स्ट्राइकथ्रू रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

निचले-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के निचले-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

निचले-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के निचले-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

ऊपर-बाएँ से निचले-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के ऊपर-बाएँ कोने से निचले-दाएँ कोने तक की विकर्ण रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

ऊपर-बाएँ से निचले-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। बॉर्डर बॉक्स के ऊपर-बाएँ कोने से निचले-दाएँ कोने तक की विकर्ण रेखा की छिपी या दिखी हुई स्थिति को निर्दिष्ट करता है।

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

बच्चों के तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

कंट्रोल कैरेक्टर प्रॉपर्टीज़

**रिटर्न:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
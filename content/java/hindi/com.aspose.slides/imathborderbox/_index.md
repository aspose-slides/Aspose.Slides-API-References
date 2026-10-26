---
title: IMathBorderBox
second_title: Aspose.Slides के लिए Java API संदर्भ
description: IMathElement के चारों ओर आयताकार या अन्य प्रकार की सीमा बनाता है।
type: docs
url: /hi/com.aspose.slides/imathborderbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Draws a rectangular or some other border around the IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की निचली किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की निचली किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getHideRight()](#getHideRight--) | Hide Right Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (डिफ़ॉल्ट false है) - लंबवत स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (डिफ़ॉल्ट false है) - लंबवत स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है। |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (डिफ़ॉल्ट false है). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (डिफ़ॉल्ट false है). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (डिफ़ॉल्ट false है). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (डिफ़ॉल्ट false है). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```


**रिटर्न्स:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


Hide Top Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**रिटर्न्स:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


Hide Top Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की शीर्ष किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


Hide Bottom Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की निचली किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**रिटर्न्स:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


Hide Bottom Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की निचली किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


Hide Left Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**रिटर्न्स:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


Hide Left Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की बाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


Hide Right Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**रिटर्न्स:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


Hide Right Edge (डिफ़ॉल्ट false है) - बॉर्डर बॉक्स की दाएँ किनारे की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


Strikethrough Horizontal (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**रिटर्न्स:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


Strikethrough Horizontal (डिफ़ॉल्ट false है) - क्षैतिज स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


Strikethrough Vertical (डिफ़ॉल्ट false है) - लंबवत स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**रिटर्न्स:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


Strikethrough Vertical (डिफ़ॉल्ट false है) - लंबवत स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


Strikethrough Bottom-Left to Top-Right (डिफ़ॉल्ट false है). बॉर्डर बॉक्स के निचले-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**रिटर्न्स:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


Strikethrough Bottom-Left to Top-Right (डिफ़ॉल्ट false है). बॉर्डर बॉक्स के निचले-बाएँ कोने से ऊपर-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```


**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


Strikethrough Top-Left to Bottom-Right (डिफ़ॉल्ट false है). बॉर्डर बॉक्स के ऊपर-बाएँ कोने से निचले-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**रिटर्न्स:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


Strikethrough Top-Left to Bottom-Right (डिफ़ॉल्ट false है). बॉर्डर बॉक्स के ऊपर-बाएँ कोने से निचले-दाएँ कोने तक की विकर्ण स्ट्राइकथ्रू रेखा की छिपी या दिखाई देने वाली स्थिति निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**पैरामीटर:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
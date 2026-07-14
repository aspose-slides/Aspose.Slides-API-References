---
title: IMathBorderBox
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: IMathElement के चारों ओर एक आयताकार या अन्य सीमा खींचता है।
type: docs
url: /hi/com.aspose.slides/imathborderbox/
---
**सभी लागू इंटरफेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

IMathElement के चारों ओर एक आयताकार या अन्य सीमा खींचता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getHideTop()](#getHideTop--) | ऊपरी किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के ऊपरी किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setHideTop(boolean value)](#setHideTop-boolean-) | ऊपरी किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के ऊपरी किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getHideBottom()](#getHideBottom--) | नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के नीचे किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के नीचे किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getHideLeft()](#getHideLeft--) | बायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के बाएं किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | बायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के बाएं किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getHideRight()](#getHideRight--) | दायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के दाएँ किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setHideRight(boolean value)](#setHideRight-boolean-) | दायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के दाएँ किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | आड़िया स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक आड़िया स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | आड़िया स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक आड़िया स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | लंबवत स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक लंबवत स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | लंबवत स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक लंबवत स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है। |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


बेस तर्क

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```


ऊपरी किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के ऊपरी किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**रिटर्न:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```


ऊपरी किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के ऊपरी किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```


नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के नीचे किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**रिटर्न:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```


नीचे किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के नीचे किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```


बायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के बाएं किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**रिटर्न:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```


बायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के बाएं किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```


दायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के दाएँ किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**रिटर्न:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```


दायां किनारा छिपाएँ (डिफ़ॉल्ट false है) - सीमा बॉक्स के दाएँ किनारे की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```


आड़िया स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक आड़िया स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```


आड़िया स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक आड़िया स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```


लंबवत स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक लंबवत स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```


लंबवत स्ट्राइकथ्रू (डिफ़ॉल्ट false है) - एक लंबवत स्ट्राइकथ्रू रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```


नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। सीमा बॉक्स के नीचे-बाएँ कोने से ऊपर-दाएँ कोने तक की स्ट्राइकथ्रू तिरछी रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```


नीचे-बाएँ से ऊपर-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। सीमा बॉक्स के नीचे-बाएँ कोने से ऊपर-दाएँ कोने तक की स्ट्राइकथ्रू तिरछी रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```


ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। सीमा बॉक्स के ऊपर-बाएँ कोने से नीचे-दाएँ कोने तक की स्ट्राइकथ्रू तिरछी रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**रिटर्न:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```


ऊपर-बाएँ से नीचे-दाएँ स्ट्राइकथ्रू (डिफ़ॉल्ट false है)। सीमा बॉक्स के ऊपर-बाएँ कोने से नीचे-दाएँ कोने तक की स्ट्राइकथ्रू तिरछी रेखा की छिपी या प्रदर्शित स्थिति को निर्दिष्ट करता है।

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
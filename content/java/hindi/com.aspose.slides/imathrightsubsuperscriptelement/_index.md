---
title: IMathRightSubSuperscriptElement
second_title: Aspose.Slides के लिए Java API संदर्भ
description: Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और एक सबस्क्रिप्ट और सुपरस्क्रिप्ट से बना है जो बेस के दाएँ पक्ष में रखा जाता है।
type: docs
url: /hi/com.aspose.slides/imathrightsubsuperscriptelement/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और एक सबस्क्रिप्ट और सुपरस्क्रिप्ट से बना है जो बेस के दाएँ पक्ष में रखा जाता है।

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getSubscript()](#getSubscript--) | Subscript argument |
| [getSuperscript()](#getSuperscript--) | Superscript argument |
| [getAlignScripts()](#getAlignScripts--) | Specifies the alignment of subscript/superscript. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | Specifies the alignment of subscript/superscript. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Base argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement baseElem = subsuperscript.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


Subscript argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sub = subsuperscript.getSubscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


Superscript argument

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  IMathElement sup = subsuperscript.getSuperscript();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```


subscript/supercript के संरेखण को निर्दिष्ट करता है। जब true हो तो सबस्क्रिप्ट और सुपरस्क्रिप्ट आपस में क्षैतिज रूप से संरेखित होते हैं। जब false हो तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Returns:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```


subscript/supercript के संरेखण को निर्दिष्ट करता है। जब true हो तो सबस्क्रिप्ट और सुपरस्क्रिप्ट आपस में क्षैतिज रूप से संरेखित होते हैं। जब false हो तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
>  subsuperscript.setAlignScripts(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
---
title: IMathRightSubSuperscriptElement
second_title: Java API रेफ़रेंस द्वारा Android के लिए Aspose.Slides
description: बेस और बेस के दाईं ओर रखे गए सबस्क्रिप्ट और सुपरसक्रिप्ट से मिलकर बने Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathrightsubsuperscriptelement/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathRightSubSuperscriptElement extends IMathElement
```

Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और बेस के दाईं ओर रखे गए सबस्क्रिप्ट व सुपरसक्रिप्ट से बना होता है।

--------------------

> ```
> Example:
>  
>  IMathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").setSubSuperscriptOnTheRight("i", "j");
>  ```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट तर्क |
| [getSuperscript()](#getSuperscript--) | सुपरसक्रिप्ट तर्क |
| [getAlignScripts()](#getAlignScripts--) | सबस्क्रिप्ट/सुपरसक्रिप्ट की संरेखण को निर्दिष्ट करता है। |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | सबस्क्रिप्ट/सुपरसक्रिप्ट की संरेखण को निर्दिष्ट करता है। |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

बेस तर्क

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

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

सबस्क्रिप्ट तर्क

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


**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

सुपरसक्रिप्ट तर्क

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

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public abstract boolean getAlignScripts()
```

सबस्क्रिप्ट/सुपरसक्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरसक्रिप्ट एक-दूसरे के साथ क्षैतिज रूप से संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

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

**रिटर्न:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public abstract void setAlignScripts(boolean value)
```

सबस्क्रिप्ट/सुपरसक्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरसक्रिप्ट एक-दूसरे के साथ क्षैतिज रूप से संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

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

**पैरामीटर:**
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
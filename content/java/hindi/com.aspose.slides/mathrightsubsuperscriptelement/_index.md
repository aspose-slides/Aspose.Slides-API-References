---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides for Java API संदर्भ
description: एक बेस और एक सबस्क्रिप्ट तथा सुपरस्क्रिप्ट जो बेस के दाएँ ओर स्थित होते हैं, से मिलकर बनता Sub-Superscript ऑब्जेक्ट निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathrightsubsuperscriptelement/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और एक सबस्क्रिप्ट तथा सुपरस्क्रिप्ट से बना होता है जो बेस के दाएँ ओर रखे जाते हैं।

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRightSubSuperscriptElement क्लास का नया उदाहरण प्रारंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट तर्क |
| [getSuperscript()](#getSuperscript--) | सुपरस्क्रिप्ट तर्क |
| [getAlignScripts()](#getAlignScripts--) | सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण निर्दिष्ट करता है। |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण निर्दिष्ट करता है। |
| [getChildren()](#getChildren--) | बच्चों के तत्व प्राप्त करें |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


MathRightSubSuperscriptElement क्लास का नया उदाहरण प्रारंभ करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
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
public final IMathElement getSuperscript()
```


सुपरस्क्रिप्ट तर्क

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
public final boolean getAlignScripts()
```


सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरस्क्रिप्ट क्षैतिज रूप से एक-दूसरे के साथ संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

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
public final void setAlignScripts(boolean value)
```


सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरस्क्रिप्ट क्षैतिज रूप से एक-दूसरे के साथ संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


संतान तत्व प्राप्त करें

**रिटर्न:**
com.aspose.slides.IMathElement[]
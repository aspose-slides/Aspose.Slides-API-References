---
title: MathRightSubSuperscriptElement
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: बेज़ और बेज़ के दाएँ स्थित उपस्क्रिप्ट और सुपरस्क्रिप्ट वाले Sub-Superscript ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/mathrightsubsuperscriptelement/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**सभी लागू इंटरफ़ेसेस:**
[com.aspose.slides.IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
```
public final class MathRightSubSuperscriptElement extends BaseScript implements IMathRightSubSuperscriptElement
```

Sub-Superscript ऑब्जेक्ट निर्दिष्ट करता है, जो एक बेज़ और बेज़ के दाएँ पक्ष में स्थित उपस्क्रिप्ट और सुपरस्क्रिप्ट से बना होता है।

--------------------

> ```
> Example:
>  
>  MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)](#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRightSubSuperscriptElement क्लास का नया इंस्टेंस आरंभ करता है. |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSubscript()](#getSubscript--) | Subscript तर्क |
| [getSuperscript()](#getSuperscript--) | Superscript तर्क |
| [getAlignScripts()](#getAlignScripts--) | उपस्क्रिप्ट/सुपरस्क्रिप्ट के संरेखण को निर्दिष्ट करता है. |
| [setAlignScripts(boolean value)](#setAlignScripts-boolean-) | उपस्क्रिप्ट/सुपरस्क्रिप्ट के संरेखण को निर्दिष्ट करता है. |
| [getChildren()](#getChildren--) | चाइल्ड तत्व प्राप्त करें |
### MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript) {#MathRightSubSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRightSubSuperscriptElement(IMathElement baseArg, IMathElement subScript, IMathElement superScript)
```


MathRightSubSuperscriptElement क्लास का नया इंस्टेंस आरंभ करता है.

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


Subscript तर्क

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

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


Superscript तर्क

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

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getAlignScripts() {#getAlignScripts--}
```
public final boolean getAlignScripts()
```


उपस्क्रिप्ट/सुपरस्क्रिप्ट के संरेखण को निर्दिष्ट करता है. यदि true हो तो उपस्क्रिप्ट और सुपरस्क्रिप्ट एक-दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं. यदि false हो तो वे बेज़ के आकार के अनुसार समायोजित होते हैं. डिफ़ॉल्ट मान false है.

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

**वापसी:**
boolean
### setAlignScripts(boolean value) {#setAlignScripts-boolean-}
```
public final void setAlignScripts(boolean value)
```


उपस्क्रिप्ट/सुपरस्क्रिप्ट के संरेखण को निर्दिष्ट करता है. यदि true हो तो उपस्क्रिप्ट और सुपरस्क्रिप्ट एक-दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं. यदि false हो तो वे बेज़ के आकार के अनुसार समायोजित होते हैं. डिफ़ॉल्ट मान false है.

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


चाइल्ड तत्व प्राप्त करें

**वापसी:**
com.aspose.slides.IMathElement[]
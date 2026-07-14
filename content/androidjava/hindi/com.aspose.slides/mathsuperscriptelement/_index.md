---
title: MathSuperscriptElement
second_title: Aspose.Slides एंड्रॉइड के लिए जावा API रेफ़रेंस के माध्यम से
description: एक बेस और ऊपर तथा दाएँ स्थित घटाए हुए आकार के सुपरस्क्रिप्ट से मिलकर बनने वाले सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/mathsuperscriptelement/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**सभी लागू किए गए इंटरफ़ेस:**
[com.aspose.slides.IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
```
public final class MathSuperscriptElement extends BaseScript implements IMathSuperscriptElement
```

सुपरसक्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और एक घटाए हुए आकार के सुपरस्क्रिप्ट से बनता है, जो ऊपर और दाईं ओर स्थित होता है

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)](#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSuperscriptElement क्लास का एक नया उदाहरण आरंभ करता है। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getSuperscript()](#getSuperscript--) | सुपरस्क्रिप्ट |
| [getChildren()](#getChildren--) | संतान तत्व प्राप्त करें |
### MathSuperscriptElement(IMathElement baseArg, IMathElement superScript) {#MathSuperscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSuperscriptElement(IMathElement baseArg, IMathElement superScript)
```


MathSuperscriptElement क्लास का एक नया उदाहरण आरंभ करता है।

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| superScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


सुपरसक्रिप्ट

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  MathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**वापसी मान:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


संतान तत्व प्राप्त करें

**वापसी मान:**
com.aspose.slides.IMathElement[]
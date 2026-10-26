---
title: IMathSuperscriptElement
second_title: जावा API रेफ़रेंस के माध्यम से Android के लिए Aspose.Slides
description: एक बेस और छोटी आकार की सुपरस्क्रिप्ट, जो ऊपर और दाएँ स्थित है, से मिलकर बने सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है
type: docs
url: /hi/com.aspose.slides/imathsuperscriptelement/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

बेस और एक छोटे आकार वाले सुपरस्क्रिप्ट, जो ऊपर और दाएँ स्थित है, से मिलकर बना सुपरस्क्रिप्ट ऑब्जेक्ट निर्दिष्ट करता है

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSuperscript()](#getSuperscript--) | सुपरस्क्रिप्ट |
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
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, subscript);
>  IMathElement baseElem = superscriptElement.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


सुपरस्क्रिप्ट

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement superscript = new MathematicalText("i");
>  IMathSuperscriptElement superscriptElement = new MathSuperscriptElement(baseElement, superscript);
>  IMathElement super = superscriptElement.getSuperscript();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
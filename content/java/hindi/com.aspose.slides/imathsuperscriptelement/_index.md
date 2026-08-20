---
title: IMathSuperscriptElement
second_title: Aspose.Slides का Java API संदर्भ
description: सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक बेस और एक छोटा आकार का सुपरस्क्रिप्ट ऊपर और दाईं ओर स्थित होता है
type: docs
url: /hi/com.aspose.slides/imathsuperscriptelement/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSuperscriptElement extends IMathElement
```

सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक बेस और एक छोटा आकार का सुपरस्क्रिप्ट ऊपर और दाईं ओर स्थित होता है

--------------------

> ```
> Example:
>  
>  IMathSuperscriptElement superscriptElement = new MathematicalText("N").setSuperscript("i");
> ```
## विधियां

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
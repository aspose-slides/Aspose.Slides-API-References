---
title: IMathSubscriptElement
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: सबस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और नीचे तथा दाएँ स्थित एक छोटा आकार का सबस्क्रिप्ट से बना होता है।
type: docs
url: /hi/com.aspose.slides/imathsubscriptelement/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

सबस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और नीचे तथा दाएँ स्थित एक छोटा आकार का सबस्क्रिप्ट से बना होता है।

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
```
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getBase()](#getBase--) | बेस तर्क |
| [getSubscript()](#getSubscript--) | सबस्क्रिप्ट |
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
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


सबस्क्रिप्ट

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**वापसी:**
[IMathElement](../../com.aspose.slides/imathelement)
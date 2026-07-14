---
title: IMathNaryOperator
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: Summation और Integral जैसी N-ary गणितीय वस्तु को निर्दिष्ट करता है।
type: docs
url: /hi/com.aspose.slides/imathnaryoperator/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस (या ऑपरेन्ड), और वैकल्पिक ऊपरी और निचली सीमाओं से बना होता है। N-ary ऑपरेटर्स के उदाहरण हैं: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getBase()](#getBase--) | आधार तर्क |
| [getSubscript()](#getSubscript--) | उपस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, एक integral के मामले में, निचली सीमा सेट करता है |
| [getSuperscript()](#getSuperscript--) | सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, एक integral के मामले में, ऊपरी सीमा सेट करता है |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


आधार तर्क

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```


उपस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, एक integral के मामले में, निचली सीमा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```


सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, एक integral के मामले में, ऊपरी सीमा सेट करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**रिटर्न:**
[IMathElement](../../com.aspose.slides/imathelement)
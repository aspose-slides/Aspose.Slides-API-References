---
title: IMathNaryOperator
second_title: Aspose.Slides for Java API संदर्भ
description: एक N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral।
type: docs
url: /hi/com.aspose.slides/imathnaryoperator/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

एक N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे कि Summation और Integral। यह एक ऑपरेटर, एक आधार (या ऑपरेण्ड), और वैकल्पिक ऊपरी तथा निचले सीमाओं से बना होता है। N-ary ऑपरेटरों के उदाहरण हैं: Summation, Union, Intersection, Integral

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
| [getSubscript()](#getSubscript--) | एक सबस्क्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, यदि यह इंटीग्रल है, तो निचला सीमा निर्धारित करता है |
| [getSuperscript()](#getSuperscript--) | एक सुपरसक्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, यदि यह इंटीग्रल है, तो ऊपरी सीमा निर्धारित करता है |
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
>  ```

**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

एक सबस्क्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, यदि यह इंटीग्रल है, तो निचला सीमा निर्धारित करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
>  ```


**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

एक सुपरसक्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, यदि यह इंटीग्रल है, तो ऊपरी सीमा निर्धारित करता है

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```


**रिटर्न:**  
[IMathElement](../../com.aspose.slides/imathelement)
---
title: IMathElement
second_title: Aspose.Sildes for .NET API संदर्भ
description: किसी भी गणितीय तत्व जैसे अंश, गणितीय पाठ, फ़ंक्शन, कई तत्वों वाली अभिव्यक्ति आदि का मूल इंटरफ़ेस
type: docs
weight: 8230
url: /hi/aspose.slides.mathtext/imathelement/
---
## IMathElement इंटरफ़ेस

किसी भी गणितीय तत्व का मूल इंटरफ़ेस: अंश, गणितीय पाठ, फ़ंक्शन, कई तत्वों वाले अभिव्यक्ति आदि

```csharp
public interface IMathElement
```

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | इस तत्व के शीर्ष पर एक उच्चारण चिह्न (एक अक्षर) सेट करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | निर्दिष्ट फ़ंक्शन को लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करते हुए |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करते हुए |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करते हुए |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | निर्दिष्ट हर के साथ इस अंशांक से एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | निर्दिष्ट हर के साथ इस अंशांक से एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर से एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर से एक भिन्न बनाता है |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | एक गणितीय तत्व को कोष्ठकों में बंद करता है |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | इस तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेम के रूप में बंद करता है |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करते हुए तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करते हुए तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | निचले कर्ली ब्रेस का उपयोग करके इस तत्व को समूह में रखता है |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | निचले कर्ली ब्रेस या अन्य समूह अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | एक गणितीय तत्व को मिलाकर एक गणितीय ब्लॉक बनाता है |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | गणितीय पाठ को मिलाकर एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | निम्न सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | निम्न सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | सुपर्सक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | उपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | उपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड वस्तु (उदाहरण के लिए) एक ऑपरेटर एмуляटर के रूप में काम कर सकती है, संरेखण बिंदु के साथ या बिना, लाइन-ब्रेक बिंदु बन सकती है, या इस तरह समूहित हो सकती है कि लाइन-ब्रेक न हो। |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | एक लंबवत ऐरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### संबंधित देखें

* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
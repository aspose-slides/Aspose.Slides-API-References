---
title: MathElementBase
second_title: Aspose.Sildes for .NET API संदर्भ
description: IMathElement के लिए बेस क्लास जिसमें सभी विरासत में मिले क्लासों के लिए सामान्य कुछ मेथड्स का कार्यान्वयन शामिल है। केवल आंतरिक उपयोग के लिए। विरासत में मिला क्लास को IMathElement होना चाहिए।
type: docs
weight: 8680
url: /hi/aspose.slides.mathtext/mathelementbase/
---
## MathElementBase वर्ग

IMathElement के लिए बेस क्लास जिसमें सभी विरासत में मिले क्लासों के लिए सामान्य कुछ मेथड्स का कार्यान्वयन शामिल है। केवल आंतरिक उपयोग के लिए। विरासत में मिला क्लास को IMathElement होना चाहिए।

```csharp
public abstract class MathElementBase : IMathElement
```

## विधियाँ

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction)(IMathElement) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_4)(string) | इस उदाहरण को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | इस उदाहरण को तर्क के रूप में उपयोग करके तथा निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | इस उदाहरण को तर्क के रूप में उपयोग करके तथा निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन को लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide)(IMathElement) | इस अंशांश और निर्दिष्ट अंशहर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_2)(string) | इस अंशांश और निर्दिष्ट अंशहर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_1)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के साथ, इस अंशांश और निर्दिष्ट अंशहर का उपयोग करके एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide#divide_3)(string, MathFractionTypes) | निर्दिष्ट प्रकार के साथ, इस अंशांश और निर्दिष्ट अंशहर का उपयोग करके एक भिन्न बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose)() | एक गणितीय तत्व को कोष्ठकों में बंद करता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose#enclose_1)(char, char) | निर्दिष्ट अक्षरों, जैसे कोष्ठक या अन्य अक्षरों के साथ, गणितीय तत्व को फ्रेमिंग के रूप में बंद करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function#function_1)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूह अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral)(MathIntegralTypes) | सीमाओं के बिना समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_3)(MathIntegralTypes, string, string) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | समाकलन लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join#join_1)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary#nary_1)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय जड़ निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical#radical_1)(string) | निर्दिष्ट तर्क से दिए गए घातांक की गणितीय जड़ निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit#setlowerlimit_1)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript#setsubscript_1)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ側 पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | बाएँ側 पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ側 पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | दाएँ側 पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript#setsuperscript_1)(string) | सुपरसक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit#setupperlimit_1)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर अनुकरणकर्ता, संरेखण बिंदु के साथ या बिना, पंक्ति ब्रेक बिंदु के रूप में, या इस तरह समूहित किया जा सकता है कि पंक्ति ब्रेक की अनुमति न मिले। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### देखें

* इंटरफ़ेस [IMathElement](../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
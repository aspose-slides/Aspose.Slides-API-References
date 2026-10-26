---
title: IMathElement
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: किसी भी गणितीय तत्व जैसे भिन्न, गणितीय पाठ, फ़ंक्शन, कई तत्वों वाली अभिव्यक्ति इत्यादि का आधार इंटरफ़ेस
type: docs
weight: 8230
url: /hi/aspose.slides.mathtext/imathelement/
---
## IMathElement इंटरफ़ेस

किसी भी गणितीय तत्व का मूल इंटरफ़ेस: भिन्न, गणितीय पाठ, फ़ंक्शन, कई तत्वों वाला अभिव्यक्ति आदि

```csharp
public interface IMathElement
```

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/imathelement/accent)(char) | इस तत्व के शीर्ष पर एक अक्षर (एक कैरेक्टर) के रूप में एक्सेंट मार्क सेट करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, जिसमें इस इंस्टेंस को तर्क के रूप में उपयोग किया जाता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_1)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को लेता है, जिसमें इस इंस्टेंस को तर्क के रूप में उपयोग किया जाता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_4)(string) | निर्दिष्ट फ़ंक्शन को लेता है, जिसमें इस इंस्टेंस को तर्क के रूप में उपयोग किया जाता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_2)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, जिसमें इस इंस्टेंस को तर्क के रूप में उपयोग किया जाता है तथा निर्दिष्ट अतिरिक्त तर्क भी प्रदान किया जाता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/imathelement/asargumentoffunction#asargumentoffunction_3)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को लेता है, जिसमें इस इंस्टेंस को तर्क के रूप में उपयोग किया जाता है तथा निर्दिष्ट अतिरिक्त तर्क भी प्रदान किया जाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide)(IMathElement) | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_2)(string) | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_1)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/imathelement/divide#divide_3)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose)() | गणितीय तत्व को कोष्ठकों में घेरता है |
| [Enclose](../../aspose.slides.mathtext/imathelement/enclose#enclose_1)(char, char) | इस तत्व को निर्दिष्ट वर्णों (जैसे कोष्ठक या अन्य वर्ण) में फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/imathelement/function#function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/imathelement/function#function_1)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/imathelement/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/imathelement/group#group)() | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करते हुए समूह में रखता है |
| [Group](../../aspose.slides.mathtext/imathelement/group#group_1)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूहिंग वर्ण (जैसे नीचे की कर्ली ब्रैकेट या अन्य) का उपयोग करके समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_1)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_3)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_2)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/imathelement/integral#integral_4)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| [Join](../../aspose.slides.mathtext/imathelement/join#join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Join](../../aspose.slides.mathtext/imathelement/join#join_1)(string) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/imathelement/nary#nary_1)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/imathelement/overbar)() | इस तत्व के शीर्ष पर बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical)(IMathElement) | निर्दिष्ट तर्क से दिये गये घातांक का गणितीय मूल निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/imathelement/radical#radical_1)(string) | निर्दिष्ट तर्क से दिये गये घातांक का गणितीय मूल निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/imathelement/setlowerlimit#setlowerlimit_1)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/imathelement/setsubscript#setsubscript_1)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft#setsubsuperscriptontheleft_1)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/imathelement/setsubsuperscriptontheright#setsubsuperscriptontheright_1)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/imathelement/setsuperscript#setsuperscript_1)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/imathelement/setupperlimit#setupperlimit_1)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/imathelement/toborderbox#toborderbox_1)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/imathelement/tobox)() | इस तत्व को एक गैर-व्यक्त दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर एमुलेटर के रूप में, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है जिससे भीतर लाइन ब्रेक की अनुमति न हो। |
| [ToMathArray](../../aspose.slides.mathtext/imathelement/tomatharray)() | ऊर्ध्वाधर सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/imathelement/underbar)() | इस तत्व के नीचे बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
```

### संबंधित देखें

* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
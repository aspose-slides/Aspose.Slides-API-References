---
title: MathFunction
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक तर्क का फलन निर्दिष्ट करता है।
type: docs
weight: 8720
url: /hi/aspose.slides.mathtext/mathfunction/
---
## MathFunction वर्ग

एक तर्क का फलन निर्दिष्ट करता है।

```csharp
public sealed class MathFunction : MathElementBase, IMathFunction
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathFunction](mathfunction#constructor)(IMathElement, IMathElement) | MathFunction वर्ग का नया उदाहरण आरंभ करता है। |
| [MathFunction](mathfunction#constructor_1)(string, IMathElement) | MathFunction वर्ग का नया उदाहरण आरंभ करता है। |

## गुणधर्म

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathfunction/base) { get; } | फलन तर्क |
| [Name](../../aspose.slides.mathtext/mathfunction/name) { get; } | फलन नाम। उदाहरण के लिए, फलन नाम sin और cos हैं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर का एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक के साथ एक भिन्न बनाता है और निर्दिष्ट हर |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक के साथ एक भिन्न बनाता है और निर्दिष्ट हर |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में गणितीय तत्व को फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathfunction/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे वाले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे वाले कर्ली ब्रैकेट या अन्य ग्रुपिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक रेखा सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए क्रमांक की गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | उपस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | उपस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर उपस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर उपस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर उपस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर उपस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि लाइन ब्रेक की अनुमति न दे। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक रेखा सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathFunction func = new MathFunction("sin", new MathematicalText("x"));
```

### संबंधित

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathFunction](../imathfunction)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: MathLimit
second_title: Aspose.Sildes for .NET API संदर्भ
description: बेसलाइन पर टेक्स्ट और उसके ठीक ऊपर या नीचे छोटे आकार के टेक्स्ट वाले Limit ऑब्जेक्ट को निर्दिष्ट करता है।
type: docs
weight: 8820
url: /hi/aspose.slides.mathtext/mathlimit/
---
## MathLimit क्लास

Specifies the Limit object, consisting of text on the baseline and reduced-size text immediately above or below it.

```csharp
public sealed class MathLimit : MathElementBase, IMathLimit
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathLimit](mathlimit#constructor)(IMathElement, IMathElement) | MathLimit क्लास का नया उदाहरण निचली सीमा के साथ प्रारंभ करता है |
| [MathLimit](mathlimit#constructor_1)(IMathElement, IMathElement, bool) | MathLimit क्लास का नया उदाहरण प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathlimit/base) { get; } | आधार तर्क |
| [Limit](../../aspose.slides.mathtext/mathlimit/limit) { get; } | सीमा तर्क |
| [UpperLimit](../../aspose.slides.mathtext/mathlimit/upperlimit) { get; set; } | ऊपरी या निचली सीमा निर्दिष्ट करता है |

## विधियां

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक उच्चारण चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क का उपयोग करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को लेता है, इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क का उपयोग करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठकों में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेम करके घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathlimit/getchildren)() | संतति तत्वों को प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | निचले कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटेग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | गणितीय पाठ को जोड़ता है और गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है जिसे समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहबद्ध करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) संरेखण बिंदु के साथ या बिना ऑपरेटर अनुकरणकर्ता के रूप में, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक नहीं हो सके। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("𝑛→∞"));
```

### संदर्भ

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathLimit](../imathlimit)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
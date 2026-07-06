---
title: MathRightSubSuperscriptElement
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक सब-सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जो एक बेस और बेस के दाएँ स्थित सबस्क्रिप्ट एवं सुपरस्क्रिप्ट से बना होता है।
type: docs
weight: 8960
url: /hi/aspose.slides.mathtext/mathrightsubsuperscriptelement/
---
## MathRightSubSuperscriptElement क्लास

सब-सुपरस्क्रिप्ट ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक बेस और बेस के दाएँ तरफ स्थित सबस्क्रिप्ट और सुपरस्क्रिप्ट शामिल होते हैं।

```csharp
public sealed class MathRightSubSuperscriptElement : BaseScript, IMathRightSubSuperscriptElement
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathRightSubSuperscriptElement](mathrightsubsuperscriptelement)(IMathElement, IMathElement, IMathElement) | MathRightSubSuperscriptElement क्लास की एक नई इंस्टेंस को प्रारम्भ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlignScripts](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/alignscripts) { get; set; } | सबस्क्रिप्ट/सुपरस्क्रिप्ट की संरेखण को निर्दिष्ट करता है। जब true हो, तो सबस्क्रिप्ट और सुपरस्क्रिप्ट एक-दूसरे के सापेक्ष क्षैतिज रूप से संरेखित होते हैं। जब false हो, तो वे बेस के आकार के अनुसार कर्न किए जाते हैं। डिफ़ॉल्ट मान false है। |
| [Base](../../aspose.slides.mathtext/basescript/base) { get; } | बेस तर्क |
| [Subscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/subscript) { get; } | सबस्क्रिप्ट तर्क |
| [Superscript](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/superscript) { get; } | सुपरस्क्रिप्ट तर्क |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक (न्यूमेरटर) और निर्दिष्ट हर (डिनॉमिनेटर) के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक (न्यूमेरटर) और निर्दिष्ट हर (डिनॉमिनेटर) के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के साथ एक फ्रैक्शन बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathrightsubsuperscriptelement/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | निचले कर्ली ब्रैकेट या अन्य ग्रुपिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटेग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटेग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-वीज़ुअल बॉक्स (तार्किक समूह) में रखता है जो समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या ऐसा समूहित हो सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | उर्ध्वाधर ऐरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के निचले भाग में एक बार सेट करता है |

### उदाहरण

```csharp
[C#]
MathRightSubSuperscriptElement subsuperscript = new MathematicalText("N").SetSubSuperscriptOnTheRight("i", "j");
```

### संबंधित देखें

* क्लास [BaseScript](../basescript)
* इंटरफ़ेस [IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
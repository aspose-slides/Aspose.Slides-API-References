---
title: MathAccent
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक बेस और संयोजित डायक्रिटिकल मार्क से बना एक्सेंट फ़ंक्शन निर्दिष्ट करता है। उदाहरण: ́
type: docs
weight: 8530
url: /hi/aspose.slides.mathtext/mathaccent/
---
## MathAccent क्लास

एक बेस और संयोजित डायक्रिटिकल मार्क से बना एक्सेंट फ़ंक्शन निर्दिष्ट करता है। उदाहरण: 𝑎́

```csharp
public sealed class MathAccent : MathElementBase, IMathAccent
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathAccent](mathaccent#constructor)(IMathElement) | एक निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणित एक्सेंट बनाता है, डिफ़ॉल्ट एक्सेंट कैरेक्टर मान के साथ। |
| [MathAccent](mathaccent#constructor_1)(IMathElement, char) | एक निर्दिष्ट गणितीय तत्व पर लागू होने वाला गणित एक्सेंट बनाता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathaccent/base) { get; } | वह तर्क जिस पर एक्सेंट लागू किया गया था। |
| [Character](../../aspose.slides.mathtext/mathaccent/character) { get; set; } | एक्सेंट कैरेक्टर मान (U+0300–U+036F) या (U+20D0–U+20EF) सीमाओं के भीतर होना चाहिए। डिफ़ॉल्ट मान: संयोजित सर्कमफ़्लेक्स एक्सेंट (U+0302) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक कैरेक्टर)। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, इस अंशांक और निर्दिष्ट हर के साथ। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में संलग्न करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में संलग्न करता है, जैसे कोष्ठक या अन्य फ्रेमिंग अक्षर। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करता है। |
| [GetChildren](../../aspose.slides.mathtext/mathaccent/getchildren)() | संतति तत्व प्राप्त करें। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे के कर्ली ब्रैकेट का प्रयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे के कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का प्रयोग करके इस तत्व को एक समूह में रखता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए क्रम की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए क्रम की गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि लाइनों के भीतर ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक ऊर्ध्वधारा एरे में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("x");
MathAccent accent = new MathAccent(baseElement, '~');
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathAccent](../imathaccent)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
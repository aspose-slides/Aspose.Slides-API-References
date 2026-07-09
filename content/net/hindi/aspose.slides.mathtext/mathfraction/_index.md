---
title: MathFraction
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक फ्रैक्शन ऑब्जेक्ट को निर्दिष्ट करता है जिसमें न्यूमेरेटर और डिनॉमिनेटर होते हैं जो फ्रैक्शन बार द्वारा विभाजित होते हैं। फ्रैक्शन बार फ्रैक्शन गुणों के आधार पर क्षैतिज या विकर्ण हो सकता है। फ्रैक्शन ऑब्जेक्ट का उपयोग स्टैक फ़ंक्शन को दर्शाने के लिए भी किया जाता है, जो एक तत्व को दूसरे के ऊपर रखता है, बिना फ्रैक्शन बार के।
type: docs
weight: 8690
url: /hi/aspose.slides.mathtext/mathfraction/
---
## MathFraction क्लास

एक फ्रैक्शन ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें न्यूमेरेटर और डिनॉमिनेटर होते हैं जो फ्रैक्शन बार द्वारा विभाजित होते हैं। फ्रैक्शन बार क्षैतिज या विकर्ण हो सकता है, यह फ्रैक्शन प्रॉपर्टीज़ पर निर्भर करता है। फ्रैक्शन ऑब्जेक्ट का उपयोग स्टैक फ़ंक्शन को दर्शाने के लिए भी किया जाता है, जो एक एलेमेंट को दूसरे के ऊपर रखता है, बिना फ्रैक्शन बार के।

```csharp
public sealed class MathFraction : MathElementBase, IMathFraction
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MathFraction](mathfraction#constructor)(IMathElement, IMathElement) | 'Bar' प्रकार का MathFraction निर्दिष्ट न्यूमेरेटर और डिनॉमिनेटर के साथ प्रारंभ करता है |
| [MathFraction](mathfraction#constructor_1)(IMathElement, IMathElement, MathFractionTypes) | निर्दिष्ट न्यूमेरेटर, डिनॉमिनेटर और प्रकार के साथ MathFraction को प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Denominator](../../aspose.slides.mathtext/mathfraction/denominator) { get; } | डिनॉमिनेटर |
| [FractionType](../../aspose.slides.mathtext/mathfraction/fractiontype) { get; set; } | फ्रैक्शन प्रकार, डिफ़ॉल्ट: Bar |
| [Numerator](../../aspose.slides.mathtext/mathfraction/numerator) { get; } | न्यूमेरेटर |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस एलेमेंट के शीर्ष पर एक एक्सेंट मार्क (एक अक्षर) सेट करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को आर्ग्युमेंट के रूप में और निर्दिष्ट अतिरिक्त आर्ग्युमेंट को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को आर्ग्युमेंट के रूप में और निर्दिष्ट अतिरिक्त आर्ग्युमेंट को उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का फ्रैक्शन इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का फ्रैक्शन इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय एलेमेंट को कोष्ठकों में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में एक गणितीय एलेमेंट को फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathfraction/getchildren)() | संतान एलेमेंट्स प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रैकेट का उपयोग करके इस एलेमेंट को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | निचले कर्ली ब्रैकेट या अन्य समूहित अक्षर का उपयोग करके इस एलेमेंट को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय एलेमेंट को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय टेक्स्ट को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस एलेमेंट के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्धारित करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री का गणितीय मूल निर्धारित करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस एलेमेंट को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस एलेमेंट को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस एलेमेंट को एक नॉन-विजुअल बॉक्स (तार्किक समूह) में रखता है, जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में काम कर सकता है, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक पॉइंट के रूप में, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस एलेमेंट के नीचे एक बार सेट करता है |

### उदाहरण

```csharp
[C#]
MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathFraction](../imathfraction)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
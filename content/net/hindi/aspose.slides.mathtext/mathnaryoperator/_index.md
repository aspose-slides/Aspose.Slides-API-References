---
title: MathNaryOperator
second_title: Aspose.Sildes for .NET एपीआई संदर्भ
description: एक N-ary गणितीय वस्तु को परिभाषित करता है जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस या ऑपेरेंड, और वैकल्पिक ऊपरी और निचली सीमाओं से बना होता है। N-ary ऑपरेटर्स के उदाहरण हैं Summation, Union, Intersection, Integral
type: docs
weight: 8870
url: /hi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator क्लास

N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस (या operand), और वैकल्पिक ऊपरी और निचली सीमाओं से बना होता है। N-ary ऑपरेटर्स के उदाहरण हैं: Summation, Union, Intersection, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## निर्माणकर्ता

| नाम | विवरण |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | MathNaryOperator क्लास का नया उदाहरण प्रारंभ करता है। |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | MathNaryOperator क्लास का नया उदाहरण प्रारंभ करता है। |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | MathNaryOperator क्लास का नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | बेस तर्क |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | ऑपरेटर वर्ण अपने ऑपरेण्ड की ऊँचाई से मेल खाने के लिए लंबवत रूप से बढ़ता है |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | सबस्क्रिप्ट छुपाएँ |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | सुपरस्क्रिप्ट छुपाएँ |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | सीमाओं (सबस्क्रिप्ट और सुपरस्क्रिप्ट) का स्थान |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Nary ऑपरेटर कैरेक्टर, उदाहरण के लिये: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | एक सबस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिये, इंटेग्रल के मामले में, निचली सीमा सेट करता है |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | एक सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिये, इंटेग्रल के मामले में, ऊपरी सीमा सेट करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के ऊपर एक कैरेक्टर)। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जहाँ यह इंस्टांस तर्क के रूप में प्रयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है जहाँ यह इंस्टांस तर्क के रूप में प्रयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है जहाँ यह इंस्टांस तर्क के रूप में प्रयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जहाँ यह इंस्टांस तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ प्रयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है जहाँ यह इंस्टांस तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क के साथ प्रयोग किया जाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर होता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न बनाता है जिसमें यह न्यूमेरेटर और निर्दिष्ट डिनॉमिनेटर होता है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में संलग्न करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में गणितीय तत्व को संलग्न करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टांस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टांस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | संतान तत्व प्राप्त करें। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहण अक्षर का उपयोग करके इस तत्व को समूह में रखता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गये डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गये डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तर्कसंगत समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिये होता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिये) ऑपरेटर एमुलेटर के रूप में, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक पॉइंट के रूप में, या ऐसा समूहित हो सकता है कि लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathNaryOperator](../imathnaryoperator)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
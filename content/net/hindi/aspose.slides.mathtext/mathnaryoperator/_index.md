---
title: MathNaryOperator
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: N-ary गणितीय वस्तु को निर्दिष्ट करता है जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस या ऑपेरेंड और वैकल्पिक ऊपरी तथा निचली सीमाओं से बना होता है। N-ary ऑपरेटर्स के उदाहरण हैं Summation Union Intersection Integral
type: docs
weight: 8890
url: /hi/aspose.slides.mathtext/mathnaryoperator/
---
## MathNaryOperator क्लास

N-ary गणितीय वस्तु को निर्दिष्ट करता है, जैसे Summation और Integral। यह एक ऑपरेटर, एक बेस (या ऑपेरेंड), और वैकल्पिक ऊपरी तथा निचले सीमाओं से बना होता है। N-ary ऑपरेटरों के उदाहरण हैं: Summation, Union, Intersection, Integral

```csharp
public sealed class MathNaryOperator : MathElementBase, IMathNaryOperator
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathNaryOperator](mathnaryoperator#constructor)(char, IMathElement) | MathNaryOperator class की नई इंस्टेंस को आरंभ करता है। |
| [MathNaryOperator](mathnaryoperator#constructor_1)(char, IMathElement, IMathElement) | MathNaryOperator class की नई इंस्टेंस को आरंभ करता है। |
| [MathNaryOperator](mathnaryoperator#constructor_2)(char, IMathElement, IMathElement, IMathElement) | MathNaryOperator class की नई इंस्टेंस को आरंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathnaryoperator/base) { get; } | बेस तर्क |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathnaryoperator/growtomatchoperandheight) { get; set; } | ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है जिससे यह उसके ऑपेरेंड की ऊँचाई से मेल खाए |
| [HideSubscript](../../aspose.slides.mathtext/mathnaryoperator/hidesubscript) { get; set; } | सबसक्रिप्ट छिपाएँ |
| [HideSuperscript](../../aspose.slides.mathtext/mathnaryoperator/hidesuperscript) { get; set; } | सुपरसक्रिप्ट छिपाएँ |
| [LimitLocation](../../aspose.slides.mathtext/mathnaryoperator/limitlocation) { get; set; } | सीमाओं (सबसक्रिप्ट और सुपरसक्रिप्ट) का स्थान |
| [Operator](../../aspose.slides.mathtext/mathnaryoperator/operator) { get; set; } | Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '∑', '∫' |
| [Subscript](../../aspose.slides.mathtext/mathnaryoperator/subscript) { get; } | सबसक्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा निर्धारित करता है |
| [Superscript](../../aspose.slides.mathtext/mathnaryoperator/superscript) { get; } | सुपरसक्रिप्ट तर्क को निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा निर्धारित करता है |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर का कैरेक्टर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को लेता है जहाँ यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को लेता है जहाँ यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को लेता है जहाँ यह इंस्टेंस तर्क के रूप में उपयोग होता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMMathElement) | निर्दिष्ट फ़ंक्शन को लेता है जहाँ यह इंस्टेंस तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के रूप में उपयोग होता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को लेता है जहाँ यह इंस्टेंस तर्क के रूप में और अतिरिक्त निर्दिष्ट तर्क के रूप में उपयोग होता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरator और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरator और निर्धारित डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह न्यूमेरator और निर्दिष्ट डिनॉमिनेटर होता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह न्यूमेरator और निर्दिष्ट डिनॉमिनेटर होता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में बंद करता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट कैरेक्टर (जैसे कोष्ठक या अन्य कैरेक्टर) में फ्रेम के रूप में बंद करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है जहाँ यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है जहाँ यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [GetChildren](../../aspose.slides.mathtext/mathnaryoperator/getchildren)() | बाल तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है जहाँ समूहन कैरेक्टर (जैसे नीचे की कर्ली ब्रैकेट या अन्य) का उपयोग किया जाता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMMathElement) | निर्दिष्ट तर्क से दिए गये डिग्री का गणितीय मूल निर्धारित करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गये डिग्री का गणितीय मूल निर्धारित करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMMathElement) | सबसक्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMMathElement, IMMathElement) | बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMMathElement, IMMathElement) | दाईं ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाईं ओर सबसक्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMMathElement) | सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर- दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहबद्ध करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित हो सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक वर्टिकल ऐरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathNaryOperator naryOperator = new MathematicalText("x").Nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```

### संबंधित

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathNaryOperator](../imathnaryoperator)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
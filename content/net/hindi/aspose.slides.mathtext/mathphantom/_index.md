---
title: MathPhantom
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक phantom गणितीय वस्तु ltmphantgt का प्रतिनिधित्व करता है जो अपने चाइल्ड एलिमेंट के लेआउट को प्रभावित करता है बिना आवश्यक रूप से इसे प्रदर्शित किए। एक phantom अपने बेस अभिव्यक्ति को छुपा सकता है जबकि उसकी चौड़ाई, ऊँचाई या गहराई को बनाए रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार Show, ZeroWid, ZeroAsc, ZeroDesc और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित होते हैं।
type: docs
weight: 8940
url: /hi/aspose.slides.mathtext/mathphantom/
---
## MathPhantom वर्ग

एक phantom गणितीय वस्तु (&lt;m:phant&gt;) का प्रतिनिधित्व करता है जो अपने चाइल्ड तत्व के लेआउट को प्रभावित करती है बिना आवश्यक रूप से इसे प्रदर्शित किए। एक phantom अपने बेस अभिव्यक्ति को छुपा सकता है जबकि उसकी चौड़ाई, ऊँचाई, या गहराई को बनाए रखता है ताकि समीकरणों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | निम्नलिखित निर्दिष्ट बेस गणितीय तत्व का उपयोग करके [`MathPhantom`](../mathphantom) वर्ग का नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | बेस तर्क |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि बेस तत्व प्रदर्शित है या नहीं। |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि phantom वर्ग-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं। |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि बेस तत्व की आरोह (baseline के ऊपर ऊँचाई) को शून्य माना जाना चाहिए या नहीं। |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि बेस तत्व का अवरोह (baseline के नीचे गहराई) को शून्य माना जाना चाहिए या नहीं। |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | एक मान प्राप्त या सेट करता है जो दर्शाता है कि बेस तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक अक्षर)। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें इस उदाहरण को तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है जिसमें इस उदाहरण को तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है जिसमें इस उदाहरण को तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है जिसमें इस उदाहरण को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग किया जाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक के साथ और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक के साथ और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर शामिल है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है जिसमें यह अंशांक और निर्दिष्ट हर शामिल है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में संलग्न करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में संलग्न करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है जिसमें इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग किया जाता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है जिसमें इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग किया जाता है। |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | बच्चा तत्व प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रीकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | एक समूह बनाती है जिसमें इस तत्व को समूहित अक्षर (जैसे निचला कर्ली ब्रीकेट या अन्य) का उपयोग किया जाता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | एक सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | एक सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएं तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएं तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएं तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएं तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | एक सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | एक सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर एम्युलेटर के रूप में कार्य कर सकता है जिसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस तरह समूहित हो सकता है कि इसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // सामग्री को छुपाएँ
phantom.ZeroWidth = false;     // चौड़ाई बनाए रखें
```

### देखें भी

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathPhantom](../imathphantom)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
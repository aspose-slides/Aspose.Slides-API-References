---
title: MathPhantom
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक phantom गणित वस्तु (ltmphantgt) का प्रतिनिधित्व करता है जो अपने चाइल्ड एलिमेंट के लेआउट को प्रभावित करता है बिना आवश्यक रूप से उसे प्रदर्शित किए। एक phantom उसके बेस अभिव्यक्ति को छिपा सकता है जबकि उसकी चौड़ाई, ऊँचाई या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।
type: docs
weight: 8920
url: /hi/aspose.slides.mathtext/mathphantom/
---
## MathPhantom वर्ग

एक phantom गणित ऑब्जेक्ट (&lt;m:phant&gt;) का प्रतिनिधित्व करता है जो अपने चाइल्ड एलिमेंट के लेआउट को प्रभावित करता है बिना आवश्यक रूप से उसे प्रदर्शित किए। एक phantom उसके बेस अभिव्यक्ति को छिपा सकता है जबकि उसकी चौड़ाई, ऊँचाई, या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टीज़ द्वारा नियंत्रित किया जाता है।

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | निर्दिष्ट बेस गणित एलिमेंट का उपयोग करके [`MathPhantom`](../mathphantom) वर्ग का एक नया उदाहरण आरंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | बेस तर्क |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि बेस एलिमेंट प्रदर्शित है या नहीं। |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि phantom क्लास-आधारित स्पेसिंग नियमों के लिए पारदर्शी है या नहीं। |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि बेस एलिमेंट की एसेंट (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं। |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि बेस एलिमेंट की डिसेंट (बेसलाइन के नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं। |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | एक मान प्राप्त करता है या सेट करता है जो यह दर्शाता है कि बेस एलिमेंट की चौड़ाई को शून्य माना जाना चाहिए या नहीं। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस एलिमेंट के शीर्ष पर एक आवाज़ चिन्ह (एक अक्षर) सेट करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग किया जाता है और अतिरिक्त तर्क निर्दिष्ट किया जाता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है जिसमें यह इंस्टेंस तर्क के रूप में उपयोग किया जाता है और अतिरिक्त तर्क संकेतित स्ट्रिंग है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय एलिमेंट को कोष्ठक में बंद करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय एलिमेंट को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में बंद करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | संतान एलिमेंट्स प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रैकेट का उपयोग करके इस एलिमेंट को समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | निचले कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस एलिमेंट को समूह में रखता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय एलिमेंट को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय टेक्स्ट को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस एलिमेंट के शीर्ष पर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाईं ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाईं ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाईं ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाईं ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस एलिमेंट को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस एलिमेंट को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस एलिमेंट को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण के घटकों या अन्य गणितीय टेक्स्ट के उदाहरण को समूहित करने के लिए किया जाता है। एक बॉक्सड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में सेवा दे सकता है, लाइन-ब्रेक बिंदु हो या न हो, या ऐसी तरह समूहित किया जा सकता है कि उसके भीतर लाइन-ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस एलिमेंट के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // सामग्री को छिपाएँ
phantom.ZeroWidth = false;     // चौड़ाई बनाए रखें
```

### संबंधित देखें

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathPhantom](../imathphantom)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ऐसेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
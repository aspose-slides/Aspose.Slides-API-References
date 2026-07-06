---
title: MathPhantom
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक phantom गणितीय ऑब्जेक्ट (ltmphantgt) को दर्शाता है जो अपने बाल तत्व के लेआउट को प्रभावित करता है, भले ही इसे आवश्यक रूप से प्रदर्शित न किया जाए। एक phantom अपने मूल अभिव्यक्ति को छिपा सकता है जबकि उसकी चौड़ाई, ऊँचाई या गहराई को संरक्षित रखता है ताकि सूत्रों को संरेखित किया जा सके या स्थान आरक्षित किया जा सके। दृश्यता और ज्यामिति व्यवहार को Show, ZeroWid, ZeroAsc, ZeroDesc, और Transp जैसी प्रॉपर्टियों द्वारा नियंत्रित किया जाता है।
type: docs
weight: 8920
url: /hi/aspose.slides.mathtext/mathphantom/
---
## MathPhantom वर्ग

Represents a phantom math object (&lt;m:phant&gt;) that affects the layout of its child element without necessarily displaying it. A phantom can hide its base expression while preserving its width, height, or depth to align formulas or reserve space. Visibility and geometry behavior are controlled by properties such as Show, ZeroWid, ZeroAsc, ZeroDesc, and Transp.

```csharp
public sealed class MathPhantom : MathElementBase, IMathPhantom
```

## निर्माताओं

| नाम | विवरण |
| --- | --- |
| [MathPhantom](mathphantom)(IMathElement) | निर्दिष्ट बेस गणितीय तत्व का उपयोग करके [`MathPhantom`](../mathphantom) वर्ग का एक नया इंस्टेंस प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathphantom/base) { get; } | मूल तर्क |
| [Show](../../aspose.slides.mathtext/mathphantom/show) { get; set; } | मूल तत्व प्रदर्शित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [Transp](../../aspose.slides.mathtext/mathphantom/transp) { get; set; } | कक्षा-आधारित स्पेसिंग नियमों के लिए phantom पारदर्शी है या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [ZeroAsc](../../aspose.slides.mathtext/mathphantom/zeroasc) { get; set; } | मूल तत्व की आरोह (बेसलाइन के ऊपर की ऊँचाई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [ZeroDesc](../../aspose.slides.mathtext/mathphantom/zerodesc) { get; set; } | मूल तत्व की अवरोह (बेसलाइन के नीचे की गहराई) को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |
| [ZeroWidth](../../aspose.slides.mathtext/mathphantom/zerowidth) { get; set; } | मूल तत्व की चौड़ाई को शून्य माना जाना चाहिए या नहीं, यह दर्शाने वाला मान प्राप्त करता है या सेट करता है। |

## विधियां

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के ऊपर एक एक्सेंट चिह्न (एक अक्षर) सेट करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को प्रयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को प्रयोग करके निर्दिष्ट फ़ंक्शन लेता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरटर और निर्दिष्ट डिनॉमीनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरटर और निर्दिष्ट डिनॉमीनेटर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, जिसमें यह न्यूमेरटर और निर्दिष्ट डिनॉमीनेटर होते हैं। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न बनाता है, जिसमें यह न्यूमेरटर और निर्दिष्ट डिनॉमीनेटर होते हैं। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में घेरता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | किसी गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में घेरता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathphantom/getchildren)() | संतान तत्व प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिए किया जाता है। एक बॉक्सेड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

```csharp
[C#]
IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
phantom.Show = false;          // सामग्री को छिपाएँ
phantom.ZeroWidth = false;     // चौड़ाई बनाए रखें
```

### संबंधित देखें

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathPhantom](../imathphantom)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
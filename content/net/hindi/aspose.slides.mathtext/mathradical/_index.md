---
title: MathRadical
second_title: Aspose.Sildes for .NET एपीआई संदर्भ
description: रैडिकल फ़ंक्शन को निर्दिष्ट करता है जो एक बेस और एक वैकल्पिक डिग्री से बना होता है। रैडिकल ऑब्जेक्ट का उदाहरण है ।
type: docs
weight: 8940
url: /hi/aspose.slides.mathtext/mathradical/
---
## MathRadical क्लास

रैडिकल फ़ंक्शन को निर्दिष्ट करता है, जिसमें एक बेस और एक वैकल्पिक डिग्री होती है। रैडिकल ऑब्जेक्ट का उदाहरण √𝑥 है।

```csharp
public sealed class MathRadical : MathElementBase, IMathRadical
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MathRadical](mathradical)(IMathElement, IMathElement) | MathRadical क्लास की नई इंस्टेंस को प्रारम्भ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathradical/base) { get; } | Base तर्क |
| [Degree](../../aspose.slides.mathtext/mathradical/degree) { get; } | Degree तर्क |
| [HideDegree](../../aspose.slides.mathtext/mathradical/hidedegree) { get; set; } | Hide degree जब true हो, डिग्री नहीं दिखती, जैसा कि √𝑥 में |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करते हुए निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करते हुए निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करते हुए निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करते हुए निर्दिष्ट अतिरिक्त आर्ग्युमेंट के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को आर्ग्युमेंट के रूप में उपयोग करते हुए निर्दिष्ट अतिरिक्त आर्ग्युमेंट के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक के साथ एक भिन्न बनाता है और निर्दिष्ट हर |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक के साथ एक भिन्न बनाता है और निर्दिष्ट हर |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न बनाता है इस अंशांक और निर्दिष्ट हर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathradical/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे की कर्ली ब्रेस का उपयोग करके एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | एक ग्रुपिंग कैरेक्टर (जैसे नीचे की कर्ली ब्रेस या अन्य) का उपयोग करके इस तत्व को समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएं ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि लाइन ब्रेकों की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक वर्टिकल एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

```csharp
[C#]
MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathRadical](../imathradical)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: MathGroupingCharacter
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक अभिव्यक्ति के ऊपर या नीचे समूह प्रतीक को निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए
type: docs
weight: 8760
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter क्लास

एक अभिव्यक्ति के ऊपर या नीचे एक समूह चिन्ह को निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## निर्माता

| Name | Description |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है जिसमें डिफ़ॉल्ट समूह चिन्ह U+23DF (BOTTOM CURLY BRACKET) है |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | MathGroupingCharacter क्लास का नया उदाहरण आरंभ करता है। |

## गुण

| Name | Description |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | आधार तर्क |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | समूह चिन्ह डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | समूह चिन्ह की स्थिति। डिफ़ॉल्ट: नीचे |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | समूह चिन्ह की लंबवत अनुशासन। यह वस्तु को बेसलाइन के सापेक्ष संरेखित करने का निर्धारण करता है। उदाहरण के तौर पर, जब समूह चिन्ह वस्तु के ऊपर हो, तो Top की VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर स्थित है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का नीचे बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिये Bottom, और Position=Bottom के लिये Top |

## विधियाँ

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक accent mark सेट करता है (इस तत्व के शीर्ष पर एक char) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस instance को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस instance को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस instance को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस numerator और निर्दिष्ट denominator के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस numerator और निर्दिष्ट denominator के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की fraction को इस numerator और निर्दिष्ट denominator के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की fraction को इस numerator और निर्दिष्ट denominator के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में गणितीय तत्व को फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस instance को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस instance को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है, जिसमें नीचे की कर्ली ब्रैकेट या अन्य समूह चिन्ह जैसे char का उपयोग किया जाता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकलन लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | दिए गए डिग्री की गणितीय मूल को निर्दिष्ट तर्क से निर्धारित करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | दिए गए डिग्री की गणितीय मूल को निर्दिष्ट तर्क से निर्धारित करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | एक subscript बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | एक subscript बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएं ओर subscript और superscript बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएं ओर subscript और superscript बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएं ओर subscript और superscript बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएं ओर subscript और superscript बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | एक superscript बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | एक superscript बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को border-box में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को border-box में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक non-visual बॉक्स (तार्किक समूह) में रखता है, जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग होता है। एक boxed object (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, जिसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में उपयोग हो सकता है, या इस प्रकार समूहित किया जा सकता है कि भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathGroupingCharacter](../imathgroupingcharacter)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
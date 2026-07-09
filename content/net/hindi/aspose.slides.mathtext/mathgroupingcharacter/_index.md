---
title: MathGroupingCharacter
second_title: Aspose.Sildes for .NET API संदर्भ
description: अभिव्यक्ति के ऊपर या नीचे एक समूह चिन्ह निर्धारित करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए
type: docs
weight: 8760
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/
---
## MathGroupingCharacter क्लास

एक अभिव्यक्ति के ऊपर या नीचे समूह चिन्ह निर्दिष्ट करता है, आमतौर पर तत्वों के बीच संबंध को उजागर करने के लिए

```csharp
public sealed class MathGroupingCharacter : MathElementBase, IMathGroupingCharacter
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathGroupingCharacter](mathgroupingcharacter#constructor)(IMathElement) | डिफ़ॉल्ट समूह चिन्ह U+23DF (BOTTOM CURLY BRACKET) के साथ MathGroupingCharacter क्लास का नया उदाहरण प्रारंभ करता है |
| [MathGroupingCharacter](mathgroupingcharacter#constructor_1)(IMathElement, char, MathTopBotPositions, MathTopBotPositions) | MathGroupingCharacter क्लास का नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [Base](../../aspose.slides.mathtext/mathgroupingcharacter/base) { get; } | बेस आर्ग्युमेंट |
| [Character](../../aspose.slides.mathtext/mathgroupingcharacter/character) { get; set; } | समूह चिन्ह डिफ़ॉल्ट मान: U+23DF (BOTTOM CURLY BRACKET) |
| [Position](../../aspose.slides.mathtext/mathgroupingcharacter/position) { get; set; } | समूह चिन्ह की स्थिति। डिफ़ॉल्ट: नीचे |
| [VerticalJustification](../../aspose.slides.mathtext/mathgroupingcharacter/verticaljustification) { get; set; } | समूह चिन्ह का ऊर्ध्वाधर संरेखण। वस्तु के बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह चिन्ह वस्तु के ऊपर हो, तो Top का VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर है; जब Bottom सेट किया जाता है, तो वस्तु का तल बेसलाइन पर होता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के शीर्ष पर एक एक्सेंट चिह्न (एक अक्षर) सेट करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस उदाहरण को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस उदाहरण को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस उदाहरण को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस उदाहरण को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त निर्दिष्ट आर्ग्युमेंट लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस उदाहरण को आर्ग्युमेंट के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है और अतिरिक्त निर्दिष्ट आर्ग्युमेंट लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | गणितीय तत्व को विशिष्ट अक्षरों जैसे कोष्ठक या अन्य फ़्रेमिंग अक्षरों में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस उदाहरण को फ़ंक्शन नाम के रूप में उपयोग करके एक आर्ग्युमेंट फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathgroupingcharacter/getchildren)() | बाल तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है, जैसा कि नीचे कर्ली ब्रैकेट या अन्य समूह चिन्ह |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट आर्ग्युमेंट से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | अधोलेख बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | अधोलेख बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ अधोलेख और उपरिलेख बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ अधोलेख और उपरिलेख बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ अधोलेख और उपरिलेख बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ अधोलेख और उपरिलेख बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | उपरिलेख बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | उपरिलेख बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहबद्ध करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है, लाइन ब्रेक बिंदु के साथ या बिना, या ऐसा समूह बना सकता है कि लाइन ब्रेक अनुमत न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के तल पर एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathGroupingCharacter](../imathgroupingcharacter)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
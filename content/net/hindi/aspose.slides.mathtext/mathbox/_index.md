---
title: MathBox
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: गणितीय तत्व की तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में काम कर सकता है या समूहित किया जा सकता है ताकि उसके भीतर लाइन ब्रेक न हो। उदाहरण के लिए, ऑपरेटर को बॉक्स किया जाना चाहिए ताकि लाइन ब्रेक न हों।
type: docs
weight: 8630
url: /hi/aspose.slides.mathtext/mathbox/
---
## MathBox क्लास

गणितीय तत्व की तार्किक बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना कार्य कर सकता है, लाइन ब्रेक बिंदु के रूप में काम कर सकता है, या इस प्रकार समूहित हो सकता है कि उसके भीतर लाइन ब्रेक न हो। उदाहरण के लिए, "==" ऑपरेटर को बॉक्स किया जाना चाहिए ताकि लाइन ब्रेक न हो।

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## निर्माताएँ

| नाम | विवरण |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | निर्दिष्ट तत्व को तर्क के रूप में उपयोग करके MathBox को प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | जब true हो, यह ऑपरेटर एमुलेटर एक संरेखण बिंदु के रूप में काम करता है; अर्थात, अन्य समीकरणों में निर्धारित संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | आधार तर्क |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | डिफरेंशियल जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (जैसे, समाकलन में 𝑑𝑥), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | स्पष्ट ब्रेक यह निर्दिष्ट करता है कि बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है या नहीं, जिससे लाइन बॉक्स की शुरुआत पर ही रैप हो जाती है। यह वर्तमान गणितीय पाठ की लाइन के संरेखण बिंदु के रूप में उपयोग किए जाने वाले पिछले लाइन के ऑपरेटर की संख्या निर्दिष्ट करता है। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | कोई ब्रेक यह गुण बॉक्स ऑब्जेक्ट पर "अभंग" गुण को निर्दिष्ट करता है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर एमुलेटरों के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटरों से मिलकर बनते हैं। जब यह तत्व निर्दिष्ट नहीं किया गया हो, तो बॉक्स के भीतर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | ऑपरेटर एमुलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और एक ऑपरेटर की गुणधर्मों को विरासत में लेती है। इसका अर्थ है, उदाहरण के लिए, कि अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एमुलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक ग्लिफ़ मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='। डिफ़ॉल्ट मान: false |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के शीर्ष पर एक उच्चारण चिह्न (एक अक्षर) निर्धारित करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है और अतिरिक्त निर्दिष्ट तर्क को भी स्वीकार करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है और अतिरिक्त निर्दिष्ट तर्क को भी स्वीकार करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक (न्यूमेरटर) और निर्दिष्ट हर (डिनॉमिनेटर) के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक (न्यूमेरटर) और निर्दिष्ट हर (डिनॉमिनेटर) के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के आधार पर एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंशांक और निर्दिष्ट हर के आधार पर एक भिन्न बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठक में संलग्न करता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) के साथ गणितीय तत्व को फ्रेमिंग के रूप में संलग्न करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | संतान तत्वों को प्राप्त करें |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकलन लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकलन लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | अधिलेख बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | अधिलेख बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ पक्ष में अधिलेख और ऊपर के लेख बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ पक्ष में अधिलेख और ऊपर के लेख बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ पक्ष में अधिलेख और ऊपर के लेख बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ पक्ष में अधिलेख और ऊपर के लेख बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | ऊपर के लेख बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | ऊपर के लेख बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरणों को समूहित करने के लिये किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिये) ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में या समूहित हो सकता है ताकि उसके भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

Example:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBox](../imathbox)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
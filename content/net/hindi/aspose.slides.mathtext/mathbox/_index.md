---
title: MathBox
second_title: Aspose.Sildes for .NET API संदर्भ
description: गणितीय तत्व की तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है, चाहे उसमें संरेखण बिंदु हो या न हो, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि बॉक्स के भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के लिए, ऑपरेटर को बॉक्स किया जाना चाहिए ताकि लाइन ब्रेक न हों।
type: docs
weight: 8630
url: /hi/aspose.slides.mathtext/mathbox/
---
## MathBox क्लास

Specifies the logical boxing (packaging) of mathematical element. For example, a boxed object can serve as an operator emulator with or without an alignment point, serve as a line break point, or be grouped such as not to allow line breaks within. For example, the "==" operator should be boxed to prevent line breaks.

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## निर्माणकर्ता

| नाम | विवरण |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | निर्दिष्ट तत्व को तर्क के रूप में उपयोग करके MathBox को प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | जब true हो, यह ऑपरेटर एम्यूलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात्, अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | आधार तर्क |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | डिफरेंशियल। जब true हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (जैसे, 𝑑𝑥 एक इंटीग्रैंड में), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज अंतराल प्राप्त करता है। डिफ़ॉल्ट: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | स्पष्ट ब्रेक यह निर्दिष्ट करता है कि क्या बॉक्स वस्तु की शुरुआत में एक लाइन ब्रेक है, जिससे लाइन बॉक्स वस्तु की शुरुआत पर ही मोड़ती है। यह गणितीय पाठ की पिछली पंक्ति में ऑपरेटर की संख्या निर्दिष्ट करता है जिसे वर्तमान पंक्ति के गणितीय पाठ के संरेखण बिंदु के रूप में उपयोग किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | नो ब्रेक। यह गुण बॉक्स वस्तु पर "unbreakable" गुण को निर्दिष्ट करता है। जब true हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह कई बाइनरी ऑपरेटरों वाले ऑपरेटर एम्यूलेटरों के लिए महत्वपूर्ण हो सकता है। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के भीतर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | ऑपरेटर एम्यूलेटर। जब true हो, बॉक्स और उसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती है और ऑपरेटर की गुणधर्मों को विरासत में मिलती है। इसका अर्थ है, उदाहरण के लिए, कि यह अक्षर लाइन ब्रेक के बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एम्यूलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट चिह्न सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को लेकर लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में घेरता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में फ्रेमिंग के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | संतति (चाइल्ड) तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | निचले कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | एक समूहिंग अक्षर जैसे निचला कर्ली ब्रैकेट या अन्य का उपयोग करके इस तत्व को समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक्स बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक्स बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल को निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को एक बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है, चाहे उसमें संरेखण बिंदु हो या न हो, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि बॉक्स के भीतर कोई लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक ऊर्ध्वाधर एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBox](../imathbox)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ऐसेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
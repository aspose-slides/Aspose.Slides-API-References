---
title: MathBox
second_title: Aspose.Sildes for .NET API संदर्भ
description: गणितीय तत्व की तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एम्यूलेटर के रूप में काम कर सकता है, चाहे वह संरेखण बिंदु के साथ हो या बिना, इसे लाइन ब्रेक बिंदु के रूप में उपयोग किया जा सकता है, या इसे इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। उदाहरण के लिए, ऑपरेटर को बॉक्स्ड किया जाना चाहिए ताकि लाइन ब्रेक रोका जा सके।
type: docs
weight: 8650
url: /hi/aspose.slides.mathtext/mathbox/
---
## MathBox क्लास

गणितीय तत्व की तर्कसंगत बॉक्सिंग (पैकेजिंग) को निर्दिष्ट करता है। उदाहरण के लिए, एक बॉक्स्ड ऑब्जेक्ट ऑपरेटर एमीयुलेटर के रूप में उपयोग किया जा सकता है, चाहे वह संरेखण बिंदु के साथ हो या बिना, इसे एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इसे इस तरह समूहित किया जा सकता है कि उसके अंदर लाइन ब्रेक न हो। उदाहरण के लिए, "==" ऑपरेटर को बॉक्स्ड किया जाना चाहिए ताकि लाइन ब्रेक रोका जा सके।

```csharp
public sealed class MathBox : MathElementBase, IMathBox
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathBox](mathbox)(IMathElement) | निर्दिष्ट तत्व को तर्क के रूप में लेकर MathBox को आरंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [AlignmentPoint](../../aspose.slides.mathtext/mathbox/alignmentpoint) { get; set; } | जब सत्य हो, यह ऑपरेटर एमीयुलेटर एक संरेखण बिंदु के रूप में कार्य करता है; अर्थात् अन्य समीकरणों में निर्दिष्ट संरेखण बिंदुओं को इसके साथ संरेखित किया जा सकता है। डिफ़ॉल्ट: false |
| [Base](../../aspose.slides.mathtext/mathbox/base) { get; } | आधार तर्क |
| [Differential](../../aspose.slides.mathtext/mathbox/differential) { get; set; } | डिफरेंशियल जब सत्य हो, बॉक्स एक डिफरेंशियल के रूप में कार्य करता है (जैसे, समाकलन में 𝑑𝑥), और गणितीय डिफरेंशियल के लिए उपयुक्त क्षैतिज स्पेसिंग प्राप्त करता है। डिफ़ॉल्ट: false |
| [ExplicitBreak](../../aspose.slides.mathtext/mathbox/explicitbreak) { get; set; } | स्पष्ट ब्रेक यह निर्दिष्ट करता है कि क्या बॉक्स ऑब्जेक्ट की शुरुआत में लाइन ब्रेक है, जिससे लाइन बॉक्स ऑब्जेक्ट की शुरुआत पर विभाजित हो। यह पिछले गणितीय पंक्ति में ऑपरेटर की संख्या को निर्दिष्ट करता है जिसका उपयोग वर्तमान पंक्ति के संरेखण बिंदु के रूप में किया जाएगा। संभावित मान: 1..255 डिफ़ॉल्ट: 0 (कोई स्पष्ट ब्रेक नहीं) |
| [NoBreak](../../aspose.slides.mathtext/mathbox/nobreak) { get; set; } | कोई ब्रेक नहीं यह प्रॉपर्टी बॉक्स ऑब्जेक्ट पर "अविभाज्य" गुण को निर्दिष्ट करती है। जब सत्य हो, बॉक्स के भीतर कोई लाइन ब्रेक नहीं हो सकता। यह उन ऑपरेटर एमीयुलेटर के लिए महत्वपूर्ण हो सकता है जो एक से अधिक बाइनरी ऑपरेटर से बनते हैं। जब यह तत्व निर्दिष्ट नहीं किया जाता, तो बॉक्स के भीतर ब्रेक हो सकते हैं। डिफ़ॉल्ट: true |
| [OperatorEmulator](../../aspose.slides.mathtext/mathbox/operatoremulator) { get; set; } | ऑपरेटर एमीयुलेटर। जब सत्य हो, बॉक्स और इसकी सामग्री एकल ऑपरेटर की तरह व्यवहार करती हैं और एक ऑपरेटर के गुणों को विरासत में लेती हैं। इसका अर्थ है कि, उदाहरण के लिए, यह अक्षर लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है और अन्य ऑपरेटरों के साथ संरेखित किया जा सकता है। ऑपरेटर एमीयुलेटर अक्सर तब उपयोग होते हैं जब एक या अधिक glyph मिलकर एक ऑपरेटर बनाते हैं, जैसे '=='. डिफ़ॉल्ट मान: false |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्धारित फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्धारित फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्धारित फ़ंक्शन को इस इंस्टेंस को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में लेकर लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्धारित फ़ंक्शन को इस इंस्टेंस को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में लेकर लेता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के एक भिन्न को इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार के एक भिन्न को इस न्यूमेरटर और निर्दिष्ट डिनॉमिनेटर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में बंद करता है |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों में बंद करता है जैसे कोष्ठक या अन्य अक्षर फ़्रेमिंग हेतु |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है जिसमें यह इंस्टेंस फ़ंक्शन नाम के रूप में उपयोग होता है |
| [GetChildren](../../aspose.slides.mathtext/mathbox/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे के कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है समूहिंग अक्षर जैसे नीचे कर्ली ब्रैकेट या अन्य का उपयोग करके |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए क्रम का गणितीय मूल निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए क्रम का गणितीय मूल निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ पर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्य बॉक्स (तर्कसंगत समूह) में रखता है जो समीकरण के घटकों या अन्य गणितीय पाठ के उदाहरण को समूहित करने के लिए उपयोग होता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमीयुलेटर के रूप में कार्य कर सकता है, चाहे वह संरेखण बिंदु के साथ हो या बिना, इसे एक लाइन ब्रेक बिंदु के रूप में काम कर सकता है, या इसे इस तरह समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
MathBox box = new MathBox(new MathematicalText("=="));
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathBox](../imathbox)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
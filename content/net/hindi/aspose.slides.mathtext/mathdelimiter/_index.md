---
title: MathDelimiter
second_title: Aspose.Sildes for .NET API संदर्भ
description: डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जो खोलने और बंद करने वाले वर्णों जैसे कोष्टक, ब्रेसेस, ब्रैकेट और लम्बवत बारों से बना होता है, और एक या अधिक गणितीय तत्वों को भीतर रखता है जो एक निर्दिष्ट वर्ण द्वारा अलग किए जाते हैं। उदाहरण 2 2x7C2
type: docs
weight: 8650
url: /hi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter वर्ग

निर्देशित करता है डिलिमिटर ऑब्जेक्ट को, जिसमें खोलने और बंद करने वाले वर्ण (जैसे ब्रेस, कर्ली ब्रेसेस, कोष्ठक, और लम्बवत बार) होते हैं, और एक या अधिक गणितीय तत्व अंदर होते हैं, जो एक निर्दिष्ट वर्ण द्वारा अलग किए जाते हैं। उदाहरण: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## कंस्ट्रक्टर

| नाम | विवरण |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | निर्दिष्ट तत्व के साथ MathDelimiter को एकल बेस तर्क के रूप में प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | डिलिमिटर वर्णों द्वारा विभाजित एक या अधिक गणितीय तत्व |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character प्रारंभिक, यानी खोलने वाले डिलिमिटर वर्ण को निर्दिष्ट करता है। गणितीय डिलिमिटर वे संलग्न वर्ण होते हैं जैसे कोष्ठक, कोष्ठक और कर्ली ब्रेकेट। डिफ़ॉल्ट: '('। |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered होता है, तो डिलिमिटर गणितीय पाठ की अक्ष के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई में फिट होने के लिए समायोजित रहते हैं। जब MathDelimiterShape.Match होता है, तो उनकी ऊँचाई और आकार समान रूप से उनकी सामग्री के साथ मेल खाने के लिए बदल दिया जाता है। |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character समाप्ति, यानी बंद करने वाले डिलिमिटर वर्ण को निर्दिष्ट करता है। गणितीय डिलिमिटर वे संलग्न वर्ण होते हैं जैसे कोष्ठक, कोष्ठक और कर्ली ब्रेकेट। डिफ़ॉल्ट: ')'. |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true होता है, तो डिलिमिटर अपने ऑपेरेंड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ते हैं। डिफ़ॉल्ट मान true है। |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करने वाले वर्ण को निर्दिष्ट करता है। डिफ़ॉल्ट: '&#x7C;'. |

## विधियां

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के शीर्ष पर एक वर्ण) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन लेता है, इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | निर्दिष्ट डिलिमिटर वर्ण का उपयोग करके तर्कों को सीमित करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिकर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस न्यूमेरटर और निर्दिष्ट डिनॉमिकर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न बनाता है इस न्यूमेरटर और निर्दिष्ट डिनॉमिकर के साथ |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की भिन्न बनाता है इस न्यूमेरटर और निर्दिष्ट डिनॉमिकर के साथ |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में भर देता है |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | एक गणितीय तत्व को निर्दिष्ट वर्णों में भरता है जैसे कोष्ठक या अन्य वर्ण ढाँचे के रूप में |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | एक तर्क का फ़ंक्शन लेता है, इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | संतान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | इस तत्व को नीचे कर्ली ब्रैकेट का उपयोग करके समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | इस तत्व को समूह में रखता है एक समूह वर्ण जैसे नीचे कर्ली ब्रैकेट या अन्य का उपयोग करके |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री की गणितीय मूल को निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरस्क्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरस्क्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर- दृश्य बॉक्स (तार्किक समूह) में रखता है जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर इम्यूलेटर के रूप में काम कर सकता है, संरेखन बिंदु के साथ या बिना, लाइन ब्रेक बिंदु के रूप में, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### देखें भी

* वर्ग [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathDelimiter](../imathdelimiter)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
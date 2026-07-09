---
title: MathDelimiter
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें कोष्ठक, कर्ली ब्रेसेस, ब्रेस्केट और वर्टिकल बार जैसे आरंभ और समाप्ति अक्षर होते हैं, और एक या अधिक गणितीय तत्व अंदर होते हैं, जो एक निर्दिष्ट अक्षर द्वारा अलग किए गए होते हैं। उदाहरण: 2 2x7C2
type: docs
weight: 8650
url: /hi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter क्लास

डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें आरंभी और समाप्ति अक्षर होते हैं (जैसे कोष्टक, कर्ली ब्रेसेस, ब्रेस्केट्स, और वर्टिकल बार), और एक या अधिक गणितीय तत्व अंदर होते हैं, जिन्हें एक निर्दिष्ट अक्षर द्वारा अलग किया जाता है। उदाहरण: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## निर्माता

| नाम | विवरण |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | निर्दिष्ट तत्व को एकल बेस तर्क के रूप में उपयोग कर MathDelimiter को प्रारंभ करता है |

## गुण

| नाम | विवरण |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | डिलिमिटर अक्षरों द्वारा अलग किए गए एक या अधिक गणितीय तत्व |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character प्रारम्भ, यानी खोलने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वह समावेशी अक्षर होते हैं जैसे कोष्टक, ब्रेस्केट, और ब्रेसेस। डिफ़ॉल्ट: '(' |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब मान MathDelimiterShape.Centered है, तो डिलिमिटर गणितीय पाठ की धुरी के चारों ओर केंद्रित होते हैं और उनकी सामग्री की पूरी ऊँचाई के अनुसार समायोजित होते हैं। जब मान MathDelimiterShape.Match है, तो उनकी ऊँचाई और आकार को ठीक उसी प्रकार बदल दिया जाता है जैसा कि उनकी सामग्री है। |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character समाप्ति, यानी बंद करने वाले डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वह समावेशी अक्षर होते हैं जैसे कोष्टक, ब्रेस्केट, और ब्रेसेस। डिफ़ॉल्ट: ')' |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | BeginningCharacter, SeparatorCharacter, EndingCharacter के वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलिमिटर ऊर्ध्वाधर रूप से बढ़कर अपने ऑपरेण्ड की ऊँचाई के अनुरूप हो जाते हैं। डिफ़ॉल्ट मान true है। |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करने वाले अक्षर को निर्दिष्ट करता है। डिफ़ॉल्ट: '&#x7C;' |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के ऊपर एक उच्चार चिह्न (एक अक्षर) सेट करता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क को लेकर निर्दिष्ट फ़ंक्शन लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क को लेकर निर्दिष्ट फ़ंक्शन लेता है |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमित करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक के साथ और निर्दिष्ट हर (डिनॉमिनेटर) के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक के साथ और निर्दिष्ट हर के साथ एक फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | इस अंशांक और निर्दिष्ट हर के साथ निर्दिष्ट प्रकार का फ्रैक्शन बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | इस अंशांक और निर्दिष्ट हर के साथ निर्दिष्ट प्रकार का फ्रैक्शन बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्टक में संलग्न करता है |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | कोष्टक या अन्य अक्षरों जैसे निर्दिष्ट अक्षरों में एक गणितीय तत्व को फ्रेम के रूप में संलग्न करता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क का फ़ंक्शन लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | संतति तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे के कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | समाकल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | समाकल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल (रूट) निर्दिष्ट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल (रूट) निर्दिष्ट करता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपर्सक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपर्सक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-त्रिप्त बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिये किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर इम्यूलेटर के रूप में कार्य कर सकता है जिसमें संरेखण बिंदु हो या न हो, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित हो सकता है कि भीतर लाइन ब्रेक की अनुमति न हो |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत एरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### संदर्भ देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathDelimiter](../imathdelimiter)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
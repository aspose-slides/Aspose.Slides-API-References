---
title: MathDelimiter
second_title: Aspose.Sildes for .NET API संदर्भ
description: डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है जिसमें कोष्ठक, ब्रेस, ब्रैकेट और वर्टिकल बार जैसे शुरुआती और समाप्ति अक्षर होते हैं और एक या अधिक गणितीय तत्वों को निर्दिष्ट अक्षर द्वारा अलग किया जाता है। उदाहरण 2 2x7C2
type: docs
weight: 8670
url: /hi/aspose.slides.mathtext/mathdelimiter/
---
## MathDelimiter क्लास

डिलिमिटर ऑब्जेक्ट को निर्दिष्ट करता है, जो शुरुआती और समाप्ति अक्षरों (जैसे कोष्ठक, ब्रेस, ब्रैकेट और वर्टिकल बार) से बना होता है, और एक या अधिक गणितीय तत्वों को भीतर रखता है, जो एक निर्दिष्ट अक्षर द्वारा अलग किए जाते हैं। उदाहरण: (𝑥2); [𝑥2&#x7C;𝑦2]

```csharp
public sealed class MathDelimiter : MathElementBase, IMathDelimiter
```

## निर्माता

| Name | Description |
| --- | --- |
| [MathDelimiter](mathdelimiter)(IMathElement) | MathDelimiter को निर्दिष्ट तत्व के साथ एकल बेस आर्ग्यूमेंट के रूप में प्रारंभ करता है |

## गुण

| Name | Description |
| --- | --- |
| [Arguments](../../aspose.slides.mathtext/mathdelimiter/arguments) { get; } | डिलिमिटर अक्षरों द्वारा अलग किए गए एक या अधिक गणितीय तत्व |
| [BeginningCharacter](../../aspose.slides.mathtext/mathdelimiter/beginningcharacter) { get; set; } | Delimiter Beginning Character शुरुआती, अर्थात् खोलने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समावेशी अक्षर हैं जैसे कोष्ठक, ब्रैकेट और ब्रेस। डिफ़ॉल्ट: '(' |
| [DelimiterShape](../../aspose.slides.mathtext/mathdelimiter/delimitershape) { get; set; } | डिलिमिटर ऑब्जेक्ट में डिलिमिटर के आकार को निर्दिष्ट करता है। जब MathDelimiterShape.Centered होता है, डिलिमिटर गणितीय पाठ के गणितीय अक्ष के चारों ओर केंद्रित होते हैं और अपनी सामग्री की पूरी ऊँचाई में फिट होते हैं। जब MathDelimiterShape.Match होता है, उनकी ऊँचाई और आकार को ठीक उनके सामग्री से मिलाने के लिए बदल दिया जाता है। |
| [EndingCharacter](../../aspose.slides.mathtext/mathdelimiter/endingcharacter) { get; set; } | Delimiter Ending Character समाप्ति, अर्थात् बंद करने वाले, डिलिमिटर अक्षर को निर्दिष्ट करता है। गणितीय डिलिमिटर वे समावेशी अक्षर हैं जैसे कोष्ठक, ब्रैकेट और ब्रेस। डिफ़ॉल्ट: ')' |
| [GrowToMatchOperandHeight](../../aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight) { get; set; } | BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, डिलिमिटर ऊर्ध्वाधर रूप से बढ़कर अपने ऑपेंड की ऊँचाई से मेल खाता है। डिफ़ॉल्ट मान true है। |
| [SeparatorCharacter](../../aspose.slides.mathtext/mathdelimiter/separatorcharacter) { get; set; } | Delimiter Separator Character डिलिमिटर ऑब्जेक्ट में तर्कों को अलग करने वाले अक्षर को निर्दिष्ट करता है। डिफ़ॉल्ट: '&#x7C;'. |

## विधियाँ

| Name | Description |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | एक एक्सेंट मार्क सेट करता है (इस तत्व के ऊपर एक अक्षर) |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को आर्ग्यूमेंट के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को आर्ग्यूमेंट के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को आर्ग्यूमेंट के रूप में उपयोग करके लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को आर्ग्यूमेंट और निर्दिष्ट अतिरिक्त आर्ग्यूमेंट के साथ लेता है |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को आर्ग्यूमेंट और निर्दिष्ट अतिरिक्त आर्ग्यूमेंट के साथ लेता है |
| [Delimit](../../aspose.slides.mathtext/mathdelimiter/delimit)(char) | निर्दिष्ट डिलिमिटर अक्षर का उपयोग करके तर्कों को सीमांकित करता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंश और निर्दिष्ट हर के साथ एक भिन्न बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंश और निर्दिष्ट हर के साथ बनाता है |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठक में घेरता है |
| override [Enclose](../../aspose.slides.mathtext/mathdelimiter/enclose#enclose_1)(char, char) | निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य अक्षरों में एक गणितीय तत्व को फ्रेम के रूप में घेरता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है |
| [GetChildren](../../aspose.slides.mathtext/mathdelimiter/getchildren)() | सन्तान तत्व प्राप्त करता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे के कर्ली ब्रैकेट या अन्य समूह-अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्दिष्ट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक नॉन-विज़ुअल बॉक्स (तार्किक समूह) में रखता है, जो समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए उपयोग किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) ऑपरेटर एम्यूलेटर के रूप में कार्य कर सकता है, जिसमें संरेखण बिंदु हो या न हो, लाइन ब्रेक बिंदु के रूप में काम कर सकता है, या इस प्रकार समूहित हो सकता है कि लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत ऐरे में रखता है |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है |

### उदाहरण

Example:

```csharp
[C#]
IMathElement element = new MathematicalText("x");
MathDelimiter delimiter = new MathDelimiter(element);
```

### संबंधित

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathDelimiter](../imathdelimiter)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
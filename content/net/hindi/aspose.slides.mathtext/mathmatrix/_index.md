---
title: MathMatrix
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड तत्वों से बने मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलीमीटर नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलीमीटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। नल आर्ग्यूमेंट्स का उपयोग करके मैट्रिक्स में अंतराल बनाया जा सकता है।
type: docs
weight: 8870
url: /hi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix क्लास

Matrix ऑब्जेक्ट को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड तत्वों से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित विभाजक नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलीमीटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। नल तर्कों का उपयोग करके मैट्रिक्स में खाली स्थान बनाया जा सकता है।

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## कंस्ट्रक्टर

| नाम | विवरण |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | MathMatrix क्लास की नई इंस्टेंस को प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | आसपास के पाठ के सापेक्ष लंबवत संरेखण निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | मैट्रिक्स में स्तंभों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (एक बिंदु का 1/20 हिस्सा) माना जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई 0.5 em बढ़ोतरी की संख्या के रूप में मानी जाती है। अन्य मामलों में नज़रअंदाज़ किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज अंतराल का प्रकार; क्षैतिज अंतराल इकाइयाँ ems या points (टविप्स में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर को छुपाएँ। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | मैट्रिक्स का तत्व |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | टविप्स में न्यूनतम स्तंभ चौड़ाई (एक बिंदु का 1/20 हिस्सा)। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग (विभिन्न स्तंभों के समान किनारों के बीच की दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0 |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | मैट्रिक्स में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (एक बिंदु का 1/20 हिस्सा) माना जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को आधी लाइनों के रूप में माना जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | मैट्रिक्स की पंक्तियों के बीच लंबवत अंतराल का प्रकार; लंबवत अंतराल इकाइयाँ lines या points (टविप्स में संग्रहित) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के ऊपर एक संकेत चिह्न (एक अक्षर) सेट करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में और निर्दिष्ट अतिरिक्त तर्क को उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | निर्दिष्ट स्तंभ को हटाता है। |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार की एक भिन्न को इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | एक गणितीय तत्व को कोष्ठकों में संलग्न करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | एक गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के रूप में संलग्न करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके एक तर्क का फ़ंक्शन लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | चाइल्ड तत्व प्राप्त करता है। |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | निर्दिष्ट स्तंभ की क्षैतिज संरेखण प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूहित अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | निर्दिष्ट स्तंभ के बाद एक नया स्तंभ सम्मिलित करता है। प्रारंभिक रूप से नए स्तंभ के सभी तत्व null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | निर्दिष्ट स्तंभ से पहले एक नया स्तंभ सम्मिलित करता है। प्रारंभिक रूप से नए स्तंभ के सभी तत्व null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करता है। प्रारंभिक रूप से नई पंक्ति के सभी तत्व null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति सम्मिलित करता है। प्रारंभिक रूप से नई पंक्ति के सभी तत्व null होते हैं। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटेग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के ऊपर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दी गई डिग्री का गणितीय मूल निर्धारित करता है। |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट स्तंभ की क्षैतिज संरेखण सेट करता है। |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ तरफ सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-visual बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एमुलेटर के रूप में संरेखण बिंदु के साथ या बिना कार्य कर सकता है, एक लाइन ब्रेक बिंदु के रूप में कार्य कर सकता है, या इस प्रकार समूहित किया जा सकता है कि उसके भीतर लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक लंबवत सरणी में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### देखें भी

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathMatrix](../imathmatrix)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: MathMatrix
second_title: Aspose.Sildes for .NET API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है जो एक या अधिक पंक्तियों और कॉलमों में व्यवस्थित बच्चे तत्वों से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में अंतर्निहित विभाजक नहीं होते हैं। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। शून्य (null) तर्कों का उपयोग मैट्रिक्स में अंतराल बनाने के लिए किया जा सकता है।
type: docs
weight: 8850
url: /hi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix क्लास

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और कॉलमों में व्यवस्थित बच्चे तत्वों से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलिमिटर्स नहीं होते हैं। मैट्रिस को ब्रैकेट्स में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) तर्कों का उपयोग मैट्रिस में अंतराल बनाने के लिए किया जा सकता है।

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | नए MathMatrix क्लास का एक नया उदाहरण प्रारंभ करता है। |

## गुण

| नाम | विवरण |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | आसपास के पाठ के संबंध में लंबवत निरूपण को निर्दिष्ट करता है। संभावित मान शीर्ष, नीचे, और मध्य हैं। डिफ़ॉल्ट: मध्य |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | मैट्रिस में कॉलमों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | मैट्रिस के कॉलमों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को टविप्स (पॉइंट का 1/20) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को 0.5 इम वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | मैट्रिस के कॉलमों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ इम या पॉइंट (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिस तत्वों के लिए प्लेसहोल्डर्स को छिपाता है। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | मैट्रिस का तत्व |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | टविप्स (पॉइंट का 1/20) में न्यूनतम कॉलम चौड़ाई। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) को MinColumnWidth में जोड़कर कुल मैट्रिस कॉलम स्पेसिंग (विभिन्न कॉलमों के समान किनारे के बीच दूरी) निर्धारित की जाती है। डिफ़ॉल्ट: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | मैट्रिस में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | मैट्रिस की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को टविप्स (पॉइंट का 1/20) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को आधी लाइनों के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | मैट्रिस की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइनों या पॉइंट (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के शीर्ष पर एक लहजा चिह्न (एक अक्षर) सेट करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क के रूप में लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | निर्दिष्ट फ़ंक्शन को इस इंस्टेंस को तर्क और निर्दिष्ट अतिरिक्त तर्क के रूप में लेता है। |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | निर्दिष्ट कॉलम को हटाता है। |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंशांक और निर्दिष्ट हर से एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंशांक और निर्दिष्ट हर से एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार का एक भिन्न इस अंशांक और निर्दिष्ट हर के साथ बनाता है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठक में संलग्न करता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | गणितीय तत्व को निर्दिष्ट अक्षरों जैसे कोष्ठक या अन्य फ्रेमिंग अक्षरों में संलग्न करता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के एक फ़ंक्शन को लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के एक फ़ंक्शन को लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | संतान तत्वों को प्राप्त करता है। |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे की कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे की कर्ली ब्रैकेट या अन्य समूह अक्षर जैसे समूह अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | निर्दिष्ट कॉलम के बाद एक नया कॉलम सम्मिलित करता है। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | निर्दिष्ट कॉलम के पहले एक नया कॉलम सम्मिलित करता है। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति के पहले एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमा के बिना इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटेग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटेग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | एक N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | एक N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गए डिग्री की गणितीय मूल निर्दिष्ट करता है। |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करता है। |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचली सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचली सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-भौतिक बॉक्स (तार्किक समूह) में रखता है जिसका उपयोग समीकरण या अन्य गणितीय पाठ के घटकों को समूहित करने के लिए किया जाता है। एक बॉक्स किया गया ऑब्जेक्ट (उदाहरण के लिए) एक ऑपरेटर एम्युलेटर के रूप में कार्य कर सकता है, संरेखण बिंदु के साथ या बिना, एक लाइन ब्रेक बिंदु के रूप में, या इस तरह समूहित किया जा सकता है कि इसके भीतर लाइन ब्रेक न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक ऊर्ध्वाधर एरे में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के नीचे एक बार सेट करता है। |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### संबंधित देखें

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathMatrix](../imathmatrix)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
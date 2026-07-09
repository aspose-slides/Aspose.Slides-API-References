---
title: MathMatrix
second_title: Aspose.Sildes for .NET API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है जिसमें बाल तत्व एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में अंतर्निहित डिलिमिटर नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। शून्य तर्कों का उपयोग करके मैट्रिक्स में गैप बनाए जा सकते हैं।
type: docs
weight: 8850
url: /hi/aspose.slides.mathtext/mathmatrix/
---
## MathMatrix क्लास

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित बाल तत्व होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में अंतर्निहित डिलिमिटर नहीं होते। मैट्रिक्स को ब्रैकेट में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य तर्कों का उपयोग करके मैट्रिक्स में गैप बनाए जा सकते हैं।

```csharp
public sealed class MathMatrix : MathElementBase, IMathMatrix
```

## Constructors

| नाम | विवरण |
| --- | --- |
| [MathMatrix](mathmatrix)(int, int) | MathMatrix क्लास की नई इंस्टेंस को प्रारंभ करता है। |

## Properties

| नाम | विवरण |
| --- | --- |
| [BaseJustification](../../aspose.slides.mathtext/mathmatrix/basejustification) { get; set; } | आसपास के टेक्स्ट के प्रति ऊर्ध्वाधर संरेखण निर्दिष्ट करता है। संभावित मान top, bottom, और center हैं। डिफ़ॉल्ट: Center |
| [ColumnCount](../../aspose.slides.mathtext/mathmatrix/columncount) { get; } | मैट्रिक्स में स्तंभों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/mathmatrix/columngap) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20 पॉइंट) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में अनदेखा किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/mathmatrix/columngaprule) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/mathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर को छुपाता है। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/mathmatrix/item) { get; set; } | मैट्रिक्स का तत्व |
| [MinColumnWidth](../../aspose.slides.mathtext/mathmatrix/mincolumnwidth) { get; set; } | टविप्स (1/20 पॉइंट) में न्यूनतम स्तंभ चौड़ाई। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” कहा जाता है) MinColumnWidth में जोड़ी जाती है ताकि कुल मैट्रिक्स स्तंभ स्पेसिंग निर्धारित हो सके। डिफ़ॉल्ट: 0. |
| [RowCount](../../aspose.slides.mathtext/mathmatrix/rowcount) { get; } | मैट्रिक्स में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/mathmatrix/rowgap) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20 पॉइंट) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को आधी पंक्तियों के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/mathmatrix/rowgaprule) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## Methods

| नाम | विवरण |
| --- | --- |
| [Accent](../../aspose.slides.mathtext/mathelementbase/accent)(char) | इस तत्व के शीर्ष पर एक एक्सेंट मार्क (एक अक्षर) सेट करता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfOneArgument) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, IMathElement) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन को लेता है। |
| [AsArgumentOfFunction](../../aspose.slides.mathtext/mathelementbase/asargumentoffunction)(MathFunctionsOfTwoArguments, string) | इस इंस्टेंस को तर्क के रूप में उपयोग करके और निर्दिष्ट अतिरिक्त तर्क के साथ निर्दिष्ट फ़ंक्शन को लेता है। |
| [DeleteColumn](../../aspose.slides.mathtext/mathmatrix/deletecolumn)(int) | निर्दिष्ट स्तंभ को हटाता है। |
| [DeleteRow](../../aspose.slides.mathtext/mathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement) | इस अंकर और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string) | इस अंकर और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(IMathElement, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंकर और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Divide](../../aspose.slides.mathtext/mathelementbase/divide)(string, MathFractionTypes) | निर्दिष्ट प्रकार के साथ इस अंकर और निर्दिष्ट हर के साथ एक भिन्न बनाता है। |
| [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)() | गणितीय तत्व को कोष्ठक में घेरता है। |
| virtual [Enclose](../../aspose.slides.mathtext/mathelementbase/enclose)(char, char) | गणितीय तत्व को निर्दिष्ट अक्षरों (जैसे कोष्ठक या अन्य अक्षर) में फ्रेमिंग के साथ घेरता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(IMathElement) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है। |
| [Function](../../aspose.slides.mathtext/mathelementbase/function)(string) | इस इंस्टेंस को फ़ंक्शन नाम के रूप में उपयोग करके तर्क के फ़ंक्शन को लेता है। |
| [GetChildren](../../aspose.slides.mathtext/mathmatrix/getchildren)() | बाल तत्वों को प्राप्त करता है। |
| [GetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/getcolumnalignment)(int) | निर्दिष्ट स्तंभ की क्षैतिज संरेखण प्राप्त करता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)() | नीचे के कर्ली ब्रैकेट का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [Group](../../aspose.slides.mathtext/mathelementbase/group)(char, MathTopBotPositions, MathTopBotPositions) | नीचे के कर्ली ब्रैकेट या अन्य समूहिंग अक्षर का उपयोग करके इस तत्व को एक समूह में रखता है। |
| [InsertColumnAfter](../../aspose.slides.mathtext/mathmatrix/insertcolumnafter)(int) | निर्दिष्ट स्तंभ के बाद एक नया स्तंभ सम्मिलित करता है। प्रारंभ में नए स्तंभ में सभी तत्व null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/mathmatrix/insertcolumnbefore)(int) | निर्दिष्ट स्तंभ से पहले एक नया स्तंभ सम्मिलित करता है। प्रारंभ में नए स्तंभ में सभी तत्व null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/mathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति में सभी तत्व null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/mathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति में सभी तत्व null होते हैं। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes) | सीमाओं के बिना इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, IMathElement, IMathElement, MathLimitLocations) | इंटीग्रल लेता है। |
| [Integral](../../aspose.slides.mathtext/mathelementbase/integral)(MathIntegralTypes, string, string, MathLimitLocations) | इंटीग्रल लेता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(IMathElement) | एक गणितीय तत्व को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| virtual [Join](../../aspose.slides.mathtext/mathelementbase/join)(string) | एक गणितीय पाठ को जोड़ता है और एक गणितीय ब्लॉक बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, IMathElement, IMathElement) | N-ary ऑपरेटर बनाता है। |
| [Nary](../../aspose.slides.mathtext/mathelementbase/nary)(MathNaryOperatorTypes, string, string) | N-ary ऑपरेटर बनाता है। |
| [Overbar](../../aspose.slides.mathtext/mathelementbase/overbar)() | इस तत्व के शीर्ष पर एक बार सेट करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(IMathElement) | निर्दिष्ट तर्क से दिए गये क्रमांक की गणितीय मूल निर्धारित करता है। |
| [Radical](../../aspose.slides.mathtext/mathelementbase/radical)(string) | निर्दिष्ट तर्क से दिए गये क्रमांक की गणितीय मूल निर्धारित करता है। |
| [SetColumnAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट स्तंभ की क्षैतिज संरेखण सेट करता है। |
| [SetColumnsAlignment](../../aspose.slides.mathtext/mathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट स्तंभों की क्षैतिज संरेखण सेट करता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(IMathElement) | निचला सीमा लेता है। |
| [SetLowerLimit](../../aspose.slides.mathtext/mathelementbase/setlowerlimit)(string) | निचला सीमा लेता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(IMathElement) | सबस्क्रिप्ट बनाता है। |
| [SetSubscript](../../aspose.slides.mathtext/mathelementbase/setsubscript)(string) | सबस्क्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(IMathElement, IMathElement) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheLeft](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft)(string, string) | बाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(IMathElement, IMathElement) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSubSuperscriptOnTheRight](../../aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright)(string, string) | दाएँ ओर सबस्क्रिप्ट और सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(IMathElement) | सुपरसक्रिप्ट बनाता है। |
| [SetSuperscript](../../aspose.slides.mathtext/mathelementbase/setsuperscript)(string) | सुपरसक्रिप्ट बनाता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(IMathElement) | ऊपरी सीमा लेता है। |
| [SetUpperLimit](../../aspose.slides.mathtext/mathelementbase/setupperlimit)(string) | ऊपरी सीमा लेता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)() | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBorderBox](../../aspose.slides.mathtext/mathelementbase/toborderbox)(bool, bool, bool, bool, bool, bool, bool, bool) | इस तत्व को बॉर्डर-बॉक्स में रखता है। |
| [ToBox](../../aspose.slides.mathtext/mathelementbase/tobox)() | इस तत्व को एक गैर-दृश्यमान बॉक्स (तार्किक समूह) में रखता है, जिसका उपयोग समीकरण के घटकों या अन्य गणितीय पाठ को समूहित करने के लिए किया जाता है। एक बॉक्स्ड ऑब्जेक्ट (उदाहरण के लिए) एलाइनमेंट बिंदु के साथ या बिना ऑपरेटर एमुलेटर, लाइन ब्रेक पॉइंट, या ऐसे समूह के रूप में कार्य कर सकता है जिससे लाइन ब्रेक की अनुमति न हो। |
| virtual [ToMathArray](../../aspose.slides.mathtext/mathelementbase/tomatharray)() | एक ऊर्ध्वाधर ऐरे में रखता है। |
| [Underbar](../../aspose.slides.mathtext/mathelementbase/underbar)() | इस तत्व के निचले भाग पर एक बार सेट करता है। |

### Examples

उदाहरण:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### See Also

* क्लास [MathElementBase](../mathelementbase)
* इंटरफ़ेस [IMathMatrix](../imathmatrix)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
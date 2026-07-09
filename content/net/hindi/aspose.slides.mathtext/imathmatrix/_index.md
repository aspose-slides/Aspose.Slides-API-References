---
title: IMathMatrix
second_title: Aspose.Sildes के लिए .NET API रेफरेंस
description: एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड एलिमेंट्स वाले Matrix ऑब्जेक्ट को निर्दिष्ट करता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में अंतर्निहित डिलीमीटर नहीं होते हैं। मैट्रिस को कोष्ठकों में रखने के लिए आपको डिलीमीटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। Null तर्कों का उपयोग करके मैट्रिस में गैप बनाए जा सकते हैं।
type: docs
weight: 8340
url: /hi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix इंटरफ़ेस

Matrix ऑब्जेक्ट को निर्दिष्ट करता है, जो एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड तत्वों से बना होता है। यह ध्यान देना महत्वपूर्ण है कि मैट्रिस में निर्मित सीमांक नहीं होते हैं। मैट्रिस को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) तर्कों का उपयोग करके मैट्रिस में अंतराल बनाया जा सकता है।

```csharp
public interface IMathMatrix : IMathElement
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | बेस IMathElement इंटरफ़ेस को प्राप्त करने की अनुमति देता है [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर संरेखण निर्दिष्ट करता है। संभावित मान top, bottom, और center। डिफ़ॉल्ट: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | मैट्रिक्स में स्तंभों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज अंतराल का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को twips (पॉइंट का 1/20) के रूप में व्याख्यायित किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को 0.5 em वृद्धि की संख्या के रूप में व्याख्यायित किया जाता है। अन्य मामलों में इसे अनदेखा किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | मैट्रिक्स के स्तंभों के बीच क्षैतिज अंतराल का प्रकार; क्षैतिज अंतराल इकाइयाँ ems या points (twips में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिक्स तत्वों के लिए प्लेसहोल्डर छिपाएँ। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | मैट्रिक्स के तत्व |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | twips (पॉइंट का 1/20) में न्यूनतम स्तंभ चौड़ाई। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग (विभिन्न कॉलम के समान किनारों के बीच दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | मैट्रिक्स में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतराल का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को twips (पॉइंट का 1/20) के रूप में व्याख्यायित किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को आधी लाइनों के रूप में व्याख्यायित किया जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर अंतराल का प्रकार; ऊर्ध्वाधर अंतराल इकाइयाँ lines या points (twips में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | निर्दिष्ट कॉलम को हटाता है |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करें |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | निर्दिष्ट कॉलम के बाद नया कॉलम सम्मिलित करें। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | निर्दिष्ट कॉलम से पहले नया कॉलम सम्मिलित करें। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद नया पंक्ति सम्मिलित करें। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति से पहले नया पंक्ति सम्मिलित करें। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करें |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करें |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### देखें

* इंटरफ़ेस [IMathElement](../imathelement)
* नेमस्पेस [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
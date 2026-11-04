---
title: IMathMatrix
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है जिसमें चाइल्ड एलिमेंट्स एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित होते हैं। यह ध्यान देना आवश्यक है कि मैट्रिस में निर्मित डिलिमिटर्स नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। शून्य (null) आर्ग्युमेंट्स का उपयोग करके मैट्रिक्स में गैप बनाया जा सकता है।
type: docs
weight: 8360
url: /hi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix interface

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तम्भों में व्यवस्थित चाइल्ड एलिमेंट्स होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में इनबिल्ट डिलिमिटर नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) आर्ग्युमेंट्स का उपयोग करके मैट्रिक्स में गैप बना सकते हैं।

```csharp
public interface IMathMatrix : IMathElement
```

## Properties

| Name | Description |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | बेस IMathElement इंटरफ़ेस [`IMathElement`](../imathelement) को प्राप्त करने की अनुमति देता है |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | आसपास के टेक्स्ट के सापेक्ष ऊर्ध्वाधर जस्टिफिकेशन को निर्दिष्ट करता है। संभावित मान हैं top, bottom, और center। डिफ़ॉल्ट: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | मैट्रिक्स में स्तम्भों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20th of a point) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में इसे नजरअंदाज़ किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | मैट्रिक्स के स्तम्भों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिक्स एलिमेंट्स के लिए प्लेसहोल्डर को छुपाएँ। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | मैट्रिक्स के एलिमेंट्स |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | टविप्स (1/20th of a point) में न्यूनतम स्तम्भ चौड़ाई। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” भी कहा जाता है) को MinColumnWidth में जोड़ा जाता है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग (विभिन्न स्तम्भों के समान किनारों के बीच दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | मैट्रिक्स में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया गया है, तो इकाई को टविप्स (1/20th of a point) के रूप में व्याख्या किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया गया है, तो इकाई को आधी लाइन के रूप में व्याख्या किया जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | मैट्रिक्स की पंक्तियों के बीच ऊर्ध्वाधर स्पेसिंग का प्रकार; ऊर्ध्वाधर स्पेसिंग इकाइयाँ lines या points (टविप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## Methods

| Name | Description |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | निर्दिष्ट स्तम्भ को हटाता है |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण प्राप्त करें |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | निर्दिष्ट स्तम्भ के बाद नया स्तम्भ डालें। शुरू में नए स्तम्भ के सभी एलिमेंट्स null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | निर्दिष्ट स्तम्भ से पहले नया स्तम्भ डालें। शुरू में नए स्तम्भ के सभी एलिमेंट्स null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद नई पंक्ति डालें। शुरू में नई पंक्ति के सभी एलिमेंट्स null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति से पहले नई पंक्ति डालें। शुरू में नई पंक्ति के सभी एलिमेंट्स null होते हैं। |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट स्तम्भ की क्षैतिज संरेखण सेट करें |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट स्तम्भों की क्षैतिज संरेखण सेट करें |

### उदाहरण

उदाहरण:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

### संबंधित देखें

* इंटरफ़ेस [IMathElement](../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: IMathMatrix
second_title: Aspose.Sildes .NET के लिए API संदर्भ
description: मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है जिसमें चाइल्ड एलिमेंट्स एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित होते हैं। यह ध्यान देने योग्य है कि मैट्रिक्स में निर्मित विभाजक नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट IMathDelimiter का उपयोग करना चाहिए। शून्य (null) तर्क का उपयोग मैट्रिक्स में अंतराल बनाने के लिए किया जा सकता है।
type: docs
weight: 8340
url: /hi/aspose.slides.mathtext/imathmatrix/
---
## IMathMatrix इंटरफ़ेस

मैट्रिक्स ऑब्जेक्ट को निर्दिष्ट करता है, जिसमें एक या अधिक पंक्तियों और स्तंभों में व्यवस्थित चाइल्ड एलिमेंट्स होते हैं। यह ध्यान देना महत्वपूर्ण है कि मैट्रिक्स में निर्मित विभाजक नहीं होते। मैट्रिक्स को कोष्ठकों में रखने के लिए आपको डिलिमिटर ऑब्जेक्ट (IMathDelimiter) का उपयोग करना चाहिए। शून्य (null) तर्क का उपयोग मैट्रिक्स में अंतराल बनाने के लिये किया जा सकता है।

```csharp
public interface IMathMatrix : IMathElement
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathmatrix/asimathelement) { get; } | बेस IMathElement इंटरफ़ेस प्राप्त करने की अनुमति देता है [`IMathElement`](../imathelement) |
| [BaseJustification](../../aspose.slides.mathtext/imathmatrix/basejustification) { get; set; } | आसपास के टेक्स्ट के सापेक्ष लंबवत समायोजन निर्दिष्ट करता है। संभावित मान शीर्ष, नीचे, और केंद्र हैं। डिफ़ॉल्ट: Center |
| [ColumnCount](../../aspose.slides.mathtext/imathmatrix/columncount) { get; } | मैट्रिक्स में स्तंभों की संख्या |
| [ColumnGap](../../aspose.slides.mathtext/imathmatrix/columngap) { get; set; } | मैट्रिक्स की कॉलमों के बीच क्षैतिज स्पेसिंग का मान; यदि ColumnGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को ट्विप्स (पॉइंट का 1/20) के रूप में व्याख्या किया जाता है। यदि ColumnGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को 0.5 em इंक्रीमेंट की संख्या के रूप में व्याख्या किया जाता है। अन्य मामलों में इसे नज़रअंदाज़ किया जाता है। डिफ़ॉल्ट: 0 |
| [ColumnGapRule](../../aspose.slides.mathtext/imathmatrix/columngaprule) { get; set; } | मैट्रिक्स की कॉलमों के बीच क्षैतिज स्पेसिंग का प्रकार; क्षैतिज स्पेसिंग इकाइयाँ ems या पॉइंट्स (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |
| [HidePlaceholders](../../aspose.slides.mathtext/imathmatrix/hideplaceholders) { get; set; } | खाली मैट्रिक्स तत्वों के प्लेसहोल्डर्स को छिपाएँ। डिफ़ॉल्ट: false |
| [Item](../../aspose.slides.mathtext/imathmatrix/item) { get; set; } | मैट्रिक्स के तत्व |
| [MinColumnWidth](../../aspose.slides.mathtext/imathmatrix/mincolumnwidth) { get; set; } | ट्विप्स (पॉइंट का 1/20) में न्यूनतम कॉलम चौड़ाई। गैप स्पेसिंग (जिसे “Column Gap” या “Gap Width” कहा जाता है) MinColumnWidth में जोड़ी जाती है ताकि कुल मैट्रिक्स कॉलम स्पेसिंग (विभिन्न कॉलमों के समान किनारों के बीच दूरी) निर्धारित हो सके। डिफ़ॉल्ट: 0. |
| [RowCount](../../aspose.slides.mathtext/imathmatrix/rowcount) { get; } | मैट्रिक्स में पंक्तियों की संख्या |
| [RowGap](../../aspose.slides.mathtext/imathmatrix/rowgap) { get; set; } | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का मान; यदि RowGapRule को 3 ("Exactly") पर सेट किया जाता है, तो इकाई को ट्विप्स (पॉइंट का 1/20) के रूप में व्याख्या किया जाता है। यदि RowGapRule को 4 ("Multiple") पर सेट किया जाता है, तो इकाई को आधी लाइनों के रूप में व्याख्या किया जाता है। डिफ़ॉल्ट: 0 |
| [RowGapRule](../../aspose.slides.mathtext/imathmatrix/rowgaprule) { get; set; } | मैट्रिक्स की पंक्तियों के बीच लंबवत स्पेसिंग का प्रकार; लंबवत स्पेसिंग इकाइयाँ लाइन्स या पॉइंट्स (ट्विप्स में संग्रहीत) हो सकती हैं। डिफ़ॉल्ट: SingleSpacingGap (0) |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [DeleteColumn](../../aspose.slides.mathtext/imathmatrix/deletecolumn)(int) | निर्दिष्ट कॉलम को हटाता है |
| [DeleteRow](../../aspose.slides.mathtext/imathmatrix/deleterow)(int) | निर्दिष्ट पंक्ति को हटाता है |
| [GetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/getcolumnalignment)(int) | निर्दिष्ट कॉलम की क्षैतिज संरेखण प्राप्त करता है |
| [InsertColumnAfter](../../aspose.slides.mathtext/imathmatrix/insertcolumnafter)(int) | निर्दिष्ट कॉलम के बाद एक नया कॉलम सम्मिलित करता है। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertColumnBefore](../../aspose.slides.mathtext/imathmatrix/insertcolumnbefore)(int) | निर्दिष्ट कॉलम से पहले एक नया कॉलम सम्मिलित करता है। प्रारंभ में नए कॉलम के सभी तत्व null होते हैं। |
| [InsertRowAfter](../../aspose.slides.mathtext/imathmatrix/insertrowafter)(int) | निर्दिष्ट पंक्ति के बाद एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [InsertRowBefore](../../aspose.slides.mathtext/imathmatrix/insertrowbefore)(int) | निर्दिष्ट पंक्ति से पहले एक नई पंक्ति सम्मिलित करता है। प्रारंभ में नई पंक्ति के सभी तत्व null होते हैं। |
| [SetColumnAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnalignment)(int, MathHorizontalAlignment) | निर्दिष्ट कॉलम की क्षैतिज संरेखण सेट करता है |
| [SetColumnsAlignment](../../aspose.slides.mathtext/imathmatrix/setcolumnsalignment)(int, uint, MathHorizontalAlignment) | निर्दिष्ट कॉलमों की क्षैतिज संरेखण सेट करता है |

## उदाहरण

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix[0, 0] = new MathematicalText("item.1.1");
```

## देखें

* इंटरफ़ेस [IMathElement](../imathelement)
* नामस्थान [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
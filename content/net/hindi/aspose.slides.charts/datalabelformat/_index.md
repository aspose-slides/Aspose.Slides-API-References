---
title: DataLabelFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: DataLabel के फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 1570
url: /hi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat क्लास

DataLabel के फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने-योग्य [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | चार्ट को वापस लौटाता है। केवल-पढ़ने-योग्य [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | डेटा लेबल के फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने-योग्य [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | पढ़ें/लिखें Boolean. |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | DataLabels ऑब्जेक्ट के फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें/लिखें String. |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें/लिखें [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | एक Variant सेट करता है या वापस करता है जो चार्ट पर डेटा लेबल के लिए उपयोग किए गए विभाजक का प्रतिनिधित्व करता है। पढ़ें/लिखें String. |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल बबल साइज वैल्यू डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर बबल साइज वैल्यू दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल कैटेगरी नाम डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर चार्ट पर डेटा लेबल के लिए कैटेगरी नाम दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में दिखाया जाएगा या डेटा लेबल के रूप में। यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट DataLabelCollection डेटा लेबल्स का संग्रह है तो यह प्रॉपर्टी नई डेटा लेबल्स के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से ShowLabelAsDataCallout प्रॉपर्टी सभी डेटा लेबल्स में सेट हो जाता है (उदाहरण: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" जिससे सभी DataLabels[i].ShowLabelAsDataCallout का मान val हो जाता है)। |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल सेल वैल्यू डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर सेल वैल्यू दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन्स डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर लीडर लाइन्स दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड की कुंजी डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर लेजेंड की कुंजी दिखाई देती है। पढ़ें/लिखें Boolean. |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत वैल्यू डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर प्रतिशत वैल्यू दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | चार्ट पर डेटा लेबल्स के लिए श्रृंखला नाम डिस्प्ले व्यवहार को इंगित करने के लिए Boolean प्राप्त या सेट करता है। True होने पर श्रृंखला नाम दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत वैल्यू डिस्प्ले व्यवहार का प्रतिनिधित्व करता है। True होने पर प्रतिशत वैल्यू दिखाता है। False होने पर छुपाता है। पढ़ें/लिखें Boolean. |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | चार्ट टेक्स्ट फ़ॉर्मेट को वापस लौटाता है। केवल-पढ़ने-योग्य [`IChartTextFormat`](../icharttextformat). |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड को वापस लौटाता है। |

### संबंधित देखें

* क्लास [PVIObject](../../aspose.slides/pviobject)
* इंटरफ़ेस [IDataLabelFormat](../idatalabelformat)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
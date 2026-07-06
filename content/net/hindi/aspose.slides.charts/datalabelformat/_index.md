---
title: DataLabelFormat
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: DataLabel के लिए फॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 1570
url: /hi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat क्लास

Represents formatting options for DataLabel.

```csharp
public sealed class DataLabelFormat : PVIObject, IDataLabelFormat
```

## गुण

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Base IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने-योग्य [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | चार्ट को लौटाता है। केवल-पढ़ने-योग्य [`IChart`](../ichart). |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | डेटा लेबल के स्वरूप का प्रतिनिधित्व करता है। केवल-पढ़ने-योग्य [`IFormat`](../iformat). |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | पढ़ने/लिखने योग्य बूलियन। |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | DataLabels ऑब्जेक्ट के लिए फॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [`LegendDataLabelPosition`](../legenddatalabelposition). |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाले एक Variant को सेट या लौटाता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। सत्य होने पर बबल आकार मान प्रदर्शित होता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। श्रेणी का नाम प्रदर्शित करने के लिए true, छिपाने के लिए false। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection डेटा लेबल संग्रह है, तो यह गुण DataLabelCollection संग्रह में नए डेटा लेबल के लिए ShowLabelAsDataCallout गुण का डिफ़ॉल्ट मान प्राप्त करता है या सेट करता है। इस गुण को मान के साथ सेट करने से यह मान सभी डेटा लेबल के ShowLabelAsDataCallout गुण के लिए भी सेट होता है DataLabelCollection संग्रह में (उदा. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" सभी DataLabels[i].ShowLabelAsDataCallout को val के बराबर बनाता है)। |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। सत्य होने पर सेल मान प्रदर्शित होता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइनों के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। सत्य होने पर लीडर लाइनों को प्रदर्शित किया जाता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। यदि डेटा लेबल लेजेंड कुंजी दृश्यमान है तो सत्य। पढ़ने/लिखने योग्य बूलियन। |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। सत्य होने पर प्रतिशत मान प्रदर्शित होता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | चार्ट पर डेटा लेबल के लिए श्रृंखला नाम प्रदर्शन व्यवहार को संकेत करने वाला बूलियन लौटाता है या सेट करता है। सत्य होने पर श्रृंखला नाम दिखाया जाता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | निर्धारित करता है कि निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। सत्य होने पर प्रतिशत मान प्रदर्शित होता है। गलत होने पर छिपा रहता है। पढ़ने/लिखने योग्य बूलियन। |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | चार्ट के पाठ स्वरूप को लौटाता है। केवल-पढ़ने-योग्य [`IChartTextFormat`](../icharttextformat). |

## विधियाँ

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | निर्दिष्ट ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### संबंधित देखें

* क्लास [PVIObject](../../aspose.slides/pviobject)
* इंटरफ़ेस [IDataLabelFormat](../idatalabelformat)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
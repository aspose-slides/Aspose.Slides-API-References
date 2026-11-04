---
title: DataLabelFormat
second_title: Aspose.Sildes for .NET API संदर्भ
description: DataLabel के लिए स्वरूपण विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 1580
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
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | बेस IPresentationComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)। |
| [Chart](../../aspose.slides.charts/datalabelformat/chart) { get; } | चार्ट लौटाता है। केवल पढ़ने योग्य [`IChart`](../ichart)। |
| [Format](../../aspose.slides.charts/datalabelformat/format) { get; } | डेटा लेबल के स्वरूप का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [`IFormat`](../iformat)। |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/datalabelformat/isnumberformatlinkedtosource) { get; set; } | पढ़ने/लिखने योग्य बूलियन। |
| [NumberFormat](../../aspose.slides.charts/datalabelformat/numberformat) { get; set; } | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [Position](../../aspose.slides.charts/datalabelformat/position) { get; set; } | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ने/लिखने योग्य [`LegendDataLabelPosition`](../legenddatalabelposition)। |
| [Separator](../../aspose.slides.charts/datalabelformat/separator) { get; set; } | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले विभाजक को दर्शाने वाला Variant सेट करता है या लौटाता है। पढ़ने/लिखने योग्य स्ट्रिंग। |
| [ShowBubbleSize](../../aspose.slides.charts/datalabelformat/showbubblesize) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True बबल आकार मान दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowCategoryName](../../aspose.slides.charts/datalabelformat/showcategoryname) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLabelAsDataCallout](../../aspose.slides.charts/datalabelformat/showlabelasdatacallout) { get; set; } | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। यदि इस DataLabelFormat ऑब्जेक्ट का पैरेंट एक DataLabelCollection है, जो डेटा लेबलों का संग्रह है, तो यह प्रॉपर्टी DataLabelCollection में नए डेटा लेबलों के लिए ShowLabelAsDataCallout प्रॉपर्टी का डिफ़ॉल्ट मान प्राप्त या सेट करती है। इस प्रॉपर्टी को मान के साथ सेट करने से DataLabelCollection में सभी डेटा लेबलों के लिए ShowLabelAsDataCallout प्रॉपर्टी भी उसी मान पर सेट हो जाती है (उदाहरण के लिए "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" जिससे सभी DataLabels[i].ShowLabelAsDataCallout का मान val हो जाता है)। |
| [ShowLabelValueFromCell](../../aspose.slides.charts/datalabelformat/showlabelvaluefromcell) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल सेल मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True सेल मान दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLeaderLines](../../aspose.slides.charts/datalabelformat/showleaderlines) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइन प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True लीडर लाइन दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowLegendKey](../../aspose.slides.charts/datalabelformat/showlegendkey) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True यदि डेटा लेबल लेजेंड कुंजी दृश्यमान है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowPercentage](../../aspose.slides.charts/datalabelformat/showpercentage) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [ShowSeriesName](../../aspose.slides.charts/datalabelformat/showseriesname) { get; set; } | चार्ट पर डेटा लेबलों के लिए श्रृंखला नाम प्रदर्शन व्यवहार को इंगित करने के लिए बूलियन लौटाता या सेट करता है। True श्रृंखला नाम दिखाने के लिए। False छिपाने के लिए। पढ़ने/लिखने योग्य बूलियन। |
| [ShowValue](../../aspose.slides.charts/datalabelformat/showvalue) { get; set; } | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाता है। पढ़ने/लिखने योग्य बूलियन। |
| [TextFormat](../../aspose.slides.charts/datalabelformat/textformat) { get; } | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [`IChartTextFormat`](../icharttextformat)। |

## विधियाँ

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | उल्लेखित ऑब्जेक्ट के साथ तुलना करता है। |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | हैश कोड लौटाता है। |

### देखें

* क्लास [PVIObject](../../aspose.slides/pviobject)
* इंटरफ़ेस [IDataLabelFormat](../idatalabelformat)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* एसेम्ब्ली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
---
title: IChartSeriesGroup
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: सीरीज़ के समूह को दर्शाता है।
type: docs
weight: 1970
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup इंटरफ़ेस

Represents group of series.

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## गुण

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | बेस IChartComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IChartComponent`](../ichartcomponent)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | बताता है कि बबल चार्ट में बबल आकार मान कैसे प्रदर्शित किए जाते हैं। पढ़ने/लिखने योग्य [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype)। |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य Int32। |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य Byte। |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है या सेट करता है, (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ने/लिखने योग्य UInt16। |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा सीरीज़ के बीच की दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में प्राप्त करता है या सेट करता है। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य UInt16। |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर्स के बीच की दूरी को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में प्राप्त करता है या सेट करता है। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य UInt16। |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | यदि चार्ट में सीरीज़ लाइन्स हैं तो true। स्टैक्ड बार और OfPie चार्ट्स पर लागू होता है। पढ़ने/लिखने योग्य Boolean। |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | निर्दिष्ट करता है कि सीरीज़ में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ने/लिखने योग्य Boolean। |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 2-D चार्ट्स में बार और कॉलम कितना ओवरलैप करेंगे, प्रतिशत के रूप में निर्दिष्ट करता है ( -100% से 100% तक)। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग होते हैं)। - 0%: बार बिना ओवरलैप या स्पेसिंग के साथ साइड बाय साइड रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप होते हैं)。 यह प्रॉपर्टी पढ़ने/लिखने योग्य SByte है। |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट पर दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने के तरीके को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट के साथ पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। इसमें उन डेटा पॉइंट्स को शामिल करता है जो दूसरे पाई या बार में खींचे जाएंगे। केवल पढ़ने योग्य [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट पर दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने के लिए उपयोग किया जाने वाला मूल्य निर्दिष्ट करता है। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | इस समूह की सीरीज़ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं, दर्शाता है। केवल पढ़ने योग्य Boolean। |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य UInt16। |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | चार्ट सीरीज़ का केवल-पढ़ने योग्य संग्रह लौटाता है। केवल पढ़ने योग्य [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection)। |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | इस सीरीज़ समूह का प्रकार लौटाता है। केवल पढ़ने योग्य [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup)। |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Line या Stock चार्ट की अप/डाउन बार तक पहुँच प्रदान करता है। केवल पढ़ने योग्य [`IUpDownBarsManager`](../iupdownbarsmanager)। |

### टिप्पणियाँ

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एनेम के लिए सारांश और टिप्पणियाँ देखें। 2) समूह में कुछ सीरीज़ प्रॉपर्टीज़ हैं जो समूह की प्रत्येक सीरीज़ के लिए सामान्य हैं ("series group properties")। ChartSeriesGroup क्लास में "series group properties" पढ़ने/लिखने योग्य हैं। प्रत्येक "series group properties" का ChartSeries क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

### देखें

* इंटरफ़ेस [IChartComponent](../ichartcomponent)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
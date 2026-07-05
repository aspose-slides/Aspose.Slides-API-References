---
title: IChartSeriesGroup
second_title: Aspose.Sildes for .NET API संदर्भ
description: श्रृंखलाओं का समूह दर्शाता है।
type: docs
weight: 1950
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup इंटरफ़ेस

श्रृंखलाओं का समूह दर्शाता है।

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## गुण

| naam | विवरण |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | बेस IChartComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IChartComponent`](../ichartcomponent)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | बबल चार्ट में बबल आकार मूल्यों को कैसे दर्शाया जाता है, यह निर्धारित करता है। पढ़ने-लिखने योग्य [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype)। |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फैक्टर निर्धारित करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ने-लिखने योग्य Int32। |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद का आकार निर्धारित करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच हो सकता है)। पढ़ने-लिखने योग्य Byte। |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने-लिखने योग्य UInt16। |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर की चौड़ाई के प्रतिशत में प्राप्त या सेट करता है। पढ़ने-लिखने योग्य UInt16। |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर्स के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत में निर्धारित करता है। पढ़ने-लिखने योग्य UInt16। |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | यदि चार्ट में श्रृंखला रेखाएँ हों तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने-लिखने योग्य Boolean। |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines स्वरूप निर्धारित करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है, यह निर्धारित करता है। पढ़ने-लिखने योग्य Boolean। |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, इसे प्रतिशत में निर्धारित करता है ( -100% से 100% तक)। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह से अलग)। - 0%: बार बगल-बगल बिना ओवरलैप या स्पेसिंग के रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार एक-दूसरे पर पूरी तरह से ओवरलैप होते हैं)। यह प्रॉपर्टी पढ़ने-लिखने योग्य SByte है। |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने का तरीका निर्धारित करता है। पढ़ने-लिखने योग्य [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट जानकारी। उन डेटा पॉइंट्स को शामिल करता है जो दूसरे पाई या बार में चित्रित किए जाएंगे। केवल-पढ़ने योग्य [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने के लिए उपयोग किए जाने वाले मान को निर्धारित करता है। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने-लिखने योग्य Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | इस समूह की श्रृंखला द्वितीयक अक्ष पर प्लॉट की गई है या नहीं, दर्शाता है। केवल-पढ़ने योग्य Boolean। |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार के आकार को पहले पाई के आकार के प्रतिशत में निर्धारित करता है (5 से 200 प्रतिशत के बीच)। पढ़ने-लिखने योग्य UInt16। |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। केवल-पढ़ने योग्य [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection)। |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup)। |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Line- या Stock-चार्ट की अप/डाउण बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [`IUpDownBarsManager`](../iupdownbarsmanager)। |

### टिप्पणी

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup enum के सारांश और टिप्पणी देखें।  
2) श्रृंखलाओं का समूह कुछ श्रृंखला प्रॉपर्टीज़ सम्मिलित करता है जो समूह की प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties")। "Series group properties" ChartSeriesGroup क्लास में पढ़ने-लिखने योग्य है। प्रत्येक "series group properties" का केवल-पढ़ने योग्य प्रोजेक्शन ChartSeries क्लास में हो सकता है।

### देखें

* इंटरफ़ेस [IChartComponent](../ichartcomponent)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
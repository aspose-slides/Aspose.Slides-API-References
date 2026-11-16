---
title: ChartSeriesGroup
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 1470
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup वर्ग

Represents group of series.

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | बबल चार्ट पर बबल आकार मूल्यों को कैसे प्रदर्शित किया जाता है, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण, डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ने/लिखने योग्य UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को प्राप्त या सेट करता है, मार्कर चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर के बीच की जगह को प्राप्त या सेट करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। मान 0 से 500 के बीच होना चाहिए। पढ़ने/लिखने योग्य UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | यदि चार्ट में श्रृंखला रेखाएँ हों तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | श्रृंखला में प्रत्येक डेटा मार्कर का अलग रंग हो, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, प्रतिशत के रूप में निर्धारित करता है ( -100% से 100% तक)। - -100%: अधिकतम स्पेसिंग (बार पूरी तरह से अलग)। - 0%: बार बिना ओवरलैप या स्पेसिंग के बगल में रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार पूरी तरह से एक-दूसरे को ओवरलैप करते हैं)। यह प्रॉपर्टी पढ़ने/लिखने योग्य SByte है। |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट वाले pie-of-pie या बार-ऑफ़-पाई चार्ट के लिए कस्टम स्प्लिट जानकारी। इसमें वे डेटा पॉइंट्स शामिल हैं जिन्हें दूसरे पाई या बार में ड्रा किया जाना चाहिए। केवल-पढ़ने योग्य [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हैं, इसे निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ने/लिखने योग्य Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | दर्शाता है कि इस समूह की श्रृंखला द्वितीयक अक्ष पर प्लॉट की गई है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत के रूप में (5 से 200 प्रतिशत के बीच हो सकता है)। पढ़ने/लिखने योग्य UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | श्रृंखलाओं का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Line- या Stock-चार्ट के up/down बार तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IUpDownBarsManager`](../iupdownbarsmanager). |

### टिप्पणियाँ

1) ChartSeriesGroupCollection वर्ग और CombinableSeriesTypesGroup enum के सारांश और टिप्पणी देखें। 2) श्रृंखलाओं का समूह कुछ श्रृंखला गुणों को शामिल करता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं (“series group properties”). ChartSeriesGroup वर्ग में “series group properties” पढ़ने/लिखने योग्य हैं। “series group properties” में से प्रत्येक को ChartSeries वर्ग में केवल-पढ़ने योग्य प्रोजेक्शन मिल सकता है।

### देखें

* इंटरफ़ेस [IChartSeriesGroup](../ichartseriesgroup)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
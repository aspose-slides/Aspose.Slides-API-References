---
title: ChartSeriesGroup
second_title: Aspose.Sildes for .NET API संदर्भ
description: श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 1460
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup क्लास

श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | निर्दिष्ट करता है कि बबल आकार मान बबल चार्ट में कैसे दर्शाए जाते हैं। पढ़ें/लिखें [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ें/लिखें Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | पैरेंट चार्ट लौटाता है। केवल पढ़ें [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत के बीच)। पढ़ें/लिखें Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है, (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। पढ़ें/लिखें UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा श्रृंखलाओं के बीच मार्कर चौड़ाई के प्रतिशत के रूप में दूरी लौटाता या सेट करता है। पढ़ें/लिखें UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर के बीच स्थान को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ें/लिखें Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं। |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ें/लिखें Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | निर्दिष्ट करता है कि 2-D चार्ट पर बार और कॉलम कितनी प्रतिशत ओवरलैप करेंगे (-100% से 100% तक)। - -100%: अधिकतम अंतराल (बार पूरी तरह अलग हैं)। - 0%: बार बिना ओवरलैप या अंतराल के एक साथ रखे जाते हैं। - 100%: अधिकतम ओवरलैप (बार एक-दूसरे पर पूरी तरह ओवरलैप होते हैं)। यह गुण पढ़ें/लिखें SByte है। |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | निर्दिष्ट करता है कि किसी pie-of-pie या bar-of-pie चार्ट में कौन से डेटा पॉइंट दूसरे पाई या बार में हैं, इसे कैसे तय किया जाए। पढ़ें/लिखें [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी एक pie-of-pie या bar-of-pie चार्ट के लिए है जिसमें कस्टम स्प्लिट है। इसमें डेटा पॉइंट शामिल हैं जो दूसरे पाई या बार में ड्रॉ किए जाएंगे। केवल पढ़ें [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | एक मान निर्दिष्ट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि कौन से डेटा पॉइंट दूसरे पाई या बार में हैं एक pie-of-pie या bar-of-pie चार्ट में। इसे PieSplitBy प्रॉपर्टी के साथ प्रयोग किया जाता है। पढ़ें/लिखें Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | बताता है कि इस समूह की श्रृंखला द्वितीयक धुरी पर प्लॉट की गई है या नहीं। केवल पढ़ें Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5% से 200% के बीच हो सकता है)। पढ़ें/लिखें UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | श्रृंखलाओं का संग्रह लौटाता है। केवल पढ़ें [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | इस श्रृंखला समूह का प्रकार लौटाता है। केवल पढ़ें [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | लाइन- या स्टॉक-चार्ट की अप/डाउन बार तक पहुँच प्रदान करता है। केवल पढ़ें [`IUpDownBarsManager`](../iupdownbarsmanager). |

### टिप्पणियाँ

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup enum के सारांश और टिप्पणियों को देखें।  
2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं ("series group properties")। "Series group properties" ChartSeriesGroup क्लास में पढ़ें/लिखें है। प्रत्येक "series group properties" का ChartSeries क्लास में केवल पढ़ने योग्य प्रोजेक्शन हो सकता है।

### देखें

* इंटरफ़ेस [IChartSeriesGroup](../ichartseriesgroup)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
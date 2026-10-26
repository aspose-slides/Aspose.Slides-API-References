---
title: ChartSeriesGroup
second_title: Aspose.Sildes for .NET API संदर्भ
description: सीरियों के समूह को दर्शाता है।
type: docs
weight: 1460
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup वर्ग

क्रमों के समूह का प्रतिनिधित्व करता है।

```csharp
public class ChartSeriesGroup : IChartSeriesGroup
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseriesgroup/bubblesizerepresentation) { get; set; } | निर्दिष्ट करता है कि बबल चार्ट पर बबल आकार मान कैसे प्रदर्शित किए जाते हैं। पढ़ें/लिखें [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype). |
| [BubbleSizeScale](../../aspose.slides.charts/chartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ें/लिखें Int32. |
| [Chart](../../aspose.slides.charts/chartseriesgroup/chart) { get; } | पैरेंट चार्ट को लौटाता है। केवल-पढ़ने योग्य [`IChart`](../ichart). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट एरिया के आकार के 0 से 90 प्रतिशत के बीच हो सकता है)। पढ़ें/लिखें Byte. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्धारित करता/सेट करता है, ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक। पढ़ें/लिखें UInt16. |
| [GapDepth](../../aspose.slides.charts/chartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा सीरीज़ के बीच, मार्कर चौड़ाई के प्रतिशत के रूप में, दूरी निर्धारित करता/सेट करता है। पढ़ें/लिखें UInt16. |
| [GapWidth](../../aspose.slides.charts/chartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर के बीच स्थान को प्रतिशत में निर्धारित करता है, बार या कॉलम की चौड़ाई के प्रतिशत के रूप में। पढ़ें/लिखें UInt16. |
| [HasSeriesLines](../../aspose.slides.charts/chartseriesgroup/hasserieslines) { get; set; } | true यदि चार्ट में सीरीज़ लाइनें हैं। stacked bar और OfPie चार्ट पर लागू। पढ़ें/लिखें Boolean. |
| [HiLowLinesFormat](../../aspose.slides.charts/chartseriesgroup/hilowlinesformat) { get; } | HiLowLines का फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू होते हैं। |
| [IsColorVaried](../../aspose.slides.charts/chartseriesgroup/iscolorvaried) { get; set; } | निर्दिष्ट करता है कि सीरीज़ में प्रत्येक डेटा मार्कर का अलग रंग हो। पढ़ें/लिखें Boolean. |
| [Item](../../aspose.slides.charts/chartseriesgroup/item) { get; } | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/chartseriesgroup/overlap) { get; set; } | 2-D चार्ट में बार और कॉलम की ओवरलैपिंग को प्रतिशत में निर्धारित करता है (-100% से 100% तक)। -100%: अधिकतम स्पेसिंग (बार पूरी तरह अलग)। 0%: बार बिना ओवरलैप के साइड बाय साइड रखे जाते हैं। 100%: अधिकतम ओवरलैप (बार पूरी तरह ओवरलैप)। यह प्रॉपर्टी पढ़ें/लिखें SByte है। |
| [PieSplitBy](../../aspose.slides.charts/chartseriesgroup/piesplitby) { get; set; } | निर्दिष्ट करता है कि दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, pie-of-pie या bar-of-pie चार्ट पर। पढ़ें/लिखें [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी जो pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट के साथ है। उन डेटा पॉइंट्स को शामिल करता है जो दूसरे पाई या बार में ड्रॉ किए जाएँगे। केवल-पढ़ने योग्य [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseriesgroup/piesplitposition) { get; set; } | वह मान निर्दिष्ट करता है जिसका उपयोग यह तय करने के लिए किया जाता है कि दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseriesgroup/plotonsecondaxis) { get; } | दर्शाता है कि इस समूह की सीरीज़ द्वितीयक अक्ष पर प्लॉट की गई है या नहीं। केवल-पढ़ने योग्य Boolean. |
| [SecondPieSize](../../aspose.slides.charts/chartseriesgroup/secondpiesize) { get; set; } | pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार का आकार प्रथम पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 प्रतिशत के बीच)। पढ़ें/लिखें UInt16. |
| [Series](../../aspose.slides.charts/chartseriesgroup/series) { get; } | सीरीज़ का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection). |
| [Type](../../aspose.slides.charts/chartseriesgroup/type) { get; } | इस सीरीज़ समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup). |
| [UpDownBars](../../aspose.slides.charts/chartseriesgroup/updownbars) { get; } | Line- या Stock-चार्ट के अप/डाउन बार तक पहुंच प्रदान करता है। केवल-पढ़ने योग्य [`IUpDownBarsManager`](../iupdownbarsmanager). |

### टिप्पणी

1) देखें सारांश और टिप्पणी ChartSeriesGroupCollection वर्ग और CombinableSeriesTypesGroup एनम के लिए। 2) सीरीज़ समूह कुछ सीरीज़ गुणों को रखता है जो समूह में प्रत्येक सीरीज़ के लिये सामान्य हैं ( "series group properties")। ChartSeriesGroup वर्ग में "series group properties" पढ़ें/लिखें हैं। प्रत्येक "series group properties" का ChartSeries वर्ग में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

### देखें

* इंटरफ़ेस [IChartSeriesGroup](../ichartseriesgroup)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* एसेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
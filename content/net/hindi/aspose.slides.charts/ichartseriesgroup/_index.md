---
title: IChartSeriesGroup
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक श्रृंखला समूह का प्रतिनिधित्व करता है।
type: docs
weight: 1950
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup इंटरफ़ेस

एक श्रृंखला समूह का प्रतिनिधित्व करता है।

```csharp
public interface IChartSeriesGroup : IChartComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseriesgroup/asichartcomponent) { get; } | आधार IChartComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IChartComponent`](../ichartcomponent)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseriesgroup/bubblesizerepresentation) { get; set; } | बबल चार्ट पर बबल आकार मानों के प्रतिनिधित्व का तरीका निर्दिष्ट करता है। पढ़ें/लिखें [`BubbleSizeRepresentationType`](../bubblesizerepresentationtype)। |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseriesgroup/bubblesizescale) { get; set; } | बबल चार्ट के लिए स्केल फैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। पढ़ें/लिखें Int32। |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseriesgroup/doughnutholesize) { get; set; } | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। पढ़ें/लिखें Byte। |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseriesgroup/firstsliceangle) { get; set; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त या सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। पढ़ें/लिखें UInt16। |
| [GapDepth](../../aspose.slides.charts/ichartseriesgroup/gapdepth) { get; set; } | 3D चार्ट में डेटा श्रृंखला के बीच मार्कर चौड़ाई के प्रतिशत के रूप में दूरी लौटाता या सेट करता है। पढ़ें/लिखें UInt16। |
| [GapWidth](../../aspose.slides.charts/ichartseriesgroup/gapwidth) { get; set; } | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। पढ़ें/लिखें UInt16। |
| [HasSeriesLines](../../aspose.slides.charts/ichartseriesgroup/hasserieslines) { get; set; } | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [HiLowLinesFormat](../../aspose.slides.charts/ichartseriesgroup/hilowlinesformat) { get; } | HiLowLines प्रारूप निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| [IsColorVaried](../../aspose.slides.charts/ichartseriesgroup/iscolorvaried) { get; set; } | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है। पढ़ें/लिखें Boolean। |
| [Item](../../aspose.slides.charts/ichartseriesgroup/item) { get; } | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| [Overlap](../../aspose.slides.charts/ichartseriesgroup/overlap) { get; set; } | 2-D चार्टों पर बार और कॉलम कितना ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है (-100 % से 100 % तक)। - -100 %: अधिकतम अंतराल (बार पूरी तरह अलग)। - 0 %: बार बगल-बगल रखे जाते हैं बिना ओवरलैप या अंतराल के। - 100 %: अधिकतम ओवरलैप (बार पूरी तरह एक-दूसरे पर ओवरलैप करते हैं)। यह गुण पढ़ें/लिखें SByte। |
| [PieSplitBy](../../aspose.slides.charts/ichartseriesgroup/piesplitby) { get; set; } | pie-of-pie या bar-of-pie चार्ट पर दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। पढ़ें/लिखें [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseriesgroup/piesplitcustompoints) { get; } | कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट जानकारी। इसमें वे डेटा पॉइंट्स होते हैं जिन्हें दूसरे पाई या बार में ड्रॉ किया जाएगा। केवल-पढ़ने योग्य [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/ichartseriesgroup/piesplitposition) { get; set; } | pie-of-pie या bar-of-pie चार्ट पर दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, यह निर्धारित करने के लिए उपयोग किया जाने वाला मान निर्दिष्ट करता है। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। पढ़ें/लिखें Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseriesgroup/plotonsecondaxis) { get; } | यह दर्शाता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। केवल-पढ़ने योग्य Boolean। |
| [SecondPieSize](../../aspose.slides.charts/ichartseriesgroup/secondpiesize) { get; set; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में निर्दिष्ट करता है (5 से 200 % के बीच)। पढ़ें/लिखें UInt16। |
| [Series](../../aspose.slides.charts/ichartseriesgroup/series) { get; } | एक केवल-पढ़ने योग्य चार्ट श्रृंखला संग्रह लौटाता है। केवल-पढ़ने योग्य [`IChartSeriesReadonlyCollection`](../ichartseriesreadonlycollection)। |
| [Type](../../aspose.slides.charts/ichartseriesgroup/type) { get; } | इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [`CombinableSeriesTypesGroup`](../combinableseriestypesgroup)। |
| [UpDownBars](../../aspose.slides.charts/ichartseriesgroup/updownbars) { get; } | Line- या Stock-चार्ट के up/down बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [`IUpDownBarsManager`](../iupdownbarsmanager)। |

### टिप्पणी

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एन्नम के लिए सारांश और टिप्पणी देखें।  
2) श्रृंखला समूह में कुछ श्रृंखला गुण होते हैं जो समूह में प्रत्येक श्रृंखला के लिए सामान्य होते हैं (“series group properties”). ChartSeriesGroup क्लास में “series group properties” पढ़ें/लिखें हैं। “series group properties” में से प्रत्येक का ChartSeries क्लास में केवल-पढ़ने योग्य प्रोजेक्शन हो सकता है।

### संबंधित देखें

* इंटरफ़ेस [IChartComponent](../ichartcomponent)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
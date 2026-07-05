---
title: ChartSeries
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
weight: 1440
url: /hi/aspose.slides.charts/chartseries/
---
## ChartSeries वर्ग

एक चार्ट श्रृंखला को दर्शाता है।

```csharp
public class ChartSeries : IChartSeries
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | 3-डी बार चार्ट की एक श्रृंखला के आकार को निर्दिष्ट करता है। इस गुण के मान को बदलने से श्रृंखला के प्रकार का स्वतः परिवर्तन हो सकता है। Read/write [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | बब्बल चार्ट में बब्बल आकार मानों के प्रतिनिधित्व को निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation read/write गुण का उपयोग करें। |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | बब्बल चार्ट के लिए स्केल फ़ैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-से-300 % के बीच हो सकता है)। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale read/write गुण का उपयोग करें। |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | अभिभावक चार्ट को लौटाता है। Read-only [`IChart`](../ichart). |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | इस श्रृंखला के डेटा बिंदुओं का संग्रह लौटाता है। Read-only [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10-से-90 % के बीच)। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize read/write गुण का उपयोग करें। Read-only Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। X दिशा वाले ErrorBars area, bar, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य किसी भी चार्ट प्रकार (3D चार्ट सहित) के लिए यह गुण null लौटाता है। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y दिशा के साथ श्रृंखला के ErrorBars को दर्शाता है। Y दिशा वाले ErrorBars area, bar, line, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य किसी भी चार्ट प्रकार (3D चार्ट सहित) के लिए यह गुण null लौटाता है। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। Read-only [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत में व्यक्त करता है। Read/write Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | पहले पाई या डोनट स्लाइस का कोण, डिग्री में (ऊपर से घड़ी की दिशा में, 0-से-360 डिग्री)। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle read/write गुण का उपयोग करें। Read-only UInt16. |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | श्रृंखला का फॉर्मेट लौटाता है। Read-only [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D चार्ट में डेटा श्रृंखलाओं के बीच मार्कर चौड़ाई के प्रतिशत के रूप में दूरी को लौटाता या सेट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth read/write गुण का उपयोग करें। Read-only Int32. |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth read/write गुण का उपयोग करें। Read-only Int32. |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | इस श्रृंखला और संबंधित श्रृंखलाओं के लिए श्रृंखला रेखाएँ हैं या नहीं, यह निर्धारित करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines read/write गुण का उपयोग करें। श्रृंखला रेखाओं के फॉर्मेट के लिए ParentSeriesGroup.SeriesLinesFormat गुण का उपयोग करें। Read-only Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | लाइन या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं, यह निर्धारित करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars read/write गुण का उपयोग करें। अप/डाउन बार के फॉर्मेट के लिए ParentSeriesGroup.UpDownBars गुण का उपयोग करें। Read-only Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | श्रृंखला के लिए उल्टी ठोस रंग निर्दिष्ट करता है। रंग सेटिंग लागू करने के लिए श्रृंखला फॉर्मेट का FillType को FillType.Solid पर सेट करें। Read/write [`ColorFormat`](../../aspose.slides/colorformat). |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो बार, कॉलम या बब्बल श्रृंखला अपने रंग उलट देगी। Read/write Boolean. |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग है यह निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried read/write गुण का उपयोग करें। Read-only Boolean. |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | श्रृंखला के Labels को लौटाता है। Read-only [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | मार्कर। Read-only [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | श्रृंखला का नाम लौटाता है। Read-only [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes. Read/write String. |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues. Read/write String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues. Read/write String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues. Read/write String. |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | श्रृंखला के क्रम को लौटाता है। Read/write Int32. |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D चार्ट पर बार और कॉलम कितने प्रतिशत (-100 % से 100 %) ओवरलैप करेंगे, यह निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है और इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap read/write गुण का उपयोग करें। Read-only SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | अभिभावक श्रेणी लेबल का लेआउट दर्शाता है। केवल Treemap चार्ट के लिए लागू। |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup. Read-only [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में यह निर्धारित करता है कि कौन से डेटा पॉइंट दूसरे पाई या बार में हैं। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। अभिभावक श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitBy read/write गुण का उपयोग करें। Read-only [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी दर्शाता है, जिसमें वह डेटा पॉइंट शामिल हैं जो पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट के दूसरे पाई या बार में चित्रित होंगे। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। Read-only [`PieSplitCustomPointCollection`](../piesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | वह मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा पॉइंट दूसरे पाई या बार में हैं। यह PieSplitBy गुण के साथ उपयोग किया जाता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition read/write गुण का उपयोग करें। Read-only Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | यह दर्शाता है कि यह श्रृंखला द्वितीय अक्ष पर प्लॉट की गई है या नहीं। Read/write Boolean. |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट के लिए लागू। |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | इस श्रृंखला से संबंधित लीजेण्ड प्रविष्टि दर्शाता है। Read-only [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार के आकार को पहले पाई के आकार के प्रतिशत (5-से-200 %) में निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं बल्कि अभिभावक श्रृंखला समूह की सभी श्रृंखलाओं के लिए है — यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.SecondPieSize read/write गुण का उपयोग करें। Read-only UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट के लिए लागू। |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | आंतरिक बिंदुओं को दर्शाता है। BoxAndWhisker चार्ट पर आंतरिक बिंदु दिखाए जाते हैं तो true। केवल BoxAndWhisker चार्ट के लिए लागू। Read/write Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | औसत रेखा को दर्शाता है। BoxAndWhisker चार्ट पर औसत रेखा दिखाए जाने पर true। केवल BoxAndWhisker चार्ट के लिए लागू। Read/write Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | औसत मार्कर को दर्शाता है। BoxAndWhisker चार्ट पर औसत मार्कर दिखाए जाने पर true। केवल BoxAndWhisker चार्ट के लिए लागू। Read/write Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | आउट्लायर बिंदुओं को दर्शाता है। BoxAndWhisker चार्ट पर आउट्लायर बिंदु दिखाए जाने पर true। केवल BoxAndWhisker चार्ट के लिए लागू। Read/write Boolean. |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | कर्व स्मूदिंग को दर्शाता है। लाइन या स्कैटर चार्ट में कर्व स्मूदिंग चालू होने पर true। केवल लाइन और स्कैटर कॉनेक्टेड बाय लाइन्स चार्ट के लिए लागू। Read/write Boolean. |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | श्रृंखला ट्रेंड लाइनों का संग्रह। Read-only [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | इस श्रृंखला का प्रकार लौटाता है। Read/write [`ChartType`](../charttype). |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | श्रृंखला इंडेक्स और चार्ट शैली के आधार पर श्रृंखला का स्वचालित रंग लौटाता है। यदि FillType NotDefined हो तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |

### संबंधित देखें

* इंटरफ़ेस [IChartSeries](../ichartseries)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
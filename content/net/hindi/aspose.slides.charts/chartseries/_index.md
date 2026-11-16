---
title: ChartSeries
second_title: Aspose.Sildes .NET API संदर्भ
description: एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
weight: 1450
url: /hi/aspose.slides.charts/chartseries/
---
## ChartSeries वर्ग

एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।

```csharp
public class ChartSeries : IChartSeries
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | एक 3-डी बार चार्ट की श्रृंखला के आकार को निर्दिष्ट करता है। इस गुण के मान को बदलने से श्रृंखला के प्रकार को स्वतः बदल सकता है। पढ़ें/लिखें [`ChartShapeType`](../chartshapetype)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | बबल आकार मानों को बबल चार्ट पर कैसे दर्शाया जाता है, निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ें/लिखें गुण का प्रयोग करें। |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | बबल चार्ट के लिए स्केल फ़ैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ें/लिखें गुण का प्रयोग करें। |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | पैरेंट चार्ट को लौटाता है। केवल पढ़ने योग्य [`IChart`](../ichart)। |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। केवल पढ़ने योग्य [`IChartDataPointCollection`](../ichartdatapointcollection)। |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | डोनट चार्ट में होल का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 10 से 90 प्रतिशत के बीच)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य Byte। |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X दिशा वाले श्रृंखला के ErrorBars को दर्शाता है। X दिशा वाले ErrorBars केवल area, bar, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह गुण null लौटाता है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। केवल पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y दिशा वाले श्रृंखला के ErrorBars को दर्शाता है। Y दिशा वाले ErrorBars केवल area, bar, line, scatter और bubble प्रकार की श्रृंखलाओं के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह गुण null लौटाता है (3D चार्ट सहित)। कस्टम मानों के लिए DataPoints संग्रह का उपयोग करके मान निर्दिष्ट करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। केवल पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | पाई चार्ट के एक खुले स्लाइस की दूरी को पाई डायमीटर के प्रतिशत के रूप में व्यक्त करता है। पढ़ें/लिखें Int32। |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य UInt16। |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | एक श्रृंखला का फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [`IFormat`](../iformat)। |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी, मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या निर्धारित करता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य Int32। |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | बार या कॉलम क्लस्टर्स के बीच स्थान को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य Int32। |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | यह निर्धारित करता है कि इस श्रृंखला और संबंधित श्रृंखलाओं के लिए श्रृंखला रेखाएँ हैं या नहीं। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ें/लिखें गुण का प्रयोग करें। श्रृंखला रेखाओं के फ़ॉर्मेट के लिए ParentSeriesGroup.SeriesLinesFormat गुण का प्रयोग करें। केवल पढ़ने योग्य Boolean। |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | यह निर्धारित करता है कि लाइन- या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ें/लिखें गुण का प्रयोग करें। अप/डाउन बार के फ़ॉर्मेट के लिए ParentSeriesGroup.UpDownBars गुण का प्रयोग करें। केवल पढ़ने योग्य Boolean। |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। रंग सेट करने के लिए श्रृंखला फ़ॉर्मेट का FillType को FillType.Solid पर सेट करें। पढ़ें/लिखें [`ColorFormat`](../../aspose.slides/colorformat)। |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो बार, कॉलम या बबल श्रृंखला को अपने रंग उलटने के लिए निर्दिष्ट करता है। पढ़ें/लिखें Boolean। |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | यह निर्धारित करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य Boolean। |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | एक श्रृंखला के लेबल लौटाता है। केवल पढ़ने योग्य [`IDataLabelCollection`](../idatalabelcollection)। |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | मार्कर। केवल पढ़ने योग्य [`IMarker`](../imarker)। |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | श्रृंखला का नाम लौटाता है। केवल पढ़ने योग्य [`IStringChartValue`](../istringchartvalue)। |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes। पढ़ें/लिखें String। |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues। पढ़ें/लिखें String। |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues। पढ़ें/लिखें String। |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues। पढ़ें/लिखें String। |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | एक श्रृंखला का क्रम लौटाता है। पढ़ें/लिखें Int32। |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-डि चार्ट में बार और कॉलम कितना ओवरलैप करते हैं, प्रतिशत के रूप में निर्दिष्ट करता है (-100% से 100% तक)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इस मान को बदलने के लिए !:ParentSeriesGroup.Overlap पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य SByte। |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | पैरेंट श्रेणी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट पर लागू। |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup। केवल पढ़ने योग्य [`IChartSeriesGroup`](../ichartseriesgroup)। |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में यह निर्धारित करने के लिए कि कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं, कैसे तय किया जाता है, निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी जिसमें पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार में खींचे जाने वाले डेटा पॉइंट्स होते हैं। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। केवल पढ़ने योग्य [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | वह मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में कौन से डेटा पॉइंट्स दूसरे पाई या बार में हैं। PieSplitBy गुण के साथ उपयोग किया जाता है। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | यह दर्शाता है कि यह श्रृंखला द्वितीयक अक्ष पर प्लॉट की गई है या नहीं। पढ़ें/लिखें Boolean। |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू। |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | इस श्रृंखला से संबंधित लेजेंड एंट्री को दर्शाता है। केवल पढ़ने योग्य [`ILegendEntryProperties`](../ilegendentryproperties)। |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत के रूप में निर्दिष्ट करता है (5 से 200 प्रतिशत तक)। यह गुण केवल इस श्रृंखला का ही नहीं बल्कि पैरेंट श्रृंखला समूह की सभी श्रृंखलाओं का प्रक्षेपण है। इसलिए यह गुण केवल पढ़ने योग्य है। पैरेंट श्रृंखला समूह तक पहुंचने के लिए ParentSeriesGroup गुण का प्रयोग करें। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ें/लिखें गुण का प्रयोग करें। केवल पढ़ने योग्य UInt16। |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | कनेक्टर लाइन्स को दर्शाता है। केवल Waterfall चार्ट पर लागू। |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | आंतरिक बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट पर आंतरिक बिंदु दिखाए गए हों तो सत्य। केवल BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | माध्य रेखा को दर्शाता है। यदि BoxAndWhisker चार्ट पर माध्य रेखा दिखायी गयी हो तो सत्य। केवल BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | माध्य मार्कर को दर्शाता है। यदि BoxAndWhisker चार्ट पर माध्य मार्कर दिखायी गये हों तो सत्य। केवल BoxAndWhisker चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | आउट्लायर बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट पर आउट्लायर बिंदु दिखाये गये हों तो सत्य। केवल BoxAndWhiskर चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | कर्व स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट के लिए कर्व स्मूथिंग सक्षम है तो सत्य। केवल लाइन और स्कैटर चार्ट पर लागू। पढ़ें/लिखें Boolean। |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | श्रृंखला ट्रेंड लाइनों का संग्रह। केवल पढ़ने योग्य [`ITrendlineCollection`](../itrendlinecollection)। |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | इस श्रृंखला का प्रकार लौटाता है। पढ़ें/लिखें [`ChartType`](../charttype)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | श्रृंखला इंडेक्स और चार्ट शैली के आधार पर श्रृंखला का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर हो तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |

### देखें

* इंटरफ़ेस [IChartSeries](../ichartseries)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
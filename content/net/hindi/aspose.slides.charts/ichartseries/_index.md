---
title: IChartSeries
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
weight: 1930
url: /hi/aspose.slides.charts/ichartseries/
---
## IChartSeries इंटरफ़ेस

एक चार्ट श्रृंखला को दर्शाता है।

```csharp
public interface IChartSeries : IChartComponent
```

## गुण

| Name | Description |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | बेस IChartComponent इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने-योग्य [`IChartComponent`](../ichartcomponent). |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3-डी बार चार्ट की श्रृंखला की आकृति निर्दिष्ट करता है। इस गुण का मान बदलने से श्रृंखला के प्रकार में स्वत: परिवर्तन हो सकता है। पढ़ने-लिखने-योग्य [`ChartShapeType`](../chartshapetype). |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | बबल चार्ट में बबल आकार मूल्यों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के लिए नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के लिए है – यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ने-लिखने-योग्य गुण का उपयोग करें। |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 % से 300 % तक हो सकता है)। यह गुण केवल इस श्रृंखला के लिए नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के लिए है – यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ने-लिखने-योग्य गुण का उपयोग करें। |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | इस श्रृंखला के डेटा पॉइंट्स का संग्रह लौटाता है। केवल-पढ़ने-योग्य [`IChartDataPointCollection`](../ichartdatapointcollection). |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 % से 90 % तक)। यह गुण केवल इस श्रृंखला के लिए नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के लिए है – यह उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह गुण केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य Byte. |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | X दिशा वाले श्रृंखला के ErrorBars को दर्शाता है। X दिशा वाले ErrorBars केवल area, bar, scatter और bubble प्रकार की श्रृक्तियों के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों (3D चार्ट सहित) के लिए यह गुण null लौटाता है। कस्टम मानों के लिए मान निर्दिष्ट करने हेतु DataPoints संग्रह का उपयोग करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। केवल-पढ़ने-योग्य [`IErrorBarsFormat`](../ierrorbarsformat). |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | Y दिशा वाले श्रृंखला के ErrorBars को दर्शाता है। Y दिशा वाले ErrorBars केवल area, bar, line, scatter और bubble प्रकार की श्रृक्तियों के लिए उपलब्ध हैं। अन्य चार्ट प्रकारों (3D चार्ट सहित) के लिए यह गुण null लौटाता है। कस्टम मानों के लिए मान निर्दिष्ट करने हेतु DataPoints संग्रह का उपयोग करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) गुण के साथ)। केवल-पढ़ने-योग्य [`IErrorBarsFormat`](../ierrorbarsformat). |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | पाई चार्ट के केंद्र से खुले पाई स्लाइस की दूरी को पाई व्यास के प्रतिशत में दर्शाया जाता है। पढ़ने-लिखने-योग्य Int32. |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से 0 से 360 डिग्री तक घड़ी की दिशा में)। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य UInt16. |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | एक श्रृंखला का फ़ॉर्मेट लौटाता है। केवल-पढ़ने-योग्य [`IFormat`](../iformat). |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3-डी चार्ट में डेटा श्रृक्तियों के बीच दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य Int32. |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | बार या कॉलम क्लस्टर्स के बीच स्थान को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य Int32. |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | यह निर्धारित करता है कि इस श्रृंखला और संबंधित श्रृक्तियों के लिए श्रृंखला रेखाएँ हैं या नहीं। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ने-लिखने-योग्य गुण का उपयोग करें। श्रृंखला रेखाओं के फ़ॉर्मेट के लिए ParentSeriesGroup.SeriesLinesFormat गुण का उपयोग करें। केवल-पढ़ने-योग्य Boolean. |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | यह निर्धारित करता है कि Line- या Stock-चार्ट में अप/डाउन बार हैं या नहीं। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ने-लिखने-योग्य गुण का उपयोग करें। अप/डाउन बार के फ़ॉर्मेट के लिए ParentSeriesGroup.UpDownBars गुण का उपयोग करें। केवल-पढ़ने-योग्य Boolean. |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | श्रृंखला के लिए उलटा ठोस रंग निर्दिष्ट करता है। रंग सेटिंग लागू करने के लिए श्रृंखला फ़ॉर्मेट का FillType को FillType.Solid पर सेट करें। पढ़ने-लिखने-योग्य [`IColorFormat`](../../aspose.slides/icolorformat). |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | यदि मान नकारात्मक हो तो बार, कॉलम या बबल श्रृंखला को अपने रंग उलटने के लिए निर्दिष्ट करता है। पढ़ने-लिखने-योग्य Boolean. |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य Boolean. |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | एक श्रृंखला के लेबल लौटाता है। केवल-पढ़ने-योग्य [`IDataLabelCollection`](../idatalabelcollection). |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | श्रृंखला मार्कर लौटाता है। केवल-पढ़ने-योग्य [`IMarker`](../imarker). |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | श्रृंखला का नाम लौटाता है। केवल-पढ़ने-योग्य [`IStringChartValue`](../istringchartvalue). |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | श्रृंखला बबल आकारों के लिए संख्या प्रारूप लौटाता या सेट करता है। पढ़ने-लिखने-योग्य String. |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | श्रृंखला मानों के लिए संख्या प्रारूप लौटाता या सेट करता है। पढ़ने-लिखने-योग्य String. |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | श्रृंखला X मानों के लिए संख्या प्रारूप लौटाता या सेट करता है। पढ़ने-लिखने-योग्य String. |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | श्रृक्ति Y मानों के लिए संख्या प्रारूप लौटाता या सेट करता है। पढ़ने-लिखने-योग्य String. |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | एक श्रृंखला का क्रम लौटाता है। पढ़ने-लिखने-योग्य Int32. |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2-डी चार्ट में बार और कॉलम कितनी ओवरलैप होते हैं, प्रतिशत में (-100 % से 100 % तक) निर्दिष्ट करता है। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – यह उपयुक्त समूह गुण का प्रक्षेपण है, इसलिए यह केवल-पढ़ने-योग्य है। मान बदलने के लिए ParentSeriesGroup.Overlap पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य SByte. |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट पर लागू होता है। |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | पैरेंट श्रृंखला समूह लौटाता है। केवल-पढ़ने-योग्य [`IChartSeriesGroup`](../ichartseriesgroup). |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | pie-of-pie या bar-of-pie चार्ट में यह निर्धारित करने के लिए कि कौन से डेटा पॉइंट्स दूसरे पाई या बार में हों, उसके लिए निर्धारित करता है। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitBy पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य [`PieSplitType`](../piesplittype). |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | कस्टम स्प्लिट के साथ pie-of-pie या bar-of-pie चार्ट के लिए कस्टम विभाजन जानकारी। इसमें उन डेटा पॉइंट्स का डेटा है जो दूसरे पाई या बार में चित्रित किए जाएंगे। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – यह उपयुक्त समूह गुण का प्रक्षेपण है। केवल-पढ़ने-योग्य [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection). |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | pie-of-pie या bar-of-pie चार्ट में यह निर्धारित करने के लिए उपयोग किया जाने वाला मान कि कौन से डेटा पॉइंट्स दूसरे पाई या बार में हों। यह PieSplitBy गुण के साथ उपयोग किया जाता है। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.PieSplitPosition पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य Double. |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | निर्दिष्ट करता है कि यह श्रृंखला दूसरे मान धुरी पर दर्शाई गई है या नहीं। पढ़ने-लिखने-योग्य Boolean. |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू। |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | इस श्रृंखला से संबंधित लीजेंड एंट्री दर्शाता है। केवल-पढ़ने-योग्य [`ILegendEntryProperties`](../ilegendentryproperties). |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 % से 200 % तक)। यह गुण केवल इस श्रृंखला के नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी श्रृक्तियों के भी है – उपयुक्त समूह गुण का प्रक्षेपण है। इसलिए यह केवल-पढ़ने-योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुंचने के लिए ParentSeriesGroup गुण का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.SecondPieSize पढ़ने-लिखने-योग्य गुण का उपयोग करें। केवल-पढ़ने-योग्य UInt16. |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू। |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | आंतरिक बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट पर आंतरिक बिंदु दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने-लिखने-योग्य Boolean. |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | औसत मार्कर दर्शाता है। यदि BoxAndWhisker चार्ट पर औसत रेखा दिखाया गया हो तो True। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने-लिखने-योग्य Boolean. |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | औसत मार्कर दर्शाता है। यदि BoxAndWhisker चार्ट पर औसत मार्कर दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने-लिखने-योग्य Boolean. |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | आउटलाइनर बिंदुओं को दर्शाता है। यदि BoxAndWhisker चार्ट पर आउटलाइनर बिंदु दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने-लिखने-योग्य Boolean. |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | कर्व स्मूदिंग दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट पर कर्व स्मूदिंग चालू हो तो True। केवल लाइन और स्कैटर चार्ट पर लागू जो लाइनों से जुड़े हों। पढ़ने-लिखने-योग्य Boolean. |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | श्रृंखला ट्रेंड लाइनों का संग्रह। केवल-पढ़ने-योग्य [`ITrendlineCollection`](../itrendlinecollection). |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | इस श्रृंखला का प्रकार लौटाता है। पढ़ने-लिखने-योग्य [`ChartType`](../charttype). |

## विधियाँ

| Name | Description |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | श्रृंखला इंडेक्स और चार्ट शैली के आधार पर श्रृंखला का स्वचालित रंग लौटाता है। यदि FillType NotDefined है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |

### संबंधित देखें

* इंटरफ़ेस [IChartComponent](../ichartcomponent)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेम्बली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
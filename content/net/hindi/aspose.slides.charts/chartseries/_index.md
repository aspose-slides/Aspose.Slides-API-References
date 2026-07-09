---
title: ChartSeries
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चार्ट सीरीज़ का प्रतिनिधित्व करता है।
type: docs
weight: 1440
url: /hi/aspose.slides.charts/chartseries/
---
## ChartSeries क्लास

एक चार्ट सीरीज़ का प्रतिनिधित्व करता है।

```csharp
public class ChartSeries : IChartSeries
```

## गुण

| नाम | विवरण |
| --- | --- |
| [Bar3DShape](../../aspose.slides.charts/chartseries/bar3dshape) { get; set; } | एक 3-डी बार चार्ट की सीरीज़ के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी के मान को बदलने से सीरीज़ के प्रकार को स्वचालित रूप से बदल सकता है। पढ़ने/लिखने योग्य [`ChartShapeType`](../chartshapetype)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/chartseries/bubblesizerepresentation) { get; } | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, इसे निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की ही नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। |
| [BubbleSizeScale](../../aspose.slides.charts/chartseries/bubblesizescale) { get; } | बबल चार्ट के लिए स्केल फ़ैक्टर को निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0-300 % के बीच हो सकता है)। यह प्रॉपर्टी केवल इस सीरीज़ की ही नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। |
| [Chart](../../aspose.slides.charts/chartseries/chart) { get; } | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [`IChart`](../ichart)। |
| [DataPoints](../../aspose.slides.charts/chartseries/datapoints) { get; } | इस सीरीज़ के डेटा पॉइंट्स का संग्रह लौटाता है। केवल-पढ़ने योग्य [`IChartDataPointCollection`](../ichartdatapointcollection)। |
| [DoughnutHoleSize](../../aspose.slides.charts/chartseries/doughnutholesize) { get; } | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10-90 % के बीच)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Byte। |
| [ErrorBarsXFormat](../../aspose.slides.charts/chartseries/errorbarsxformat) { get; } | X दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। X दिशा वाले ErrorBars area, bar, scatter और bubble प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के मामले में मान निर्दिष्ट करने के लिए DataPoints संग्रह का उपयोग करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) प्रॉपर्टी के साथ)। केवल-पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [ErrorBarsYFormat](../../aspose.slides.charts/chartseries/errorbarsyformat) { get; } | Y दिशा वाले सीरीज़ के ErrorBars को दर्शाता है। Y दिशा वाले ErrorBars area, bar, line, scatter और bubble प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य प्रकार के चार्ट के लिए यह प्रॉपर्टी null लौटाती है (3D चार्ट सहित)। कस्टम मानों के मामले में मान निर्दिष्ट करने के लिए DataPoints संग्रह का उपयोग करें ([`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) प्रॉपर्टी के साथ)। केवल-पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [Explosion](../../aspose.slides.charts/chartseries/explosion) { get; set; } | खुले पाई स्लाइस की केंद्र से दूरी को पाई व्यास के प्रतिशत के रूप में व्यक्त किया जाता है। पढ़ने/लिखने योग्य Int32। |
| [FirstSliceAngle](../../aspose.slides.charts/chartseries/firstsliceangle) { get; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0-360 डिग्री)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य UInt16। |
| [Format](../../aspose.slides.charts/chartseries/format) { get; } | सीरीज़ का फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [`IFormat`](../iformat)। |
| [GapDepth](../../aspose.slides.charts/chartseries/gapdepth) { get; } | 3D चार्ट में डेटा सीरीज़ के बीच दूरी को मार्कर की चौड़ाई के प्रतिशत के रूप में लौटाता या सेट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Int32। |
| [GapWidth](../../aspose.slides.charts/chartseries/gapwidth) { get; } | बार या कॉलम क्लस्टर के बीच अंतराल को बार या कॉलम की चौड़ाई के प्रतिशत के रूप में निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Int32। |
| [HasSeriesLines](../../aspose.slides.charts/chartseries/hasserieslines) { get; } | यह निर्धारित करता है कि इस सीरीज़ और संबंधित सीरीज़ के लिए सीरीज़ लाइनें हैं या नहीं। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेट के लिए ParentSeriesGroup.SeriesLinesFormat प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Boolean। |
| [HasUpDownBars](../../aspose.slides.charts/chartseries/hasupdownbars) { get; } | यह निर्धारित करता है कि Line- या Stock-चार्ट में अप/डाउन बार हैं या नहीं। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेट के लिए ParentSeriesGroup.UpDownBars प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Boolean। |
| [InvertedSolidFillColor](../../aspose.slides.charts/chartseries/invertedsolidfillcolor) { get; } | सीरीज़ के लिये उल्टे ठोस रंग को निर्दिष्ट करता है। रंग सेटिंग लागू करने के लिए सीरीज़ फ़ॉर्मेट का FillType को FillType.Solid पर सेट करें। पढ़ने/लिखने योग्य [`ColorFormat`](../../aspose.slides/colorformat)। |
| [InvertIfNegative](../../aspose.slides.charts/chartseries/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो बार, कॉलम या बबल सीरीज़ के रंग को उलटने के लिये निर्दिष्ट करता है। पढ़ने/लिखने योग्य Boolean। |
| [IsColorVaried](../../aspose.slides.charts/chartseries/iscolorvaried) { get; } | यह निर्धारित करता है कि सीरीज़ के प्रत्येक डेटा मार्कर का रंग अलग है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह प्रॉपर्टी केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Boolean। |
| [Labels](../../aspose.slides.charts/chartseries/labels) { get; } | सीरीज़ के Labels लौटाता है। केवल-पढ़ने योग्य [`IDataLabelCollection`](../idatalabelcollection)। |
| [Marker](../../aspose.slides.charts/chartseries/marker) { get; } | Marker। केवल-पढ़ने योग्य [`IMarker`](../imarker)। |
| [Name](../../aspose.slides.charts/chartseries/name) { get; } | सीरीज़ का नाम लौटाता है। केवल-पढ़ने योग्य [`IStringChartValue`](../istringchartvalue)। |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/chartseries/numberformatofbubblesizes) { get; set; } | NumberFormatOfBubbleSizes। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfValues](../../aspose.slides.charts/chartseries/numberformatofvalues) { get; set; } | NumberFormatOfValues। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfXValues](../../aspose.slides.charts/chartseries/numberformatofxvalues) { get; set; } | NumberFormatOfXValues। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfYValues](../../aspose.slides.charts/chartseries/numberformatofyvalues) { get; set; } | NumberFormatOfYValues। पढ़ने/लिखने योग्य String। |
| [Order](../../aspose.slides.charts/chartseries/order) { get; set; } | सीरीज़ का क्रम लौटाता है। पढ़ने/लिखने योग्य Int32। |
| [Overlap](../../aspose.slides.charts/chartseries/overlap) { get; } | 2-D चार्ट में बार और कॉलम का ओवरलैप प्रतिशत (-100 % से 100 % तक) निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है, इसलिए यह केवल-पढ़ने योग्य है। मान बदलने के लिये !:ParentSeriesGroup.Overlap पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य SByte। |
| [ParentLabelLayout](../../aspose.slides.charts/chartseries/parentlabellayout) { get; set; } | पैरेंट कैटेगरी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट में लागू। |
| [ParentSeriesGroup](../../aspose.slides.charts/chartseries/parentseriesgroup) { get; } | ParentSeriesGroup। केवल-पढ़ने योग्य [`IChartSeriesGroup`](../ichartseriesgroup)। |
| [PieSplitBy](../../aspose.slides.charts/chartseries/piesplitby) { get; } | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट्स हों, यह निर्धारित करने की विधि को निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिये ParentSeriesGroup.PieSplitBy पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/chartseries/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी जिसमें वे डेटा पॉइंट्स शामिल हैं जो pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार में चित्रित किए जाएंगे। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। केवल-पढ़ने योग्य [`PieSplitCustomPointCollection`](../piesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/chartseries/piesplitposition) { get; } | एक मान को निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा पॉइंट्स pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार में हों। यह PieSplitBy प्रॉपर्टी के साथ उपयोग होता है। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिये ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिये ParentSeriesGroup.PieSplitPosition पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/chartseries/plotonsecondaxis) { get; set; } | यह दर्शाता है कि यह सीरीज़ द्वितीयक अक्ष पर प्लॉट की गई है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [QuartileMethod](../../aspose.slides.charts/chartseries/quartilemethod) { get; set; } | क्वार्टाइल विधि को दर्शाता है। केवल BoxAndWhisker चार्ट में लागू। |
| [RelatedLegendEntry](../../aspose.slides.charts/chartseries/relatedlegendentry) { get; } | इस सीरीज़ से संबंधित लेजेंड एंट्री को दर्शाता है। केवल-पढ़ने योग्य [`ILegendEntryProperties`](../ilegendentryproperties)। |
| [SecondPieSize](../../aspose.slides.charts/chartseries/secondpiesize) { get; } | pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5-200 % के बीच)। यह प्रॉपर्टी केवल इस सीरीज़ की नहीं, बल्कि पैरेंट सीरीज़ ग्रुप की सभी सीरीज़ की भी है – यह उपयुक्त समूह प्रॉपर्टी का प्रोजेक्शन है। इसलिए यह केवल-पढ़ने योग्य है। पैरेंट सीरीज़ ग्रुप तक पहुँचने के लिये ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिये ParentSeriesGroup.SecondPieSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल-पढ़ने योग्य UInt16। |
| [ShowConnectorLines](../../aspose.slides.charts/chartseries/showconnectorlines) { get; set; } | कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट में लागू। |
| [ShowInnerPoints](../../aspose.slides.charts/chartseries/showinnerpoints) { get; set; } | अंदरूनी बिंदु को दर्शाता है। यदि BoxAndWhisker चार्ट में अंदरूनी बिंदु दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट में लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowMeanLine](../../aspose.slides.charts/chartseries/showmeanline) { get; set; } | औसत रेखा को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत रेखा दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट में लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowMeanMarkers](../../aspose.slides.charts/chartseries/showmeanmarkers) { get; set; } | औसत मार्कर को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत मार्कर दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट में लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowOutlierPoints](../../aspose.slides.charts/chartseries/showoutlierpoints) { get; set; } | आउटलायर बिंदु को दर्शाता है। यदि BoxAndWhisker चार्ट में आउटलायर बिंदु दिखाए गए हों तो True। केवल BoxAndWhisker चार्ट में लागू। पढ़ने/लिखने योग्य Boolean। |
| [Smooth](../../aspose.slides.charts/chartseries/smooth) { get; set; } | वक्र स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट के लिए वक्र स्मूथिंग चालू हो तो True। केवल लाइन और स्कैटर (लाइन से जुड़ी) चार्ट में लागू। पढ़ने/लिखने योग्य Boolean। |
| [TrendLines](../../aspose.slides.charts/chartseries/trendlines) { get; } | सीरीज़ ट्रेंड लाइनों का संग्रह। केवल-पढ़ने योग्य [`ITrendlineCollection`](../itrendlinecollection)। |
| [Type](../../aspose.slides.charts/chartseries/type) { get; set; } | इस सीरीज़ का प्रकार लौटाता है। पढ़ने/लिखने योग्य [`ChartType`](../charttype)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/chartseries/getautomaticseriescolor)() | सीरीज़ इंडेक्स और चार्ट स्टाइल के आधार पर सीरीज़ का एक स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर है, तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |

### देखें

* इंटरफ़ेस [IChartSeries](../ichartseries)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
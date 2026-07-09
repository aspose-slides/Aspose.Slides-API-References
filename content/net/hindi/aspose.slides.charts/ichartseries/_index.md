---
title: IChartSeries
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चार्ट श्रृंखला का प्रतिनिधित्व करता है।
type: docs
weight: 1930
url: /hi/aspose.slides.charts/ichartseries/
---
## IChartSeries इंटरफ़ेस

चार्ट सीरीज का प्रतिनिधित्व करता है।

```csharp
public interface IChartSeries : IChartComponent
```

## गुण

| नाम | विवरण |
| --- | --- |
| [AsIChartComponent](../../aspose.slides.charts/ichartseries/asichartcomponent) { get; } | बेस IChartComponent इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल पढ़ने योग्य [`IChartComponent`](../ichartcomponent)। |
| [Bar3DShape](../../aspose.slides.charts/ichartseries/bar3dshape) { get; set; } | 3-D बार चार्ट की सीरीज के आकार को निर्दिष्ट करता है। इस प्रॉपर्टी का मान बदलने से स्वचालित रूप से सीरीज़ का प्रकार बदल सकता है। पढ़ने/लिखने योग्य [`ChartShapeType`](../chartshapetype)। |
| [BubbleSizeRepresentation](../../aspose.slides.charts/ichartseries/bubblesizerepresentation) { get; } | बबल चार्ट में बबल आकार के मानों को कैसे प्रस्तुत किया जाता है, यह निर्दिष्ट करता है। यह प्रॉपर्टी केवल इस सीरीज़ के लिए नहीं बल्कि पैरेंट सीरीज़ समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। पैरेंट सीरीज़ समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeRepresentation पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। |
| [BubbleSizeScale](../../aspose.slides.charts/ichartseries/bubblesizescale) { get; } | बबल चार्ट के लिए स्केल फ़ैक्टर निर्धारित करता है (डिफ़ॉल्ट आकार का 0-300 % तक)। यह प्रॉपर्टी पैरेंट सीरीज़ समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। पैरेंट समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.BubbleSizeScale पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। |
| [DataPoints](../../aspose.slides.charts/ichartseries/datapoints) { get; } | इस सीरीज़ के डेटा पॉइंट्स का संग्रह लौटाता है। केवल पढ़ने योग्य [`IChartDataPointCollection`](../ichartdatapointcollection)। |
| [DoughnutHoleSize](../../aspose.slides.charts/ichartseries/doughnutholesize) { get; } | डोनट चार्ट में छेद का आकार निर्धारित करता है (प्लॉट एरिया के आकार का 10-90 % तक)। यह प्रॉपर्टी पैरेंट सीरीज़ समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। पैरेंट समूह तक पहुँचने के लिए ParentSeriesGroup प्रॉपर्टी का उपयोग करें। मान बदलने के लिए ParentSeriesGroup.DoughnutHoleSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Byte। |
| [ErrorBarsXFormat](../../aspose.slides.charts/ichartseries/errorbarsxformat) { get; } | दिशा X वाले सीरीज़ के ErrorBars को दर्शाता है। X दिशा वाले ErrorBars area, bar, scatter और bubble प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य चार्ट प्रकार (जिसमें 3D चार्ट भी शामिल हैं) के लिए यह प्रॉपर्टी null लौटाती है। कस्टम मानों के लिये DataPoints संग्रह का उपयोग करके [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) प्रॉपर्टी के साथ मान निर्दिष्ट करें। केवल पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [ErrorBarsYFormat](../../aspose.slides.charts/ichartseries/errorbarsyformat) { get; } | दिशा Y वाले सीरीज़ के ErrorBars को दर्शाता है। Y दिशा वाले ErrorBars area, bar, line, scatter और bubble प्रकार की सीरीज़ के लिए उपलब्ध हैं। अन्य चार्ट प्रकार (जिसमें 3D चार्ट भी शामिल हैं) के लिए यह प्रॉपर्टी null लौटाती है। कस्टम मानों के लिये DataPoints संग्रह का उपयोग करके [`ErrorBarsCustomValues`](../ichartdatapoint/errorbarscustomvalues) प्रॉपर्टी के साथ मान निर्दिष्ट करें। केवल पढ़ने योग्य [`IErrorBarsFormat`](../ierrorbarsformat)। |
| [Explosion](../../aspose.slides.charts/ichartseries/explosion) { get; set; } | खुले पाई स्लाइस की दूरी को पाई चार्ट के केंद्र से पाई के व्यास के प्रतिशत में व्यक्त करता है। पढ़ने/लिखने योग्य Int32। |
| [FirstSliceAngle](../../aspose.slides.charts/ichartseries/firstsliceangle) { get; } | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में निर्दिष्ट करता है (ऊपर से घड़ी की दिशा में, 0-360 डिग्री)। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.FirstSliceAngle पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य UInt16। |
| [Format](../../aspose.slides.charts/ichartseries/format) { get; } | सीरीज़ का फ़ॉर्मेट लौटाता है। केवल पढ़ने योग्य [`IFormat`](../iformat)। |
| [GapDepth](../../aspose.slides.charts/ichartseries/gapdepth) { get; } | 3D चार्ट में डेटा सीरीज़ के बीच मार्कर चौड़ाई के प्रतिशत के रूप में दूरी को निर्दिष्ट करता है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.GapDepth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Int32। |
| [GapWidth](../../aspose.slides.charts/ichartseries/gapwidth) { get; } | बार या कॉलम क्लस्टर के बीच स्पेस को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.GapWidth पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Int32। |
| [HasSeriesLines](../../aspose.slides.charts/ichartseries/hasserieslines) { get; } | यह निर्धारित करता है कि इस सीरीज़ और संबंधित सीरीज़ के लिए सीरीज़ लाइन्स मौजूद हैं या नहीं। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.HasSeriesLines पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेट के लिए ParentSeriesGroup.SeriesLinesFormat प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Boolean। |
| [HasUpDownBars](../../aspose.slides.charts/ichartseries/hasupdownbars) { get; } | निर्धारित करता है कि लाइन- या स्टॉक-चार्ट में अप/डाउन बार हैं या नहीं। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.UpDownBars.HasUpDownBars पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। फ़ॉर्मेट के लिए ParentSeriesGroup.UpDownBars प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Boolean। |
| [InvertedSolidFillColor](../../aspose.slides.charts/ichartseries/invertedsolidfillcolor) { get; } | सीरीज़ के लिए उलटा ठोस रंग निर्दिष्ट करता है। रंग सेट करने के लिए सीरीज़ फ़ॉर्मेट का FillType को FillType.Solid पर सेट करें। पढ़ने/लिखने योग्य [`IColorFormat`](../../aspose.slides/icolorformat)। |
| [InvertIfNegative](../../aspose.slides.charts/ichartseries/invertifnegative) { get; set; } | यदि मान नकारात्मक है तो बार, कॉलम या बबल सीरीज़ अपने रंग उलटेगी। पढ़ने/लिखने योग्य Boolean। |
| [IsColorVaried](../../aspose.slides.charts/ichartseries/iscolorvaried) { get; } | निर्धारित करता है कि सीरीज़ के प्रत्येक डेटा मार्कर का रंग अलग है या नहीं। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिए ParentSeriesGroup.IsColorVaried पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Boolean। |
| [Labels](../../aspose.slides.charts/ichartseries/labels) { get; } | सीरीज़ की लेबल्स लौटाता है। केवल पढ़ने योग्य [`IDataLabelCollection`](../idatalabelcollection)। |
| [Marker](../../aspose.slides.charts/ichartseries/marker) { get; } | सीरीज़ मार्कर लौटाता है। केवल पढ़ने योग्य [`IMarker`](../imarker)। |
| [Name](../../aspose.slides.charts/ichartseries/name) { get; } | सीरीज़ का नाम लौटाता है। केवल पढ़ने योग्य [`IStringChartValue`](../istringchartvalue)। |
| [NumberFormatOfBubbleSizes](../../aspose.slides.charts/ichartseries/numberformatofbubblesizes) { get; set; } | सीरीज़ बबल आकारों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfValues](../../aspose.slides.charts/ichartseries/numberformatofvalues) { get; set; } | सीरीज़ मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfXValues](../../aspose.slides.charts/ichartseries/numberformatofxvalues) { get; set; } | सीरीज़ x मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ने/लिखने योग्य String। |
| [NumberFormatOfYValues](../../aspose.slides.charts/ichartseries/numberformatofyvalues) { get; set; } | सीरीज़ y मानों के लिए संख्या फ़ॉर्मेट लौटाता या सेट करता है। पढ़ने/लिखने योग्य String। |
| [Order](../../aspose.slides.charts/ichartseries/order) { get; set; } | सीरीज़ का क्रम लौटाता या सेट करता है। पढ़ने/लिखने योग्य Int32। |
| [Overlap](../../aspose.slides.charts/ichartseries/overlap) { get; } | 2-D चार्ट में बार और कॉलम के ओवरलैप प्रतिशत को (-100 % से 100 % तक) निर्धारित करता है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिये ParentSeriesGroup.Overlap पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य SByte। |
| [ParentLabelLayout](../../aspose.slides.charts/ichartseries/parentlabellayout) { get; set; } | पैरेंट श्रेणी लेबल्स का लेआउट दर्शाता है। केवल Treemap चार्ट पर लागू। |
| [ParentSeriesGroup](../../aspose.slides.charts/ichartseries/parentseriesgroup) { get; } | पैरेंट सीरीज़ समूह लौटाता है। केवल पढ़ने योग्य [`IChartSeriesGroup`](../ichartseriesgroup)। |
| [PieSplitBy](../../aspose.slides.charts/ichartseries/piesplitby) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में द्वितीय पाई या बार में कौन से डेटा पॉइंट्स हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिये ParentSeriesGroup.PieSplitBy पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य [`PieSplitType`](../piesplittype)। |
| [PieSplitCustomPoints](../../aspose.slides.charts/ichartseries/piesplitcustompoints) { get; } | कस्टम स्प्लिट जानकारी जो पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में द्वितीय पाई या बार में ड्रॉ की जाने वाली डेटा पॉइंट्स को रखती है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है। केवल पढ़ने योग्य [`IPieSplitCustomPointCollection`](../ipiesplitcustompointcollection)। |
| [PieSplitPosition](../../aspose.slides.charts/ichartseries/piesplitposition) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में द्वितीय पाई या बार में कौन से डेटा पॉइंट्स हैं, यह निर्धारित करने के लिये उपयोग किया जाने वाला मान निर्दिष्ट करता है। यह PieSplitBy प्रॉपर्टी के साथ उपयोग होता है। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिये ParentSeriesGroup.PieSplitPosition पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य Double। |
| [PlotOnSecondAxis](../../aspose.slides.charts/ichartseries/plotonsecondaxis) { get; set; } | दर्शाता है कि यह सीरीज़ द्वितीय मान अक्ष पर प्लॉट की गई है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [QuartileMethod](../../aspose.slides.charts/ichartseries/quartilemethod) { get; set; } | क्वारटाइल मेथड को दर्शाता है। केवल BoxAndWhisker चार्ट पर लागू। |
| [RelatedLegendEntry](../../aspose.slides.charts/ichartseries/relatedlegendentry) { get; } | इस सीरीज़ से संबंधित लेजेंड एंट्री को दर्शाता है। केवल पढ़ने योग्य [`ILegendEntryProperties`](../ilegendentryproperties)। |
| [SecondPieSize](../../aspose.slides.charts/ichartseries/secondpiesize) { get; } | पाई-ऑफ़-पाई या बार-ऑफ़-पाई चार्ट में द्वितीय पाई या बार का आकार, प्रथम पाई के आकार के प्रतिशत में (5-200 %)। यह प्रॉपर्टी पैरेंट समूह की सभी सीरीज़ के लिए प्रोजेक्शन है, इसलिए यह केवल पढ़ने योग्य है। मान बदलने के लिये ParentSeriesGroup.SecondPieSize पढ़ने/लिखने योग्य प्रॉपर्टी का उपयोग करें। केवल पढ़ने योग्य UInt16। |
| [ShowConnectorLines](../../aspose.slides.charts/ichartseries/showconnectorlines) { get; set; } | कनेक्टर लाइनों को दर्शाता है। केवल Waterfall चार्ट पर लागू। |
| [ShowInnerPoints](../../aspose.slides.charts/ichartseries/showinnerpoints) { get; set; } | अंदरूनी पॉइंट्स को दर्शाता है। यदि BoxAndWhisker चार्ट में अंदरूनी पॉइंट्स दिखाए गए हों तो true होता है। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowMeanLine](../../aspose.slides.charts/ichartseries/showmeanline) { get; set; } | औसत मार्कर्स को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत लाइन दिखायी गयी हो तो true होता है। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowMeanMarkers](../../aspose.slides.charts/ichartseries/showmeanmarkers) { get; set; } | औसत मार्कर्स को दर्शाता है। यदि BoxAndWhisker चार्ट में औसत मार्कर्स दिखाये गये हों तो true होता है। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean। |
| [ShowOutlierPoints](../../aspose.slides.charts/ichartseries/showoutlierpoints) { get; set; } | आउट्लायर पॉइंट्स को दर्शाता है। यदि BoxAndWhisker चार्ट में आउट्लायर पॉइंट्स दिखाये गये हों तो true होता है। केवल BoxAndWhisker चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean। |
| [Smooth](../../aspose.slides.charts/ichartseries/smooth) { get; set; } | कर्व स्मूथिंग को दर्शाता है। यदि लाइन चार्ट या स्कैटर चार्ट में कर्व स्मूथिंग चालू हो तो true होता है। केवल लाइन और स्कैटर (लाइनों से जुड़े) चार्ट पर लागू। पढ़ने/लिखने योग्य Boolean। |
| [TrendLines](../../aspose.slides.charts/ichartseries/trendlines) { get; } | सीरीज़ ट्रेंड लाइन्स का संग्रह। केवल पढ़ने योग्य [`ITrendlineCollection`](../itrendlinecollection)। |
| [Type](../../aspose.slides.charts/ichartseries/type) { get; set; } | इस सीरीज़ का प्रकार लौटाता या सेट करता है। पढ़ने/लिखने योग्य [`ChartType`](../charttype)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [GetAutomaticSeriesColor](../../aspose.slides.charts/ichartseries/getautomaticseriescolor)() | सीरीज़ इंडेक्स और चार्ट शैली के आधार पर सीरीज़ का स्वचालित रंग लौटाता है। यदि FillType NotDefined है तो यह रंग डिफ़ॉल्ट रूप से उपयोग किया जाता है। |

### देखें भी

* इंटरफ़ेस [IChartComponent](../ichartcomponent)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
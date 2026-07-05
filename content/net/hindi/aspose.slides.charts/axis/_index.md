---
title: Axis
second_title: Aspose.Sildes for .NET API संदर्भ
description: चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को समाहित करता है।
type: docs
weight: 1180
url: /hi/aspose.slides.charts/axis/
---
## Axis वर्ग

चार्ट के अक्ष को प्रतिनिधित्व करने वाले वस्तु को समाहित करता है।

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | अक्ष का वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | अक्ष का वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | अक्ष पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | अक्ष का वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | अक्ष का वास्तविक लघु इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | अक्ष पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने हेतु पहले IChart.ValidateChartLayout() विधि को कॉल करें। |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | वर्गीकरण अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | निर्दिष्ट करता है कि मान अक्ष वर्गीकरण अक्ष के बीच श्रेणियों के बीच क्रॉस करता है या नहीं। यह गुण केवल वर्गीकरण अक्षों पर लागू होता है और 3-डी चार्ट पर लागू नहीं होता। पढ़ें/लिखें Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | तिथि अक्ष पर प्रदर्शित सबसे छोटी समय इकाई निर्दिष्ट करता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | जब AggregationType गुण का मान AxisAggregationType.ByBinWidth हो तो बिन चौड़ाई निर्दिष्ट करता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | वर्गीकरण अक्ष का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | अक्ष पर वह बिंदु दर्शाता है जहाँ लम्बवत अक्ष इसका प्रतिच्छेदन करता है। पढ़ें/लिखें Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | निर्दिष्ट अक्ष पर जहाँ दूसरा अक्ष प्रतिच्छेद करता है, उसके CrossType को दर्शाता है। पढ़ें/लिखें [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | मान अक्ष के प्रदर्शन इकाइयों के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें/लिखें [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | अक्ष का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | निर्धारित करता है कि क्या अक्ष का दिखाई देने वाला शीर्षक है। पढ़ें/लिखें Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | यह दर्शाता है कि अक्ष की प्रमुख इकाई स्वचालित रूप से असाइन की गई है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | यह दर्शाता है कि अधिकतम मान स्वचालित रूप से असाइन किया गया है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | यह दर्शाता है कि अक्ष की लघु इकाई स्वचालित रूप से असाइन की गई है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | यह दर्शाता है कि न्यूनतम मान स्वचालित रूप से असाइन किया गया है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो OverflowBin गुण का उपयोग करें। |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | स्वचालित टिक लेबल अंतराल मान निर्दिष्ट करता है। यदि false हो तो TickLabelSpacing गुण का उपयोग करें। पढ़ें/लिखें Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | स्वचालित टिक मार्क अंतराल मान निर्दिष्ट करता है। यदि false हो तो TickMarksSpacing गुण का उपयोग करें। पढ़ें/लिखें Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो UnderflowBin गुण का उपयोग करें। |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | दर्शाता है कि मान अक्ष का स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ें/लिखें Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | यह दर्शाता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | यदि ओवरफ़्लो बिन लागू है तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | दर्शाता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | यदि अंडरफ़्लो बिन लागू है तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | दर्शाता है कि अक्ष दृश्यमान है या नहीं। पढ़ें/लिखें Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | लेबल को अक्ष से दूरी निर्दिष्ट करता है। वर्गीकरण या तिथि अक्ष पर लागू। मान 0 % से 1000 % के बीच होना चाहिए। पढ़ें/लिखें UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | लॉगरिदमिक आधार दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | चार्ट के अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | तिथि या मान अक्ष के लिए प्रमुख इकाइयाँ दर्शाता है। पढ़ें/लिखें Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | मान अक्ष पर अधिकतम मान दर्शाता है। पढ़ें/लिखें Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | चार्ट के अक्ष पर लघु ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | निर्दिष्ट अक्ष के लिए लघु टिक मार्क प्रकार दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | तिथि या मान अक्ष के लिए लघु इकाइयाँ दर्शाता है। पढ़ें/लिखें Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | मान अक्ष पर न्यूनतम मान दर्शाता है। पढ़ें/लिखें Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | अक्ष लेबल के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें/लिखें String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | जब AggregationType का मान AxisAggregationType.ByNumberOfBins हो तो बिन की संख्या निर्दिष्ट करता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin false और IsOverflowBin true हो तब लागू। |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | अक्ष की स्थिति दर्शाता है। पढ़ें/लिखें [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | प्रमुख ग्रिडलाइन को छिपाने हेतु MajorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill सेट करें। केवल-पढ़ने योग्य Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | लघु ग्रिडलाइन को छिपाने हेतु MinorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill सेट करें। केवल-पढ़ने योग्य Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | टेक्स्ट का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ें/लिखें [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | टिक लेबल के घूर्णन कोण को दर्शाता है। पढ़ें/लिखें Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | यह निर्दिष्ट करता है कि ड्रॉ किए गए लेबल के बीच कितने टिक लेबल छोड़े जाएँ। वर्गीकरण या श्रृंखला अक्ष पर लागू। पढ़ें/लिखें UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | यह निर्दिष्ट करता है कि अगला टिक मार्क ड्रॉ करने से पहले कितने टिक मार्क छोड़ें। वर्गीकरण या श्रृंखला अक्ष पर लागू। पढ़ें/लिखें UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | अक्ष का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin false और IsUnderflowBin true हो तब लागू। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType गुण को ऐसी मान से सेट करता है जो अक्ष डेटा के आधार पर स्वचालित रूप से निर्धारित हो। |

### देखें

* वर्ग [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* वर्ग [AxesManager](../axesmanager)
* इंटरफ़ेस [IAxis](../iaxis)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
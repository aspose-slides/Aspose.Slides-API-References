---
title: Axis
second_title: Aspose.Sildes for .NET API संदर्भ
description: ऑब्जेक्ट को संलग्न करता है जो चार्ट की अक्ष को दर्शाता है।
type: docs
weight: 1180
url: /hi/aspose.slides.charts/axis/
---
## Axis वर्ग

Encapsulates the object that represents a chart's axis.

```csharp
public class Axis : DomObject<AxesManager>, IAxis
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/axis/actualmajorunit) { get; } | एक्सिस की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMajorUnitScale](../../aspose.slides.charts/axis/actualmajorunitscale) { get; } | एक्सिस के वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMaxValue](../../aspose.slides.charts/axis/actualmaxvalue) { get; } | एक्सिस पर वास्तविक अधिकतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnit](../../aspose.slides.charts/axis/actualminorunit) { get; } | एक्सिस की वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnitScale](../../aspose.slides.charts/axis/actualminorunitscale) { get; } | एक्सिस के वास्तविक लघु इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinValue](../../aspose.slides.charts/axis/actualminvalue) { get; } | एक्सिस पर वास्तविक न्यूनतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [AggregationType](../../aspose.slides.charts/axis/aggregationtype) { get; set; } | श्रेणी एक्सिस (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [AxisBetweenCategories](../../aspose.slides.charts/axis/axisbetweencategories) { get; set; } | निर्दिष्ट करता है कि मान एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच काटता है या नहीं। यह प्रॉपर्टी केवल श्रेणी एक्सिस पर लागू होती है, और 3-डी चार्ट्स पर लागू नहीं होती। पढ़ें/लिखें Boolean. |
| [BaseUnitScale](../../aspose.slides.charts/axis/baseunitscale) { get; set; } | डेट़ एक्सिस पर दर्शाए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [BinWidth](../../aspose.slides.charts/axis/binwidth) { get; set; } | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट किया जाता है, तो बिन की चौड़ाई निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू होता है। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [CategoryAxisType](../../aspose.slides.charts/axis/categoryaxistype) { get; set; } | श्रेणी एक्सिस का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [`CategoryAxisType`](../categoryaxistype). |
| [Chart](../../aspose.slides.charts/axis/chart) { get; } | पेरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [`IChart`](../ichart). |
| [CrossAt](../../aspose.slides.charts/axis/crossat) { get; set; } | एक्सिस पर वह बिंदु दर्शाता है जहाँ लंबवत एक्सिस इसे काटता है। पढ़ें/लिखें Single. |
| [CrossType](../../aspose.slides.charts/axis/crosstype) { get; set; } | निर्दिष्ट एक्सिस पर जहाँ अन्य एक्सिस क्रॉस करता है, वहाँ के CrossType को दर्शाता है। पढ़ें/लिखें [`CrossesType`](../crossestype). |
| [DisplayUnit](../../aspose.slides.charts/axis/displayunit) { get; set; } | मान एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें/लिखें [`DisplayUnitType`](../displayunittype). |
| [Format](../../aspose.slides.charts/axis/format) { get; } | एक्सिस का फ़ॉर्मैट दर्शाता है। केवल-पढ़ने योग्य [`IAxisFormat`](../iaxisformat). |
| [HasTitle](../../aspose.slides.charts/axis/hastitle) { get; set; } | निर्धारित करता है कि एक्सिस का शीर्षक दृश्य है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/axis/isautomaticmajorunit) { get; set; } | संकेत करता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से निर्धारित है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMaxValue](../../aspose.slides.charts/axis/isautomaticmaxvalue) { get; set; } | संकेत करता है कि अधिकतम मान स्वचालित रूप से निर्धारित है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/axis/isautomaticminorunit) { get; set; } | संकेत करता है कि एक्सिस की लघु इकाई स्वचालित रूप से निर्धारित है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticMinValue](../../aspose.slides.charts/axis/isautomaticminvalue) { get; set; } | संकेत करता है कि न्यूनतम मान स्वचालित रूप से निर्धारित है या नहीं। पढ़ें/लिखें Boolean. |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/axis/isautomaticoverflowbin) { get; set; } | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का उपयोग करें। |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/axis/isautomaticticklabelspacing) { get; set; } | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें Boolean. |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/axis/isautomatictickmarksspacing) { get; set; } | स्वचालित टिक चिह्न स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें Boolean. |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/axis/isautomaticunderflowbin) { get; set; } | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का उपयोग करें। |
| [IsLogarithmic](../../aspose.slides.charts/axis/islogarithmic) { get; set; } | निर्दिष्ट करता है कि मान एक्सिस का स्केल प्रकार लोगारिदमिक है या नहीं। पढ़ें/लिखें Boolean. |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/axis/isnumberformatlinkedtosource) { get; set; } | संकेत करता है कि फ़ॉर्मैट लिंक्ड स्रोत डेटा से है। पढ़ें/लिखें Boolean. |
| [IsOverflowBin](../../aspose.slides.charts/axis/isoverflowbin) { get; set; } | निर्दिष्ट करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने हेतु IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| [IsPlotOrderReversed](../../aspose.slides.charts/axis/isplotorderreversed) { get; set; } | निर्दिष्ट करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें Boolean. |
| [IsUnderflowBin](../../aspose.slides.charts/axis/isunderflowbin) { get; set; } | निर्दिष्ट करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने हेतु IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| [IsVisible](../../aspose.slides.charts/axis/isvisible) { get; set; } | निर्दिष्ट करता है कि एक्सिस दृश्य है या नहीं। पढ़ें/लिखें Boolean. |
| [LabelOffset](../../aspose.slides.charts/axis/labeloffset) { get; set; } | लेबल्स की एक्सिस से दूरी को निर्दिष्ट करता है। श्रेणी या डेट एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें UInt16. |
| [LogBase](../../aspose.slides.charts/axis/logbase) { get; set; } | लॉगारिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें Double. |
| [MajorGridLinesFormat](../../aspose.slides.charts/axis/majorgridlinesformat) { get; } | एक चार्ट एक्सिस पर प्रमुख ग्रिडलाइन का फ़ॉर्मैट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat). |
| [MajorTickMark](../../aspose.slides.charts/axis/majortickmark) { get; set; } | निर्दिष्ट एक्सिस के प्रमुख टिक मार्क के प्रकार को दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype). |
| [MajorUnit](../../aspose.slides.charts/axis/majorunit) { get; set; } | डेट या वैल्यू एक्सिस के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ें/लिखें Double. |
| [MajorUnitScale](../../aspose.slides.charts/axis/majorunitscale) { get; set; } | डेट एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [MaxValue](../../aspose.slides.charts/axis/maxvalue) { get; set; } | वैल्यू एक्सिस पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें Double. |
| [MinorGridLinesFormat](../../aspose.slides.charts/axis/minorgridlinesformat) { get; } | एक चार्ट एक्सिस पर लघु ग्रिडलाइन का फ़ॉर्मैट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat). |
| [MinorTickMark](../../aspose.slides.charts/axis/minortickmark) { get; set; } | निर्दिष्ट एक्सिस के लघु टिक मार्क के प्रकार को दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype). |
| [MinorUnit](../../aspose.slides.charts/axis/minorunit) { get; set; } | डेट या वैल्यू एक्सिस के लिए लघु इकाइयों को दर्शाता है। पढ़ें/लिखें Double. |
| [MinorUnitScale](../../aspose.slides.charts/axis/minorunitscale) { get; set; } | डेट एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype). |
| [MinValue](../../aspose.slides.charts/axis/minvalue) { get; set; } | वैल्यू एक्सिस पर न्यूनतम मान को दर्शाता है। पढ़ें/लिखें Double. |
| [NumberFormat](../../aspose.slides.charts/axis/numberformat) { get; set; } | Axis Labels के लिए फ़ॉर्मैट स्ट्रिंग को दर्शाता है। पढ़ें/लिखें String. |
| [NumberOfBins](../../aspose.slides.charts/axis/numberofbins) { get; set; } | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट किया जाता है, तब बिन की संख्या निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [OverflowBin](../../aspose.slides.charts/axis/overflowbin) { get; set; } | ओवरफ़्लो बिन कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट हो और IsOverflowBin प्रॉपर्टी true हो तब लागू होता है। |
| [Position](../../aspose.slides.charts/axis/position) { get; set; } | एक्सिस की स्थिति दर्शाता है। पढ़ें/लिखें [`AxisPositionType`](../axispositiontype). |
| [ShowMajorGridLines](../../aspose.slides.charts/axis/showmajorgridlines) { get; } | मुख्य ग्रिडलाइन को छुपाने के लिए MajorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। केवल-पढ़ने योग्य Boolean. |
| [ShowMinorGridLines](../../aspose.slides.charts/axis/showminorgridlines) { get; } | लघु ग्रिडलाइन को छुपाने के लिए MinorGridLinesFormat.Line.FillFormat.FillType को FillType.NoFill पर सेट करें। केवल-पढ़ने योग्य Boolean. |
| [TextFormat](../../aspose.slides.charts/axis/textformat) { get; } | टेक्स्ट का फ़ॉर्मैट दर्शाता है। केवल-पढ़ने योग्य [`IChartTextFormat`](../icharttextformat). |
| [TickLabelPosition](../../aspose.slides.charts/axis/ticklabelposition) { get; set; } | निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति को दर्शाता है। पढ़ें/लिखें [`TickLabelPositionType`](../ticklabelpositiontype). |
| [TickLabelRotationAngle](../../aspose.slides.charts/axis/ticklabelrotationangle) { get; set; } | टिक लेबल्स का घुमाव कोण दर्शाता है। पढ़ें/लिखें Single. |
| [TickLabelSpacing](../../aspose.slides.charts/axis/ticklabelspacing) { get; set; } | ड्रॉ किए गए लेबल के बीच कितने टिक लेबल छोड़ने हैं, इसे निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। पढ़ें/लिखें UInt32. |
| [TickMarksSpacing](../../aspose.slides.charts/axis/tickmarksspacing) { get; set; } | अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ने हैं, इसे निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। पढ़ें/लिखें UInt16. |
| [Title](../../aspose.slides.charts/axis/title) { get; } | एक्सिस का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle). |
| [UnderflowBin](../../aspose.slides.charts/axis/underflowbin) { get; set; } | अंडरफ़्लो बिन कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट हो और IsUnderflowBin प्रॉपर्टी true हो तब लागू होता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/axis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType प्रॉपर्टी को एक ऐसे मान से सेट करता है जो एक्सिस डेटा के आधार पर स्वचालित रूप से निर्धारित किया जाता है। |

### देखें

* वर्ग [DomObject&lt;TParent&gt;](../../aspose.slides/domobject-1)
* वर्ग [AxesManager](../axesmanager)
* इंटरफ़ेस [IAxis](../iaxis)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
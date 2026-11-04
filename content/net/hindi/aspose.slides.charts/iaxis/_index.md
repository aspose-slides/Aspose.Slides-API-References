---
title: IAxis
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक चार्ट के एक्सिस को दर्शाने वाले ऑब्जेक्ट को संलग्न करता है।
type: docs
weight: 1720
url: /hi/aspose.slides.charts/iaxis/
---
## IAxis इंटरफ़ेस

एक चार्ट के एक्सिस को दर्शाने वाले ऑब्जेक्ट को संलग्न करता है।

```csharp
public interface IAxis : IFormattedTextContainer
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | एक्सिस की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | एक्सिस की वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | एक्सिस पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | एक्सिस की वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | एक्सिस की वास्तविक लघु इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | एक्सिस पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | श्रेणी एक्सिस (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है। |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | आधार IFormattedTextContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFormattedTextContainer`](../iformattedtextcontainer)। |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | यह दर्शाता है कि मान एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच पार करता है या नहीं। यह प्रॉपर्टी केवल श्रेणी एक्सिस पर लागू होती है, और 3-डी चार्ट्स पर लागू नहीं होती। पढ़ें/लिखें बूलियन। |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | डेट अक्सिस पर प्रतिनिधित्व की गई सबसे छोटी समय इकाई निर्दिष्ट करता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype)। |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByBinWidth पर सेट हो तो बिन की चौड़ाई निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है। |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | श्रेणी एक्सिस का प्रकार निर्दिष्ट करता है। पढ़ें/लिखें [`CategoryAxisType`](./categoryaxistype)। |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्बवत एक्सिस इसे पार करता है। पढ़ें/लिखें सिंगल। |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | निर्दिष्ट एक्सिस पर जहाँ अन्य एक्सिस पार करता है, वहाँ का CrossType दर्शाता है। पढ़ें/लिखें [`CrossesType`](../crossestype)। |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | मान एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें/लिखें [`DisplayUnitType`](../displayunittype)। |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | एक्सिस का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IAxisFormat`](../iaxisformat)। |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | निर्धारित करता है कि एक्सिस का शीर्षक दृश्यमान है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | बताता है कि एक्सिस की प्रमुख इकाई स्वचालित रूप से निर्धारित होती है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | बताता है कि अधिकतम मान स्वचालित रूप से निर्धारित होता है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | बताता है कि एक्सिस की लघु इकाई स्वचालित रूप से निर्धारित होती है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | बताता है कि न्यूनतम मान स्वचालित रूप से निर्धारित होता है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | स्वचालित ओवरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: OverflowBin प्रॉपर्टी का उपयोग करें। |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | स्वचालित टिक लेबल स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickLabelSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें बूलियन। |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | स्वचालित टिक मार्क्स स्पेसिंग मान को निर्दिष्ट करता है। यदि false: TickMarksSpacing प्रॉपर्टी का उपयोग करें। पढ़ें/लिखें बूलियन। |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | स्वचालित अंडरफ़्लो बिन मान को निर्दिष्ट करता है। यदि false: UnderflowBin प्रॉपर्टी का उपयोग करें। |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | बताता है कि मान एक्सिस स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | बताता है कि फ़ॉर्मेट स्रोत डेटा से जुड़ा है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | निर्धारित करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | बताता है कि MS PowerPoint डेटा पॉइंट्स को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ें/लिखें बूलियन। |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | निर्धारित करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | बताता है कि एक्सिस दृश्यमान है या नहीं। पढ़ें/लिखें बूलियन। |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | लेबल्स की एक्सिस से दूरी निर्दिष्ट करता है। श्रेणी या तिथि एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें/लिखें UInt16। |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | लॉगरिदमिक बेस दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें/लिखें Double। |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | चार्ट एक्सिस पर प्रमुख ग्रिडलाइन का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | निर्दिष्ट एक्सिस के प्रमुख टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype)। |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | तिथि या मान एक्सिस के प्रमुख इकाइयों को दर्शाता है। पढ़ें/लिखें Double। |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | तिथि एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype)। |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | मान एक्सिस पर अधिकतम मान को दर्शाता है। पढ़ें/लिखें Double। |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | चार्ट एक्सिस पर लघु ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | निर्दिष्ट एक्सिस के लघु टिक मार्क प्रकार को दर्शाता है। पढ़ें/लिखें [`TickMarkType`](../tickmarktype)। |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | तिथि या मान एक्सिस के लघु इकाइयों को दर्शाता है। पढ़ें/लिखें Double। |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | तिथि एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें/लिखें [`TimeUnitType`](../timeunittype)। |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | मान एक्सिस पर न्यूनतम मान को दर्शाता है। पढ़ें/लिखें Double। |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | एक्सिस लेबल्स के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें/लिखें String। |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | जब AggregationType प्रॉपर्टी का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तो बिनों की संख्या को निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto सीरीज़ के साथ उपयोग किया जाता है। |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | ओवरफ़्लो बिन के कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट हो और IsOverflowBin प्रॉपर्टी true हो, तब लागू। |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | एक्सिस की स्थिति को दर्शाता है। पढ़ें/लिखें [`AxisPositionType`](../axispositiontype)। |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | बताता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य बूलियन। |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | बताता है कि लघु ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य बूलियन। |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति को दर्शाता है। पढ़ें/लिखें [`TickLabelPositionType`](../ticklabelpositiontype)। |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | टिक लेबल्स के घूर्णन कोण को दर्शाता है। पढ़ें/लिखें Single। |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | ड्रॉ किए गए लेबल के बीच कितने टिक लेबल छोड़ें, इसे निर्दिष्ट करता है। पढ़ें/लिखें UInt32। |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | अगले टिक मार्क के ड्रॉ होने से पहले कितने टिक मार्क छोड़ें, इसे निर्दिष्ट करता है। श्रेणी या सीरीज़ एक्सिस पर लागू। पढ़ें/लिखें UInt16। |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | एक्सिस का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle)। |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | अंडरफ़्लो बिन के कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट हो और IsUnderflowBin प्रॉपर्टी true हो, तब लागू। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType प्रॉपर्टी को उस मान से सेट करता है जो एक्सिस डेटा के आधार पर स्वतः निर्धारित किया जाता है। |

### देखें

* इंटरफ़ेस [IFormattedTextContainer](../iformattedtextcontainer)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
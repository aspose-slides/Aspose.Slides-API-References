---
title: IAxis
second_title: Aspose.Sildes for .NET API संदर्भ
description: एक चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को संलग्न करता है।
type: docs
weight: 1710
url: /hi/aspose.slides.charts/iaxis/
---
## IAxis इंटरफ़ेस

एक चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को संलग्न करता है।

```csharp
public interface IAxis : IFormattedTextContainer
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | अक्ष की वास्तविक प्रमुख इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | अक्ष की वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | अक्ष पर वास्तविक अधिकतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | अक्ष की वास्तविक लघु इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | अक्ष की वास्तविक लघु इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | अक्ष पर वास्तविक न्यूनतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | बेस IFormattedTextContainer इंटरफ़ेस को प्राप्त करने की अनुमति देता है। केवल-पढ़ने योग्य [`IFormattedTextContainer`](../iformattedtextcontainer)। |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | निर्दिष्ट करता है कि मान अक्ष श्रेणियों के बीच श्रेणी अक्ष को पार करता है या नहीं। यह प्रॉपर्टी केवल श्रेणी अक्षों पर लागू होती है, और 3-डी चार्ट पर लागू नहीं होती। पढ़ने/लिखने योग्य Boolean। |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | तारीख अक्ष पर प्रतिनिधित्व किया गया सबसे छोटा समय इकाई निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`TimeUnitType`](../timeunittype)। |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByBinWidth पर सेट किया जाता है, तो बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | श्रेणी अक्ष के प्रकार को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`CategoryAxisType`](./categoryaxistype)। |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | अक्ष पर वह बिंदु दर्शाता है जहाँ लम्बवत अक्ष इसे पार करता है। पढ़ने/लिखने योग्य Single। |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | निर्दिष्ट अक्ष पर जहाँ अन्य अक्ष पार करता है, उस स्थान का CrossType दर्शाता है। पढ़ने/लिखने योग्य [`CrossesType`](../crossestype)। |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | मान अक्ष के डिस्प्ले इकाइयों के स्केलिंग मान को निर्दिष्ट करता है। पढ़ने/लिखने योग्य [`DisplayUnitType`](../displayunittype)। |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | अक्ष का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IAxisFormat`](../iaxisformat)। |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | निर्धारित करता है कि अक्ष का शीर्षक दृश्य है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | सूचित करता है कि अक्ष की प्रमुख इकाई स्वचालित रूप से आवंटित है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | सूचित करता है कि अधिकतम मान स्वचालित रूप से आवंटित है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | सूचित करता है कि अक्ष की लघु इकाई स्वचालित रूप से आवंटित है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | सूचित करता है कि न्यूनतम मान स्वचालित रूप से आवंटित है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है: OverflowBin प्रॉपर्टी का उपयोग करें। |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false है: TickLabelSpacing प्रॉपर्टी का उपयोग करें। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | स्वचालित टिक मार्क स्पेसिंग मान निर्दिष्ट करता है। यदि false है: TickMarksSpacing प्रॉपर्टी का उपयोग करें। पढ़ने/लिखने योग्य Boolean। |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है: UnderflowBin प्रॉपर्टी का उपयोग करें। |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | निर्दिष्ट करता है कि मान अक्ष का स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | सूचित करता है कि फ़ॉर्मेट लिंक्ड स्रोत डेटा है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | निर्दिष्ट करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | निर्दिष्ट करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | निर्दिष्ट करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | निर्दिष्ट करता है कि अक्ष दृश्यमान है या नहीं। पढ़ने/लिखने योग्य Boolean। |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | अक्ष से लेबलों की दूरी निर्दिष्ट करता है। श्रेणी या तारीख अक्ष पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ने/लिखने योग्य UInt16। |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | लॉगरिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ने/लिखने योग्य Double। |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | निर्दिष्ट अक्ष पर प्रमुख टिक मार्क के प्रकार को दर्शाता है। पढ़ने/लिखने योग्य [`TickMarkType`](../tickmarktype)। |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | तारीख या मान अक्ष के लिए प्रमुख इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य Double। |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ने/लिखने योग्य [`TimeUnitType`](../timeunittype)। |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | मान अक्ष पर अधिकतम मान को दर्शाता है। पढ़ने/लिखने योग्य Double। |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | चार्ट अक्ष पर लघु ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | निर्दिष्ट अक्ष पर लघु टिक मार्क के प्रकार को दर्शाता है। पढ़ने/लिखने योग्य [`TickMarkType`](../tickmarktype)। |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | तारीख या मान अक्ष के लिए लघु इकाइयों को दर्शाता है। पढ़ने/लिखने योग्य Double। |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | तारीख अक्ष के लिए प्रमुख इकाई स्केल को दर्शाता है। पढ़ने/लिखने योग्य [`TimeUnitType`](../timeunittype)। |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | मान अक्ष पर न्यूनतम मान को दर्शाता है। पढ़ने/लिखने योग्य Double। |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | अक्ष लेबल के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ने/लिखने योग्य String। |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | जब AggregationType प्रॉपर्टी मान AxisAggregationType.ByNumberOfBins पर सेट किया जाता है, तो बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | ओवरफ़्लो बिन कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticOverflowBin प्रॉपर्टी false पर सेट होती है और IsOverflowBin प्रॉपर्टी true होती है, तब लागू। |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | अक्ष की स्थिति को दर्शाता है। पढ़ने/लिखने योग्य [`AxisPositionType`](../axispositiontype)। |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | निर्दिष्ट करता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य Boolean। |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | निर्दिष्ट करता है कि लघु ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने योग्य Boolean। |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति को दर्शाता है। पढ़ने/लिखने योग्य [`TickLabelPositionType`](../ticklabelpositiontype)। |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | टिक लेबल का घूर्णन कोण दर्शाता है। पढ़ने/लिखने योग्य Single। |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | ड्रॉ किए गए लेबल के बीच कितने टिक लेबल को छोड़ना है, यह निर्दिष्ट करता है। पढ़ने/लिखने योग्य UInt32। |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | अगला टिक मार्क ड्रॉ करने से पहले कितने टिक मार्क को छोड़ना है, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ने/लिखने योग्य UInt16। |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | अक्ष का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [`IChartTitle`](../icharttitle)। |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | अंडरफ़्लो बिन कस्टम मान को निर्दिष्ट करता है। जब IsAutomaticUnderflowBin प्रॉपर्टी false पर सेट होती है और IsUnderflowBin प्रॉपर्टी true होती है, तब लागू। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType प्रॉपर्टी को एक मान सेट करता है जो अक्ष डेटा के आधार पर स्वचालित रूप से निर्धारित होता है। |

### देखें

* इंटरफ़ेस [IFormattedTextContainer](../iformattedtextcontainer)
* नामस्थान [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
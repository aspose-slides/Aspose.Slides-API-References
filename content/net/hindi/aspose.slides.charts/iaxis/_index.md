---
title: IAxis
second_title: Aspose.Sildes के लिए .NET API संदर्भ
description: एक वस्तु को संलग्न करता है जो चार्ट के अक्ष का प्रतिनिधित्व करती है।
type: docs
weight: 1710
url: /hi/aspose.slides.charts/iaxis/
---
## IAxis इंटरफ़ेस

एक वस्तु को संलग्न करता है जो चार्ट के अक्ष का प्रतिनिधित्व करती है।

```csharp
public interface IAxis : IFormattedTextContainer
```

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| [ActualMajorUnit](../../aspose.slides.charts/iaxis/actualmajorunit) { get; } | अक्ष की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMajorUnitScale](../../aspose.slides.charts/iaxis/actualmajorunitscale) { get; } | अक्ष की वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMaxValue](../../aspose.slides.charts/iaxis/actualmaxvalue) { get; } | अक्ष पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnit](../../aspose.slides.charts/iaxis/actualminorunit) { get; } | अक्ष की वास्तविक गौण इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinorUnitScale](../../aspose.slides.charts/iaxis/actualminorunitscale) { get; } | अक्ष की वास्तविक गौण इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [ActualMinValue](../../aspose.slides.charts/iaxis/actualminvalue) { get; } | अक्ष पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले IChart.ValidateChartLayout() मेथड को कॉल करें। |
| [AggregationType](../../aspose.slides.charts/iaxis/aggregationtype) { get; set; } | श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। केवल श्रेणियों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [AsIFormattedTextContainer](../../aspose.slides.charts/iaxis/asiformattedtextcontainer) { get; } | आधार IFormattedTextContainer इंटरफ़ेस प्राप्त करने की अनुमति देता है। केवल-पढ़ने-योग्य [`IFormattedTextContainer`](../iformattedtextcontainer)। |
| [AxisBetweenCategories](../../aspose.slides.charts/iaxis/axisbetweencategories) { get; set; } | निर्देशित करता है कि क्या मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच पार करता है। यह गुण केवल श्रेणी अक्षों पर लागू होता है और 3-डी चार्ट पर लागू नहीं होता। पढ़ने-लिखने-योग्य Boolean। |
| [BaseUnitScale](../../aspose.slides.charts/iaxis/baseunitscale) { get; set; } | डेट़ अक्ष पर दर्शाए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ने-लिखने-योग्य [`TimeUnitType`](../timeunittype)। |
| [BinWidth](../../aspose.slides.charts/iaxis/binwidth) { get; set; } | जब AggregationType गुण का मान AxisAggregationType.ByBinWidth पर सेट हो, तब बिन चौड़ाई निर्दिष्ट करता है। श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [CategoryAxisType](../../aspose.slides.charts/iaxis/categoryaxistype) { get; set; } | श्रेणी अक्ष के प्रकार को निर्दिष्ट करता है। पढ़ने-लिखने-योग्य [`CategoryAxisType`](./categoryaxistype)। |
| [CrossAt](../../aspose.slides.charts/iaxis/crossat) { get; set; } | अक्ष पर वह बिंदु दर्शाता है जहाँ लंबवत अक्ष इसे काटता है। पढ़ने-लिखने-योग्य Single। |
| [CrossType](../../aspose.slides.charts/iaxis/crosstype) { get; set; } | निर्दिष्ट अक्ष पर जहाँ अन्य अक्ष काटता है, उस पर CrossType दर्शाता है। पढ़ने-लिखने-योग्य [`CrossesType`](../crossestype)। |
| [DisplayUnit](../../aspose.slides.charts/iaxis/displayunit) { get; set; } | मान अक्ष के डिस्प्ले इकाइयों के स्केलिंग मान को निर्दिष्ट करता है। पढ़ने-लिखने-योग्य [`DisplayUnitType`](../displayunittype)। |
| [Format](../../aspose.slides.charts/iaxis/format) { get; } | अक्ष का फॉर्मेट दर्शाता है। केवल-पढ़ने-योग्य [`IAxisFormat`](../iaxisformat)। |
| [HasTitle](../../aspose.slides.charts/iaxis/hastitle) { get; set; } | निर्धारित करता है कि क्या अक्ष का शीर्षक दृश्यमान है। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticMajorUnit](../../aspose.slides.charts/iaxis/isautomaticmajorunit) { get; set; } | निर्दिष्ट करता है कि क्या अक्ष की प्रमुख इकाई स्वचालित रूप से निर्धारित होती है। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticMaxValue](../../aspose.slides.charts/iaxis/isautomaticmaxvalue) { get; set; } | निर्दिष्ट करता है कि क्या अधिकतम मान स्वचालित रूप से निर्धारित होता है। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticMinorUnit](../../aspose.slides.charts/iaxis/isautomaticminorunit) { get; set; } | निर्दिष्ट करता है कि क्या अक्ष की गौण इकाई स्वचालित रूप से निर्धारित होती है। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticMinValue](../../aspose.slides.charts/iaxis/isautomaticminvalue) { get; set; } | निर्दिष्ट करता है कि क्या न्यूनतम मान स्वचालित रूप से निर्धारित होता है। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticOverflowBin](../../aspose.slides.charts/iaxis/isautomaticoverflowbin) { get; set; } | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: OverflowBin गुण का उपयोग करें। |
| [IsAutomaticTickLabelSpacing](../../aspose.slides.charts/iaxis/isautomaticticklabelspacing) { get; set; } | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickLabelSpacing गुण का उपयोग करें। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticTickMarksSpacing](../../aspose.slides.charts/iaxis/isautomatictickmarksspacing) { get; set; } | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false: TickMarksSpacing गुण का उपयोग करें। पढ़ने-लिखने-योग्य Boolean। |
| [IsAutomaticUnderflowBin](../../aspose.slides.charts/iaxis/isautomaticunderflowbin) { get; set; } | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false: UnderflowBin गुण का उपयोग करें। |
| [IsLogarithmic](../../aspose.slides.charts/iaxis/islogarithmic) { get; set; } | निर्दिष्ट करता है कि मान अक्ष का स्केल प्रकार लॉगरिदमिक है या नहीं। पढ़ने-लिखने-योग्य Boolean। |
| [IsNumberFormatLinkedToSource](../../aspose.slides.charts/iaxis/isnumberformatlinkedtosource) { get; set; } | निर्दिष्ट करता है कि फ़ॉर्मेट लिंक्ड सोर्स डेटा है या नहीं। पढ़ने-लिखने-योग्य Boolean। |
| [IsOverflowBin](../../aspose.slides.charts/iaxis/isoverflowbin) { get; set; } | निर्दिष्ट करता है कि ओवरफ़्लो बिन लागू है या नहीं। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| [IsPlotOrderReversed](../../aspose.slides.charts/iaxis/isplotorderreversed) { get; set; } | निर्दिष्ट करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ने-लिखने-योग्य Boolean। |
| [IsUnderflowBin](../../aspose.slides.charts/iaxis/isunderflowbin) { get; set; } | निर्दिष्ट करता है कि अंडरफ़्लो बिन लागू है या नहीं। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| [IsVisible](../../aspose.slides.charts/iaxis/isvisible) { get; set; } | निर्दिष्ट करता है कि अक्ष दृश्यमान है या नहीं। पढ़ने-लिखने-योग्य Boolean। |
| [LabelOffset](../../aspose.slides.charts/iaxis/labeloffset) { get; set; } | अक्ष से लेबल की दूरी निर्दिष्ट करता है। श्रेणी या डेट अक्ष पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ने-लिखने-योग्य UInt16। |
| [LogBase](../../aspose.slides.charts/iaxis/logbase) { get; set; } | लॉगरिदमिक आधार दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ने-लिखने-योग्य Double। |
| [MajorGridLinesFormat](../../aspose.slides.charts/iaxis/majorgridlinesformat) { get; } | चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने-योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MajorTickMark](../../aspose.slides.charts/iaxis/majortickmark) { get; set; } | निर्दिष्ट अक्ष के प्रमुख टिक मार्क प्रकार को दर्शाता है। पढ़ने-लिखने-योग्य [`TickMarkType`](../tickmarktype)। |
| [MajorUnit](../../aspose.slides.charts/iaxis/majorunit) { get; set; } | डेट या मान अक्ष के प्रमुख इकाइयों को दर्शाता है। पढ़ने-लिखने-योग्य Double। |
| [MajorUnitScale](../../aspose.slides.charts/iaxis/majorunitscale) { get; set; } | डेट अक्ष के प्रमुख इकाई स्केल को दर्शाता है। पढ़ने-लिखने-योग्य [`TimeUnitType`](../timeunittype)। |
| [MaxValue](../../aspose.slides.charts/iaxis/maxvalue) { get; set; } | मान अक्ष पर अधिकतम मान दर्शाता है। पढ़ने-लिखने-योग्य Double। |
| [MinorGridLinesFormat](../../aspose.slides.charts/iaxis/minorgridlinesformat) { get; } | चार्ट अक्ष पर गौण ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने-योग्य [`IChartLinesFormat`](../ichartlinesformat)। |
| [MinorTickMark](../../aspose.slides.charts/iaxis/minortickmark) { get; set; } | निर्दिष्ट अक्ष के गौण टिक मार्क प्रकार को दर्शाता है। पढ़ने-लिखने-योग्य [`TickMarkType`](../tickmarktype)। |
| [MinorUnit](../../aspose.slides.charts/iaxis/minorunit) { get; set; } | डेट या मान अक्ष के गौण इकाइयों को दर्शाता है। पढ़ने-लिखने-योग्य Double। |
| [MinorUnitScale](../../aspose.slides.charts/iaxis/minorunitscale) { get; set; } | डेट अक्ष के प्रमुख इकाई स्केल को दर्शाता है। पढ़ने-लिखने-योग्य [`TimeUnitType`](../timeunittype)। |
| [MinValue](../../aspose.slides.charts/iaxis/minvalue) { get; set; } | मान अक्ष पर न्यूनतम मान दर्शाता है। पढ़ने-लिखने-योग्य Double। |
| [NumberFormat](../../aspose.slides.charts/iaxis/numberformat) { get; set; } | अक्ष लेबल्स के लिए फ़ॉर्मेट स्ट्रिंग दर्शाता है। पढ़ने-लिखने-योग्य String। |
| [NumberOfBins](../../aspose.slides.charts/iaxis/numberofbins) { get; set; } | जब AggregationType गुण का मान AxisAggregationType.ByNumberOfBins पर सेट हो, तब बिनों की संख्या निर्दिष्ट करता है। श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [OverflowBin](../../aspose.slides.charts/iaxis/overflowbin) { get; set; } | ओवरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin गुण false पर सेट हो और IsOverflowBin गुण true हो, तब लागू होता है। |
| [Position](../../aspose.slides.charts/iaxis/position) { get; set; } | अक्ष की स्थिति दर्शाता है। पढ़ने-लिखने-योग्य [`AxisPositionType`](../axispositiontype)। |
| [ShowMajorGridLines](../../aspose.slides.charts/iaxis/showmajorgridlines) { get; } | निर्धारित करता है कि प्रमुख ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने-योग्य Boolean। |
| [ShowMinorGridLines](../../aspose.slides.charts/iaxis/showminorgridlines) { get; } | निर्धारित करता है कि गौण ग्रिडलाइन दिखाए गए हैं या नहीं। केवल-पढ़ने-योग्य Boolean। |
| [TickLabelPosition](../../aspose.slides.charts/iaxis/ticklabelposition) { get; set; } | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ने-लिखने-योग्य [`TickLabelPositionType`](../ticklabelpositiontype)। |
| [TickLabelRotationAngle](../../aspose.slides.charts/iaxis/ticklabelrotationangle) { get; set; } | टिक लेबल की घूर्णन कोण दर्शाता है। पढ़ने-लिखने-योग्य Single। |
| [TickLabelSpacing](../../aspose.slides.charts/iaxis/ticklabelspacing) { get; set; } | दर्शाता है कि दिखाए गए लेबल के बीच कितने टिक लेबल को छोड़ना है। पढ़ने-लिखने-योग्य UInt32। |
| [TickMarksSpacing](../../aspose.slides.charts/iaxis/tickmarksspacing) { get; set; } | अगले टिक मार्क को खींचने से पहले कितने टिक मार्क को छोड़ना है, इसे निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ने-लिखने-योग्य UInt16। |
| [Title](../../aspose.slides.charts/iaxis/title) { get; } | अक्ष का शीर्षक प्राप्त करता है। केवल-पढ़ने-योग्य [`IChartTitle`](../icharttitle)। |
| [UnderflowBin](../../aspose.slides.charts/iaxis/underflowbin) { get; set; } | अंडरफ़्लो बिन का कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin गुण false पर सेट हो और IsUnderflowBin गुण true हो, तब लागू होता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| [SetCategoryAxisTypeAutomatically](../../aspose.slides.charts/iaxis/setcategoryaxistypeautomatically)() | IAxis.CategoryAxisType प्रॉपर्टी को एक मान से सेट करता है जो अक्ष डेटा के आधार पर स्वचालित रूप से निर्धारित होता है। |

### देखें

* इंटरफ़ेस [IFormattedTextContainer](../iformattedtextcontainer)
* नेमस्पेस [Aspose.Slides.Charts](../../aspose.slides.charts)
* असेंबली [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
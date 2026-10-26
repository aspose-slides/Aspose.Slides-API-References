---
title: Axis
second_title: Aspose.Slides for C++ API संदर्भ
description: चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को संलग्न करता है।
type: docs
weight: 14
url: /hi/aspose.slides.charts/axis/
---
## Axis क्लास

चार्ट के अक्ष का प्रतिनिधित्व करने वाले ऑब्जेक्ट को संलग्न करता है।

```cpp
class Axis : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::AxesManager>>,
             public Aspose::Slides::Charts::IAxis
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **double** [get_ActualMajorUnit](./get_actualmajorunit/)() override | अक्ष की वास्तविक प्रमुख इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() override | अक्ष की वास्तविक प्रमुख इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| **double** [get_ActualMaxValue](./get_actualmaxvalue/)() override | अक्ष पर वास्तविक अधिकतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| **double** [get_ActualMinorUnit](./get_actualminorunit/)() override | अक्ष की वास्तविक लघु इकाई को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() override | अक्ष की वास्तविक लघु इकाई स्केल को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| **double** [get_ActualMinValue](./get_actualminvalue/)() override | अक्ष पर वास्तविक न्यूनतम मान को निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) मेथड को कॉल करें। |
| [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() override | श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। केवल श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() override | दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच काटता है या नहीं। यह गुण केवल श्रेणी अक्षों पर लागू होता है, और 3-डी चार्ट पर लागू नहीं होता। पढ़ें **bool**। |
| [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() override | तिथि अक्ष पर दर्शाई गई सबसे छोटी समय इकाई को निर्दिष्ट करता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| **double** [get_BinWidth](./get_binwidth/)() override | AggregationType गुण मान [AxisAggregationType::ByBinWidth](../axisaggregationtype/) पर सेट होने पर बिन चौड़ाई निर्दिष्ट करता है। केवल श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() override | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। पढ़ें [Charts::CategoryAxisType](../categoryaxistype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| **float** [get_CrossAt](./get_crossat/)() override | उस बिंदु को दर्शाता है जहाँ लम्बवत अक्ष इसे काटता है। पढ़ें **float**। |
| [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() override | निर्दिष्ट अक्ष पर जहाँ अन्य अक्ष काटता है, उस CrossType को दर्शाता है। पढ़ें [CrossesType](../crossestype/)। |
| [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() override | मान अक्ष के डिस्प्ले यूनिट्स के स्केल मान को निर्दिष्ट करता है। पढ़ें [DisplayUnitType](../displayunittype/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() override | अक्ष का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IAxisFormat](../iaxisformat/)। |
| **bool** [get_HasTitle](./get_hastitle/)() override | निर्धारित करता है कि अक्ष के पास दृश्यमान शीर्षक है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() override | दर्शाता है कि अक्ष की प्रमुख इकाई स्वचालित रूप से असाइन की गई है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() override | दर्शाता है कि अधिकतम मान स्वचालित रूप से असाइन किया गया है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() override | दर्शाता है कि अक्ष की लघु इकाई स्वचालित रूप से असाइन की गई है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() override | दर्शाता है कि न्यूनतम मान स्वचालित रूप से असाइन किया गया है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() override | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है तो OverflowBin गुण का उपयोग करें। |
| **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() override | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false है तो TickLabelSpacing गुण का उपयोग करें। पढ़ें **bool**। |
| **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() override | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false है तो TickMarksSpacing गुण का उपयोग करें। पढ़ें **bool**। |
| **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() override | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है तो UnderflowBin गुण का उपयोग करें। |
| **bool** [get_IsLogarithmic](./get_islogarithmic/)() override | दर्शाता है कि मान अक्ष का स्केल प्रकार लोगारिदमिक है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | दर्शाता है कि फ़ॉर्मेट लिंक्ड स्रोत डेटा है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsOverflowBin](./get_isoverflowbin/)() override | यदि ओवरफ़्लो बिन लागू है तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() override | दर्शाता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ें **bool**। |
| **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() override | यदि अंडरफ़्लो बिन लागू है तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| **bool** [get_IsVisible](./get_isvisible/)() override | दर्शाता है कि अक्ष दृश्यमान है या नहीं। पढ़ें **bool**। |
| **uint16_t** [get_LabelOffset](./get_labeloffset/)() override | अक्ष से लेबल की दूरी निर्दिष्ट करता है। श्रेणी या तिथि अक्ष पर लागू। मान 0 % से 1000 % के बीच होना चाहिए। पढ़ें **uint16_t**। |
| **double** [get_LogBase](./get_logbase/)() override | लॉगरिदमिक आधार को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें **double**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() override | चार्ट अक्ष पर प्रमुख ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../ichartlinesformat/)। |
| [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() override | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार दर्शाता है। पढ़ें [TickMarkType](../tickmarktype/)। |
| **double** [get_MajorUnit](./get_majorunit/)() override | तिथि या मान अक्ष के लिए प्रमुख इकाइयाँ दर्शाता है। पढ़ें **double**। |
| [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() override | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| **double** [get_MaxValue](./get_maxvalue/)() override | मान अक्ष पर अधिकतम मान दर्शाता है। पढ़ें **double**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() override | चार्ट अक्ष पर लघु ग्रिडलाइन फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../ichartlinesformat/)। |
| [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() override | निर्दिष्ट अक्ष के लिए लघु टिक मार्क प्रकार दर्शाता है। पढ़ें [TickMarkType](../tickmarktype/)। |
| **double** [get_MinorUnit](./get_minorunit/)() override | तिथि या मान अक्ष के लिए लघु इकाइयाँ दर्शाता है। पढ़ें **double**। |
| [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() override | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| **double** [get_MinValue](./get_minvalue/)() override | मान अक्ष पर न्यूनतम मान दर्शाता है। पढ़ें **double**। |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | [Axis](./) लेबल के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। पढ़ें [System::String](../../system/string/)। |
| **uint32_t** [get_NumberOfBins](./get_numberofbins/)() override | AggregationType गुण मान [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) पर सेट होने पर बिनों की संख्या निर्दिष्ट करता है। केवल श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| **double** [get_OverflowBin](./get_overflowbin/)() override | ओवरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin false और IsOverflowBin true हो तो लागू होता है। |
| [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() override | अक्ष की स्थिति दर्शाता है। पढ़ें [AxisPositionType](../axispositiontype/)। |
| **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() override | प्रमुख ग्रिडलाइन छिपाने के लिए [get_MajorGridLinesFormat()](./get_majorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() को [FillType::NoFill](../../aspose.slides/filltype/) पर सेट करें। केवल-पढ़ने योग्य **bool**। |
| **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() override | लघु ग्रिडलाइन छिपाने के लिए [get_MinorGridLinesFormat()](./get_minorgridlinesformat/)->get_Line()->get_FillFormat()->get(set)_FillType() को [FillType::NoFill](../../aspose.slides/filltype/) पर सेट करें। केवल-पढ़ने योग्य **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | टेक्स्ट का फ़ॉर्मेट दर्शाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() override | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ें [TickLabelPositionType](../ticklabelpositiontype/)। |
| **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() override | टिक लेबल के घुमाव कोण को दर्शाता है। पढ़ें **float**। |
| **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() override | ड्रॉ किए गए लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ें **uint32_t**। |
| **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() override | अगले टिक मार्क से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। पढ़ें **uint16_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() override | अक्ष का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [IChartTitle](../icharttitle/)। |
| **double** [get_UnderflowBin](./get_underflowbin/)() override | अंडरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin false और IsUnderflowBin true हो तो लागू होता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंनरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स का क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्ट करने की अनुमति देता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्ट करने की अनुमति देता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr से रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) override | श्रेणी अक्ष (बिनिंग) का एग्रीगेशन प्रकार दर्शाता है। केवल श्रेणी पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) override | दर्शाता है कि मान अक्ष श्रेणी अक्ष को श्रेणियों के बीच काटता है या नहीं। यह गुण केवल श्रेणी अक्षों पर लागू होता है, और 3-डी चार्ट पर लागू नहीं होता। लिखें **bool**। |
| void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) override | तिथि अक्ष पर दर्शाई गई सबसे छोटी समय इकाई को निर्दिष्ट करता है। लिखें [TimeUnitType](../timeunittype/)। |
| void [set_BinWidth](./set_binwidth/)(**double**) override | AggregationType गुण मान [AxisAggregationType::ByBinWidth](../axisaggregationtype/) पर सेट होने पर बिन चौड़ाई निर्दिष्ट करता है। केवल श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) override | श्रेणी अक्ष का प्रकार निर्दिष्ट करता है। लिखें [Charts::CategoryAxisType](../categoryaxistype/)। |
| void [set_CrossAt](./set_crossat/)(**float**) override | अक्ष पर वह बिंदु दर्शाता है जहाँ लम्बवत अक्ष इसे काटता है। लिखें **float**। |
| void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) override | निर्दिष्ट अक्ष पर जहाँ अन्य अक्ष काटता है, उस CrossType को दर्शाता है। लिखें [CrossesType](../crossestype/)। |
| void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) override | मान अक्ष के डिस्प्ले यूनिट्स के स्केल मान को निर्दिष्ट करता है। लिखें [DisplayUnitType](../displayunittype/)। |
| void [set_HasTitle](./set_hastitle/)(**bool**) override | निर्धारित करता है कि अक्ष के पास दृश्यमान शीर्षक है या नहीं। लिखें **bool**। |
| void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) override | दर्शाता है कि अक्ष की प्रमुख इकाई स्वचालित रूप से असाइन की गई है या नहीं। लिखें **bool**। |
| void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) override | दर्शाता है कि अधिकतम मान स्वचालित रूप से असाइन किया गया है या नहीं। लिखें **bool**। |
| void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) override | दर्शाता है कि अक्ष की लघु इकाई स्वचालित रूप से असाइन की गई है या नहीं। लिखें **bool**। |
| void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) override | दर्शाता है कि न्यूनतम मान स्वचालित रूप से असाइन किया गया है या नहीं। लिखें **bool**। |
| void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) override | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है तो OverflowBin गुण का उपयोग करें। |
| void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) override | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false है तो TickLabelSpacing गुण का उपयोग करें। लिखें **bool**। |
| void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) override | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false है तो TickMarksSpacing गुण का उपयोग करें। लिखें **bool**। |
| void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) override | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false है तो UnderflowBin गुण का उपयोग करें। |
| void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) override | दर्शाता है कि मान अक्ष का स्केल प्रकार लोगारिदमिक है या नहीं। लिखें **bool**। |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | दर्शाता है कि फ़ॉर्मेट लिंक्ड स्रोत डेटा है या नहीं। लिखें **bool**। |
| void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) override | यदि ओवरफ़्लो बिन लागू है तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) override | दर्शाता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। लिखें **bool**। |
| void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) override | यदि अंडरफ़्लो बिन लागू है तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| void [set_IsVisible](./set_isvisible/)(**bool**) override | दर्शाता है कि अक्ष दृश्यमान है या नहीं। लिखें **bool**। |
| void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) override | अक्ष से लेबल की दूरी निर्दिष्ट करता है। श्रेणी या तिथि अक्ष पर लागू। मान 0 % से 1000 % के बीच होना चाहिए। लिखें **uint16_t**। |
| void [set_LogBase](./set_logbase/)(**double**) override | लॉगरिदमिक आधार को दर्शाता है। डिफ़ॉल्ट मान 10 है। लिखें **double**। |
| void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) override | निर्दिष्ट अक्ष के लिए प्रमुख टिक मार्क प्रकार दर्शाता है। लिखें [TickMarkType](../tickmarktype/)। |
| void [set_MajorUnit](./set_majorunit/)(**double**) override | तिथि या मान अक्ष के लिए प्रमुख इकाइयाँ दर्शाता है। लिखें **double**। |
| void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) override | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। लिखें [TimeUnitType](../timeunittype/)। |
| void [set_MaxValue](./set_maxvalue/)(**double**) override | मान अक्ष पर अधिकतम मान दर्शाता है। लिखें **double**। |
| void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) override | निर्दिष्ट अक्ष के लिए लघु टिक मार्क प्रकार दर्शाता है। लिखें [TickMarkType](../tickmarktype/)। |
| void [set_MinorUnit](./set_minorunit/)(**double**) override | तिथि या मान अक्ष के लिए लघु इकाइयाँ दर्शाता है। लिखें **double**। |
| void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) override | तिथि अक्ष के लिए प्रमुख इकाई स्केल दर्शाता है। लिखें [TimeUnitType](../timeunittype/)। |
| void [set_MinValue](./set_minvalue/)(**double**) override | मान अक्ष पर न्यूनतम मान दर्शाता है। लिखें **double**। |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | [Axis](./) लेबल के फ़ॉर्मेट स्ट्रिंग को दर्शाता है। लिखें [System::String](../../system/string/)। |
| void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) override | AggregationType गुण मान [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) पर सेट होने पर बिनों की संख्या निर्दिष्ट करता है। केवल श्रेणी अक्षों पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| void [set_OverflowBin](./set_overflowbin/)(**double**) override | ओवरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin false और IsOverflowBin true हो तो लागू होता है। |
| void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) override | अक्ष की स्थिति दर्शाता है। लिखें [AxisPositionType](../axispositiontype/)। |
| void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) override | निर्दिष्ट अक्ष पर टिक-मार्क लेबल की स्थिति दर्शाता है। लिखें [TickLabelPositionType](../ticklabelpositiontype/)। |
| void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) override | टिक लेबल के घुमाव कोण को दर्शाता है। लिखें **float**। |
| void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) override | ड्रॉ किए गए लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। लिखें **uint32_t**। |
| void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) override | अगले टिक मार्क से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला अक्ष पर लागू। लिखें **uint16_t**। |
| void [set_UnderflowBin](./set_underflowbin/)(**double**) override | अंडरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin false और IsUnderflowBin true हो तो लागू होता है। |
| void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() override | IAxis::get(set)_CategoryAxisType गुण को स्वचालित रूप से निर्धारित मान के साथ सेट करता है। |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | टेम्प्लेट के n-वें तर्क को weak पॉइंटर (shared नहीं) बनाता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंनरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [DomObject](../../aspose.slides/domobject/)
* क्लास [IAxis](../iaxis/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
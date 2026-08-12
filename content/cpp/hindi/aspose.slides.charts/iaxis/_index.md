---
title: IAxis
second_title: Aspose.Slides for C++ API संदर्भ
description: एक चार्ट की एक्सिस का प्रतिनिधित्व करने वाली वस्तु को संलग्न करता है।
type: docs
weight: 534
url: /hi/aspose.slides.charts/iaxis/
---
## IAxis क्लास

Encapsulates the object that represents a chart's axis.

```cpp
class IAxis : public Aspose::Slides::Charts::IFormattedTextContainer
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धान्त का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है۔ |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को समान मानते हुए C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को समान मानते हुए C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual **double** [get_ActualMajorUnit](./get_actualmajorunit/)() | एक्सिस की वास्तविक प्रमुख इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMajorUnitScale](./get_actualmajorunitscale/)() | एक्सिस की वास्तविक प्रमुख इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual **double** [get_ActualMaxValue](./get_actualmaxvalue/)() | एक्सिस पर वास्तविक अधिकतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual **double** [get_ActualMinorUnit](./get_actualminorunit/)() | एक्सिस की वास्तविक लघु इकाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual [TimeUnitType](../timeunittype/) [get_ActualMinorUnitScale](./get_actualminorunitscale/)() | एक्सिस की वास्तविक लघु इकाई स्केल निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual **double** [get_ActualMinValue](./get_actualminvalue/)() | एक्सिस पर वास्तविक न्यूनतम मान निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले [IChart::ValidateChartLayout](../ichart/validatechartlayout/) विधि को कॉल करें। |
| virtual [AxisAggregationType](../axisaggregationtype/) [get_AggregationType](./get_aggregationtype/)() | श्रेणी एक्सिस (बिनिंग) के एग्रीगेशन प्रकार का प्रतिनिधित्व करता है। श्रेणी पर लागू। केवल हिस्टोग्राम या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual **bool** [get_AxisBetweenCategories](./get_axisbetweencategories/)() | यदि मान एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच पार करता है तो दर्शाता है। यह गुण केवल श्रेणी एक्सिस पर लागू होता है, और 3-D चार्ट पर लागू नहीं होता। पढ़ें **bool**। |
| virtual [TimeUnitType](../timeunittype/) [get_BaseUnitScale](./get_baseunitscale/)() | तारीख एक्सिस पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| virtual **double** [get_BinWidth](./get_binwidth/)() | जब AggregationType गुण का मान [AxisAggregationType::ByBinWidth](../axisaggregationtype/) हो तो बिन चौड़ाई निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual [Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/) [get_CategoryAxisType](./get_categoryaxistype/)() | श्रेणी एक्सिस के प्रकार को निर्दिष्ट करता है। पढ़ें [CategoryAxisType](../categoryaxistype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual **float** [get_CrossAt](./get_crossat/)() | एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्बवत एक्सिस इसे पार करता है। पढ़ें **float**। |
| virtual [CrossesType](../crossestype/) [get_CrossType](./get_crosstype/)() | निर्दिष्ट एक्सिस पर जहाँ दूसरी एक्सिस पार करती है, उस स्थान का CrossType दर्शाता है। पढ़ें [CrossesType](../crossestype/)। |
| virtual [DisplayUnitType](../displayunittype/) [get_DisplayUnit](./get_displayunit/)() | मान एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। पढ़ें [DisplayUnitType](../displayunittype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAxisFormat](../iaxisformat/)\> [get_Format](./get_format/)() | एक्सिस का प्रारूप दर्शाता है। केवल-पढ़ने योग्य [IAxisFormat](../iaxisformat/)। |
| virtual **bool** [get_HasTitle](./get_hastitle/)() | निर्धारित करता है कि क्या एक्सिस का एक दृश्यमान शीर्षक है। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticMajorUnit](./get_isautomaticmajorunit/)() | यह बताता है कि क्या एक्सिस की प्रमुख इकाई स्वचालित रूप से निर्धारित है। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticMaxValue](./get_isautomaticmaxvalue/)() | यह दर्शाता है कि क्या अधिकतम मान स्वचालित रूप से निर्धारित है। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticMinorUnit](./get_isautomaticminorunit/)() | यह दर्शाता है कि क्या एक्सिस की लघु इकाई स्वचालित रूप से निर्धारित है। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticMinValue](./get_isautomaticminvalue/)() | यह दर्शाता है कि क्या न्यूनतम मान स्वचालित रूप से निर्धारित है। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticOverflowBin](./get_isautomaticoverflowbin/)() | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो OverflowBin गुण का उपयोग करें। |
| virtual **bool** [get_IsAutomaticTickLabelSpacing](./get_isautomaticticklabelspacing/)() | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false हो तो TickLabelSpacing गुण का उपयोग करें। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticTickMarksSpacing](./get_isautomatictickmarksspacing/)() | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false हो तो TickMarksSpacing गुण का उपयोग करें। पढ़ें **bool**। |
| virtual **bool** [get_IsAutomaticUnderflowBin](./get_isautomaticunderflowbin/)() | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो UnderflowBin गुण का उपयोग करें। |
| virtual **bool** [get_IsLogarithmic](./get_islogarithmic/)() | यदि मान एक्सिस का स्केल प्रकार लॉगरिदमिक है या नहीं दर्शाता है। पढ़ें **bool**। |
| virtual **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() | यह इंगित करता है कि प्रारूप लिंक्ड स्रोत डेटा है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_IsOverflowBin](./get_isoverflowbin/)() | यदि ओवरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| virtual **bool** [get_IsPlotOrderReversed](./get_isplotorderreversed/)() | निर्दिष्ट करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। पढ़ें **bool**। |
| virtual **bool** [get_IsUnderflowBin](./get_isunderflowbin/)() | यदि अंडरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | निर्दिष्ट करता है कि क्या एक्सिस दृश्यमान है। पढ़ें **bool**। |
| virtual **uint16_t** [get_LabelOffset](./get_labeloffset/)() | लेबलों की एक्सिस से दूरी निर्दिष्ट करता है। श्रेणी या तारीख एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। पढ़ें **uint16_t**। |
| virtual **double** [get_LogBase](./get_logbase/)() | लॉगरिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। पढ़ें **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MajorGridLinesFormat](./get_majorgridlinesformat/)() | चार्ट एक्सिस पर प्रमुख ग्रिडलाइन का प्रारूप दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../ichartlinesformat/)। |
| virtual [TickMarkType](../tickmarktype/) [get_MajorTickMark](./get_majortickmark/)() | निर्दिष्ट एक्सिस के प्रमुख टिक मार्क के प्रकार को दर्शाता है। पढ़ें [TickMarkType](../tickmarktype/)। |
| virtual **double** [get_MajorUnit](./get_majorunit/)() | तारीख या मान एक्सिस के प्रमुख इकाइयों को दर्शाता है। पढ़ें **double**। |
| virtual [TimeUnitType](../timeunittype/) [get_MajorUnitScale](./get_majorunitscale/)() | तारीख एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| virtual **double** [get_MaxValue](./get_maxvalue/)() | मान एक्सिस पर अधिकतम मान दर्शाता है। पढ़ें **double**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_MinorGridLinesFormat](./get_minorgridlinesformat/)() | चार्ट एक्सिस पर लघु ग्रिडलाइन का प्रारूप दर्शाता है। केवल-पढ़ने योग्य [IChartLinesFormat](../ichartlinesformat/)। |
| virtual [TickMarkType](../tickmarktype/) [get_MinorTickMark](./get_minortickmark/)() | निर्दिष्ट एक्सिस के लघु टिक मार्क के प्रकार को दर्शाता है। पढ़ें [TickMarkType](../tickmarktype/)। |
| virtual **double** [get_MinorUnit](./get_minorunit/)() | तारीख या मान एक्सिस के लघु इकाइयों को दर्शाता है। पढ़ें **double**। |
| virtual [TimeUnitType](../timeunittype/) [get_MinorUnitScale](./get_minorunitscale/)() | तारीख एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। पढ़ें [TimeUnitType](../timeunittype/)। |
| virtual **double** [get_MinValue](./get_minvalue/)() | मान एक्सिस पर न्यूनतम मान दर्शाता है। पढ़ें **double**। |
| virtual [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() | [Axis](../axis/) लेबल्स के लिए प्रारूप स्ट्रिंग दर्शाता है। पढ़ें [System::String](../../system/string/)। |
| virtual **uint32_t** [get_NumberOfBins](./get_numberofbins/)() | जब AggregationType गुण का मान [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) हो तो बिनों की संख्या निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual **double** [get_OverflowBin](./get_overflowbin/)() | ओवरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin गुण false और IsOverflowBin गुण true हो तो लागू होता है। |
| virtual [AxisPositionType](../axispositiontype/) [get_Position](./get_position/)() | एक्सिस की स्थिति दर्शाता है। पढ़ें [AxisPositionType](../axispositiontype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual **bool** [get_ShowMajorGridLines](./get_showmajorgridlines/)() | यदि प्रमुख ग्रिडलाइन दिखती है तो दर्शाता है। केवल-पढ़ने योग्य **bool**। |
| virtual **bool** [get_ShowMinorGridLines](./get_showminorgridlines/)() | यदि लघु ग्रिडलाइन दिखती है तो दर्शाता है। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| virtual [TickLabelPositionType](../ticklabelpositiontype/) [get_TickLabelPosition](./get_ticklabelposition/)() | निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति दर्शाता है। पढ़ें [TickLabelPositionType](../ticklabelpositiontype/)। |
| virtual **float** [get_TickLabelRotationAngle](./get_ticklabelrotationangle/)() | टिक लेबल की घूर्णन कोण दर्शाता है। पढ़ें **float**। |
| virtual **uint32_t** [get_TickLabelSpacing](./get_ticklabelspacing/)() | ड्रॉ किए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। पढ़ें **uint32_t**। |
| virtual **uint32_t** [get_TickMarksSpacing](./get_tickmarksspacing/)() | अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। पढ़ें **uint16_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTitle](../icharttitle/)\> [get_Title](./get_title/)() | एक्सिस का शीर्षक प्राप्त करता है। केवल-पढ़ने योग्य [IChartTitle](../icharttitle/)। |
| virtual **double** [get_UnderflowBin](./get_underflowbin/)() | अंडरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin गुण false और IsUnderflowBin गुण true हो तो लागू होता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू प्रकार के ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_AggregationType](./set_aggregationtype/)([AxisAggregationType](../axisaggregationtype/)) | श्रेणी एक्सिस (बिनिंग) के एग्रीगेशन प्रकार का प्रतिनिधित्व करता है। श्रेणी पर लागू। केवल हिस्टोग्राम या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual void [set_AxisBetweenCategories](./set_axisbetweencategories/)(**bool**) | यदि मान एक्सिस श्रेणी एक्सिस को श्रेणियों के बीच पार करता है तो दर्शाता है। यह गुण केवल श्रेणी एक्सिस पर लागू होता है, और 3-D चार्ट पर लागू नहीं होता। लिखें **bool**। |
| virtual void [set_BaseUnitScale](./set_baseunitscale/)([TimeUnitType](../timeunittype/)) | तारीख एक्सिस पर प्रतिनिधित्व किए जाने वाले सबसे छोटे समय इकाई को निर्दिष्ट करता है। लिखें [TimeUnitType](../timeunittype/)। |
| virtual void [set_BinWidth](./set_binwidth/)(**double**) | जब AggregationType गुण का मान [AxisAggregationType::ByBinWidth](../axisaggregationtype/) हो तो बिन चौड़ाई निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual void [set_CategoryAxisType](./set_categoryaxistype/)([Aspose::Slides::Charts::CategoryAxisType](../categoryaxistype/)) | श्रेणी एक्सिस के प्रकार को निर्दिष्ट करता है। लिखें [CategoryAxisType](../categoryaxistype/)। |
| virtual void [set_CrossAt](./set_crossat/)(**float**) | एक्सिस पर वह बिंदु दर्शाता है जहाँ लम्बवत एक्सिस इसे पार करता है। लिखें **float**। |
| virtual void [set_CrossType](./set_crosstype/)([CrossesType](../crossestype/)) | निर्दिष्ट एक्सिस पर जहाँ अन्य एक्सिस पार करती है, उस स्थान का CrossType दर्शाता है। लिखें [CrossesType](../crossestype/)। |
| virtual void [set_DisplayUnit](./set_displayunit/)([DisplayUnitType](../displayunittype/)) | मान एक्सिस के डिस्प्ले यूनिट्स के स्केलिंग मान को निर्दिष्ट करता है। लिखें [DisplayUnitType](../displayunittype/)। |
| virtual void [set_HasTitle](./set_hastitle/)(**bool**) | निर्धारित करता है कि क्या एक्सिस का एक दृश्यमान शीर्षक है। लिखें **bool**। |
| virtual void [set_IsAutomaticMajorUnit](./set_isautomaticmajorunit/)(**bool**) | यह बताता है कि क्या एक्सिस की प्रमुख इकाई स्वचालित रूप से निर्धारित है। लिखें **bool**। |
| virtual void [set_IsAutomaticMaxValue](./set_isautomaticmaxvalue/)(**bool**) | यह दर्शाता है कि क्या अधिकतम मान स्वचालित रूप से निर्धारित है। लिखें **bool**। |
| virtual void [set_IsAutomaticMinorUnit](./set_isautomaticminorunit/)(**bool**) | यह दर्शाता है कि क्या एक्सिस की लघु इकाई स्वचालित रूप से निर्धारित है। लिखें **bool**। |
| virtual void [set_IsAutomaticMinValue](./set_isautomaticminvalue/)(**bool**) | यह दर्शाता है कि क्या न्यूनतम मान स्वचालित रूप से निर्धारित है। लिखें **bool**। |
| virtual void [set_IsAutomaticOverflowBin](./set_isautomaticoverflowbin/)(**bool**) | स्वचालित ओवरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो OverflowBin गुण का उपयोग करें। |
| virtual void [set_IsAutomaticTickLabelSpacing](./set_isautomaticticklabelspacing/)(**bool**) | स्वचालित टिक लेबल स्पेसिंग मान निर्दिष्ट करता है। यदि false हो तो TickLabelSpacing गुण का उपयोग करें। लिखें **bool**। |
| virtual void [set_IsAutomaticTickMarksSpacing](./set_isautomatictickmarksspacing/)(**bool**) | स्वचालित टिक मार्क्स स्पेसिंग मान निर्दिष्ट करता है। यदि false हो तो TickMarksSpacing गुण का उपयोग करें। लिखें **bool**। |
| virtual void [set_IsAutomaticUnderflowBin](./set_isautomaticunderflowbin/)(**bool**) | स्वचालित अंडरफ़्लो बिन मान निर्दिष्ट करता है। यदि false हो तो UnderflowBin गुण का उपयोग करें। |
| virtual void [set_IsLogarithmic](./set_islogarithmic/)(**bool**) | यदि मान एक्सिस का स्केल प्रकार लॉगरिदमिक है या नहीं दर्शाता है। लिखें **bool**। |
| virtual void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) | यह इंगित करता है कि प्रारूप लिंक्ड स्रोत डेटा है या नहीं। लिखें **bool**। |
| virtual void [set_IsOverflowBin](./set_isoverflowbin/)(**bool**) | यदि ओवरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। ओवरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticOverflowBin और OverflowBin का उपयोग करें। |
| virtual void [set_IsPlotOrderReversed](./set_isplotorderreversed/)(**bool**) | निर्दिष्ट करता है कि MS PowerPoint डेटा बिंदुओं को अंतिम से प्रथम क्रम में प्लॉट करता है या नहीं। लिखें **bool**। |
| virtual void [set_IsUnderflowBin](./set_isunderflowbin/)(**bool**) | यदि अंडरफ़्लो बिन लागू हो तो निर्दिष्ट करता है। अंडरफ़्लो बिन मान को समायोजित करने के लिए IsAutomaticUnderflowBin और UnderflowBin का उपयोग करें। |
| virtual void [set_IsVisible](./set_isvisible/)(**bool**) | निर्दिष्ट करता है कि एक्सिस दृश्यमान है या नहीं। लिखें **bool**। |
| virtual void [set_LabelOffset](./set_labeloffset/)(**uint16_t**) | लेबलों की एक्सिस से दूरी निर्दिष्ट करता है। श्रेणी या तारीख एक्सिस पर लागू। मान 0% से 1000% के बीच होना चाहिए। लिखें **uint16_t**। |
| virtual void [set_LogBase](./set_logbase/)(**double**) | लॉगरिदमिक बेस को दर्शाता है। डिफ़ॉल्ट मान 10 है। लिखें **double**। |
| virtual void [set_MajorTickMark](./set_majortickmark/)([TickMarkType](../tickmarktype/)) | निर्दिष्ट एक्सिस के प्रमुख टिक मार्क के प्रकार को दर्शाता है। लिखें [TickMarkType](../tickmarktype/)। |
| virtual void [set_MajorUnit](./set_majorunit/)(**double**) | तारीख या मान एक्सिस के प्रमुख इकाइयों को दर्शाता है। लिखें **double**। |
| virtual void [set_MajorUnitScale](./set_majorunitscale/)([TimeUnitType](../timeunittype/)) | तारीख एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। लिखें [TimeUnitType](../timeunittype/)। |
| virtual void [set_MaxValue](./set_maxvalue/)(**double**) | मान एक्सिस पर अधिकतम मान दर्शाता है। लिखें **double**। |
| virtual void [set_MinorTickMark](./set_minortickmark/)([TickMarkType](../tickmarktype/)) | निर्दिष्ट एक्सिस के लघु टिक मार्क के प्रकार को दर्शाता है। लिखें [TickMarkType](../tickmarktype/)। |
| virtual void [set_MinorUnit](./set_minorunit/)(**double**) | तारीख या मान एक्सिस के लघु इकाइयों को दर्शाता है। लिखें **double**। |
| virtual void [set_MinorUnitScale](./set_minorunitscale/)([TimeUnitType](../timeunittype/)) | तारीख एक्सिस के प्रमुख इकाई स्केल को दर्शाता है। लिखें [TimeUnitType](../timeunittype/)। |
| virtual void [set_MinValue](./set_minvalue/)(**double**) | मान एक्सिस पर न्यूनतम मान दर्शाता है। लिखें **double**। |
| virtual void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) | [Axis](../axis/) लेबल्स के लिए प्रारूप स्ट्रिंग दर्शाता है। लिखें [System::String](../../system/string/)। |
| virtual void [set_NumberOfBins](./set_numberofbins/)(**uint32_t**) | जब AggregationType गुण का मान [AxisAggregationType::ByNumberOfBins](../axisaggregationtype/) हो तो बिनों की संख्या निर्दिष्ट करता है। श्रेणी एक्सिस पर लागू। केवल Histogram या HistogramPareto श्रृंखला के साथ उपयोग किया जाता है। |
| virtual void [set_OverflowBin](./set_overflowbin/)(**double**) | ओवरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticOverflowBin गुण false और IsOverflowBin गुण true हो तो लागू होता है। |
| virtual void [set_Position](./set_position/)([AxisPositionType](../axispositiontype/)) | एक्सिस की स्थिति दर्शाता है। लिखें [AxisPositionType](../axispositiontype/)। |
| virtual void [set_TickLabelPosition](./set_ticklabelposition/)([TickLabelPositionType](../ticklabelpositiontype/)) | निर्दिष्ट एक्सिस पर टिक-मार्क लेबल की स्थिति दर्शाता है। लिखें [TickLabelPositionType](../ticklabelpositiontype/)। |
| virtual void [set_TickLabelRotationAngle](./set_ticklabelrotationangle/)(**float**) | टिक लेबल की घूर्णन कोण दर्शाता है। लिखें **float**। |
| virtual void [set_TickLabelSpacing](./set_ticklabelspacing/)(**uint32_t**) | ड्रॉ किए जाने वाले लेबल के बीच कितने टिक लेबल छोड़ने हैं, यह निर्दिष्ट करता है। लिखें **uint32_t**। |
| virtual void [set_TickMarksSpacing](./set_tickmarksspacing/)(**uint32_t**) | अगले टिक मार्क को ड्रॉ करने से पहले कितने टिक मार्क छोड़ने हैं, यह निर्दिष्ट करता है। श्रेणी या श्रृंखला एक्सिस पर लागू। लिखें **uint16_t**। |
| virtual void [set_UnderflowBin](./set_underflowbin/)(**double**) | अंडरफ़्लो बिन कस्टम मान निर्दिष्ट करता है। जब IsAutomaticUnderflowBin गुण false और IsUnderflowBin गुण true हो तो लागू होता है। |
| virtual void [SetCategoryAxisTypeAutomatically](./setcategoryaxistypeautomatically/)() | IAxis::get(set)_CategoryAxisType गुण को एक मान से सेट करता है जो एक्सिस डेटा के आधार पर स्वचालित रूप से निर्धारित होता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट तर्क को शैयर की बजाय कमजोर पॉइंटर सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउँट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउँट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउँट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउँट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IFormattedTextContainer](../iformattedtextcontainer/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
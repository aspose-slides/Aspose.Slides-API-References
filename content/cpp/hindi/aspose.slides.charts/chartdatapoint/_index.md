---
title: ChartDataPoint
second_title: Aspose.Slides for C++ API संदर्भ
description: सीरीज़ डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
weight: 144
url: /hi/aspose.slides.charts/chartdatapoint/
---
## ChartDataPoint क्लास


Represents series data point.

```cpp
class ChartDataPoint : public Aspose::Slides::Charts::IChartDataPoint,
                       public Aspose::Slides::IDOMObject
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, NaN सहित। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, NaN सहित। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **float** [get_ActualHeight](./get_actualheight/)() override | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualWidth](./get_actualwidth/)() override | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualX](./get_actualx/)() override | चार्ट तत्व का वास्तविक x स्थान (बाएँ) चार्ट के बाएं ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| **float** [get_ActualY](./get_actualy/)() override | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएं ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले मेथड [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। **float** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() override | BubbleSize। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() override | चार्ट डेटा पॉइंट का रंग मान लौटाता है। मैप चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने के लिए [IDoubleChartValue](../idoublechartvalue/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर डेटा पॉइंट स्तर लौटाता है। Treeamp और Sunburst सीरीज़ के लिए लागू। डेटा पॉइंट स्तर का इंडेक्स शून्य-आधारित है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() override | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst सीरीज़ के लिए लागू। डेटा पॉइंट स्तर का इंडेक्स शून्य-आधारित है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() override | कस्टम वैल्यू टाइप के मामले में सीरीज़ एरर बार मानों का प्रतिनिधित्व करता है। केवल पढ़ने के लिए [IErrorBarsCustomValues](../ierrorbarscustomvalues/)। |
| **int32_t** [get_Explosion](./get_explosion/)() override | डेटा पॉइंट को पाई के केंद्र से कितनी दूरी तक ले जाना है, यह निर्दिष्ट करता है। **int32_t** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। पढ़ें [IFormat](../iformat/)। |
| **uint32_t** [get_Index](./get_index/)() override | निर्धारित करता है कि इस डेटा पॉइंट का संबंध पैरेंट के कौनसे चाइल्ड कलेक्शन से है। **uint32_t** पढ़ें। |
| **bool** [get_InvertIfNegative](./get_invertifnegative/)() override | यदि मान नकारात्मक हो तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। **bool** पढ़ें। |
| **bool** [get_IsBubble3D](./get_isbubble3d/)() override | यह निर्दिष्ट करता है कि बबल्स पर 3-D इफ़ेक्ट लागू है। **bool** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() override | लेबल। केवल पढ़ने के लिए [IDataLabel](../idatalabel/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() override | डेटा मार्कर निर्दिष्ट करता है। केवल पढ़ने के लिए [IMarker](../imarker/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() override | इस सूची में से चार्ट प्रकार के मामले में संबंधित लेजेंड एंट्री की प्रॉपर्टीज़: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/)। केवल पढ़ने के लिए [ILegendEntryProperties](../ilegendentryproperties/)। |
| **bool** [get_SetAsTotal](./get_setastotal/)() override | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() override | चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट्स के साथ उपयोग किया जाता है। केवल पढ़ने के लिए [IDoubleChartValue](../idoublechartvalue/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() override | मान। केवल पढ़ने के लिए [IDoubleChartValue](../idoublechartvalue/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() override | XValue। केवल पढ़ने के लिए [IStringOrDoubleChartValue](../istringordoublechartvalue/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() override | YValue। केवल पढ़ने के लिए [IDoubleChartValue](../idoublechartvalue/)। |
| [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() override | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट स्टाइल के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined के बराबर हो तो यह रंग डिफ़ॉल्ट रूप से उपयोग होता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकृत संस्करण। |
| void [Remove](./remove/)() override | डेटा पॉइंट को चार्ट सीरीज़ से हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Explosion](./set_explosion/)(**int32_t**) override | डेटा पॉइंट को पाई के केंद्र से कितनी दूरी तक ले जाना है, यह निर्दिष्ट करता है। **int32_t** लिखें। |
| void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) override | फ़ॉर्मेटिंग प्रॉपर्टीज़ का प्रतिनिधित्व करता है। [IFormat](../iformat/) लिखें। |
| void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) override | यदि मान नकारात्मक हो तो डेटा पॉइंट अपने रंगों को उलट देगा, यह निर्दिष्ट करता है। **bool** लिखें। |
| void [set_IsBubble3D](./set_isbubble3d/)(**bool**) override | यह निर्दिष्ट करता है कि बबल्स पर 3-D इफ़ेक्ट लागू है। **bool** लिखें। |
| void [set_SetAsTotal](./set_setastotal/)(**bool**) override | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall सीरीज़ प्रकार के लिए लागू। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्यूमेंट को weak पॉइंटर सेट करता है (shared के बजाय)। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## देखें

* क्लास [IChartDataPoint](../ichartdatapoint/)
* क्लास [IDOMObject](../../aspose.slides/idomobject/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
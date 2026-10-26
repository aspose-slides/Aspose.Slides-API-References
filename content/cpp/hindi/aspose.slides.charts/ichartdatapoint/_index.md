---
title: IChartDataPoint
second_title: Aspose.Slides for C++ API संदर्भ
description: श्रृंखला डेटा पॉइंट का प्रतिनिधित्व करता है।
type: docs
weight: 677
url: /hi/aspose.slides.charts/ichartdatapoint/
---
## IChartDataPoint क्लास


Represents series data point.

```cpp
class IChartDataPoint : public Aspose::Slides::Charts::IActualLayout
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैटिक का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | चार्ट तत्व की वास्तविक ऊँचाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले विधि [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | चार्ट तत्व की वास्तविक चौड़ाई निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले विधि [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | चार्ट तत्व का वास्तविक x स्थान (बाएँ) चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले विधि [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | चार्ट तत्व का वास्तविक शीर्ष चार्ट के बाएँ ऊपर कोने के सापेक्ष निर्दिष्ट करता है। वास्तविक मान प्राप्त करने के लिए पहले विधि [IChart::ValidateChartLayout](../ichart/validatechartlayout/) को कॉल करें। पढ़ें **float**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_BubbleSize](./get_bubblesize/)() | चार्ट डेटा पॉइंट का बबल आकार लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_ColorValue](./get_colorvalue/)() | चार्ट डेटा पॉइंट का रंग मान लौटाता है। मैप चार्ट के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevel](../ichartdatapointlevel/)\> [get_DataPointLevel](./get_datapointlevel/)(**int32_t**) | निर्दिष्ट इंडेक्स पर डेटा पॉइंट स्तर लौटाता है। Treeamp और Sunburst श्रृंखला में लागू होता है। डेटा पॉइंट स्तर की इंडेक्सिंग शून्य आधारित है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPointLevelsManager](../ichartdatapointlevelsmanager/)\> [get_DataPointLevels](./get_datapointlevels/)() | डेटा पॉइंट स्तरों का कंटेनर लौटाता है। Treeamp और Sunburst श्रृंखला में लागू होता है। डेटा पॉइंट स्तर की इंडेक्सिंग शून्य आधारित है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IErrorBarsCustomValues](../ierrorbarscustomvalues/)\> [get_ErrorBarsCustomValues](./get_errorbarscustomvalues/)() | कस्टम वैल्यू प्रकार के मामले में श्रृंखला त्रुटि बार मानों का प्रतिनिधित्व करता है। केवल पढ़ने योग्य [IErrorBarsCustomValues](../ierrorbarscustomvalues/)। |
| virtual **int32_t** [get_Explosion](./get_explosion/)() | पाई के केंद्र से डेटा पॉइंट को स्थानांतरित किए जाने की मात्रा निर्दिष्ट करता है। पढ़ें **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। पढ़ें [IFormat](../iformat/)। |
| virtual **uint32_t** [get_Index](./get_index/)() | निर्धारित करता है कि इस डेटा पॉइंट के लिए पैरेंट के बच्चों के संग्रह में कौन-सा लागू होता है। पढ़ें **uint32_t**। |
| virtual **bool** [get_InvertIfNegative](./get_invertifnegative/)() | यदि मान नकारात्मक हो तो डेटा पॉइंट के रंग उलट देगा, यह निर्दिष्ट करता है। पढ़ें **bool**। |
| virtual **bool** [get_IsBubble3D](./get_isbubble3d/)() | यह निर्दिष्ट करता है कि बुल्बों पर 3-डी प्रभाव लागू है। पढ़ें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabel](../idatalabel/)\> [get_Label](./get_label/)() | चार्ट डेटा पॉइंट का लेबल दर्शाता है। केवल पढ़ने योग्य [IDataLabel](../idatalabel/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMarker](../imarker/)\> [get_Marker](./get_marker/)() | डेटा मार्कर निर्दिष्ट करता है। केवल पढ़ने योग्य [IMarker](../imarker/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILegendEntryProperties](../ilegendentryproperties/)\> [get_RelatedLegendEntry](./get_relatedlegendentry/)() | इस सूची के चार्ट प्रकार के मामले में संबंधित लेजेंड प्रविष्टि की प्रॉपर्टीज़: [ChartType::BarOfPie](../charttype/), [ChartType::ExplodedPie](../charttype/), [ChartType::ExplodedPie3D](../charttype/), [ChartType::Pie](../charttype/), [ChartType::Pie3D](../charttype/), [ChartType::PieOfPie](../charttype/)। केवल पढ़ने योग्य [ILegendEntryProperties](../ilegendentryproperties/)। |
| virtual **bool** [get_SetAsTotal](./get_setastotal/)() | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_SizeValue](./get_sizevalue/)() | चार्ट डेटा पॉइंट का आकार मान लौटाता है। Treemap और Sunburst चार्ट के साथ उपयोग किया जाता है। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_Value](./get_value/)() | चार्ट डेटा पॉइंट का मान लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IStringOrDoubleChartValue](../istringordoublechartvalue/)\> [get_XValue](./get_xvalue/)() | चार्ट डेटा पॉइंट का x मान लौटाता है। केवल पढ़ने योग्य [IStringOrDoubleChartValue](../istringordoublechartvalue/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDoubleChartValue](../idoublechartvalue/)\> [get_YValue](./get_yvalue/)() | चार्ट डेटा पॉइंट का y मान लौटाता है। केवल पढ़ने योग्य [IDoubleChartValue](../idoublechartvalue/)। |
| virtual [System::Drawing::Color](../../system.drawing/color/) [GetAutomaticDataPointColor](./getautomaticdatapointcolor/)() | सीरीज़ इंडेक्स, डेटा पॉइंट इंडेक्स, ParentSeriesGroup.IsColorVaried प्रॉपर्टी और चार्ट शैली के आधार पर डेटा पॉइंट का स्वचालित रंग लौटाता है। यदि FillType NotDefined है तो यह रंग डिफ़ॉल्ट रूप से उपयोग होता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इकाई का प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना वैल्यू प्रकार की वस्तु को nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr स्थिति के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशेषीकरण। |
| virtual void [Remove](./remove/)() | चार्ट श्रृंखला से DataPoint को हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_Explosion](./set_explosion/)(**int32_t**) | पाई के केंद्र से डेटा पॉइंट को स्थानांतरित किए जाने की मात्रा निर्दिष्ट करता है। लिखें **int32_t**। |
| virtual void [set_Format](./set_format/)([System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\>) | फ़ॉर्मेटिंग गुणों का प्रतिनिधित्व करता है। लिखें [IFormat](../iformat/)। |
| virtual void [set_InvertIfNegative](./set_invertifnegative/)(**bool**) | यदि मान नकारात्मक हो तो डेटा पॉइंट के रंग उलट देगा, यह निर्दिष्ट करता है। लिखें **bool**। |
| virtual void [set_IsBubble3D](./set_isbubble3d/)(**bool**) | यह निर्दिष्ट करता है कि बुल्बों पर 3-डी प्रभाव लागू है। लिखें **bool**। |
| virtual void [set_SetAsTotal](./set_setastotal/)(**bool**) | डेटा पॉइंट को कुल के रूप में सेट करता है। केवल Waterfall श्रृंखला प्रकार के लिए लागू। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट तर्क को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाना चाहिए; बल्कि स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [IActualLayout](../iactuallayout/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
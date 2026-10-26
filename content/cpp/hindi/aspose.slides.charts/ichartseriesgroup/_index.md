---
title: IChartSeriesGroup
second_title: Aspose.Slides for C++ API संदर्भ
description: श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।
type: docs
weight: 846
url: /hi/aspose.slides.charts/ichartseriesgroup/
---
## IChartSeriesGroup क्लास

श्रृंखलाओं के समूह का प्रतिनिधित्व करता है।

```cpp
class IChartSeriesGroup : public Aspose::Slides::Charts::IChartComponent
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | संदर्भ प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाए, यह निर्दिष्ट करता है। देखें [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)। |
| virtual **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच हो सकता है)। देखें **int32_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) | निर्दिष्ट इंडेक्स पर समूह में चार्ट श्रृंखला लौटाता है। |
| virtual **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() | डोनट चार्ट में छेद के आकार को निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत के बीच)। देखें **uint8_t**। |
| virtual **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। देखें **uint16_t**। |
| virtual **uint16_t** [get_GapDepth](./get_gapdepth/)() | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी को मार्कर चौड़ाई के प्रतिशत में लौटाता है। देखें **uint16_t**। |
| virtual **uint16_t** [get_GapWidth](./get_gapwidth/)() | बार या कॉलम क्लस्टर्स के बीच स्थान को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। देखें **uint16_t**। |
| virtual **bool** [get_HasSeriesLines](./get_hasserieslines/)() | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। देखें **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() | HiLowLines फ़ॉर्मेट निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| virtual **bool** [get_IsColorVaried](./get_iscolorvaried/)() | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। देखें **bool**। |
| virtual **int8_t** [get_Overlap](./get_overlap/)() | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| virtual [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() | निर्दिष्ट करता है कि pie-of-pie या bar-of-pie चार्ट में दूसरी पाई या बार में कौन से डेटा पॉइंट हैं, यह निर्धारित करने का तरीका निर्दिष्ट करता है। देखें [PieSplitType](../piesplittype/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) | कस्टम स्प्लिट जानकारी जिसे pie-of-pie या bar-of-pie चार्ट में कस्टम स्प्लिट के साथ उपयोग किया जाता है। यह डेटा पॉइंट लौटाता है जिसे इंडेक्स द्वारा दूसरी पाई या बार में ड्रॉ किया जाना चाहिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() | कस्टम स्प्लिट जानकारी जिसे pie-of-pie या bar-of-pie चार्ट में कस्टम स्प्लिट के साथ उपयोग किया जाता है। इसमें डेटा पॉइंट्स होते हैं जिन्हें दूसरी पाई या बार में ड्रॉ किया जाना चाहिए। केवल-पढ़ने योग्य [IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)। |
| virtual **double** [get_PieSplitPosition](./get_piesplitposition/)() | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाता है कि कौन से डेटा पॉइंट्स pie-of-pie या bar-of-pie चार्ट में दूसरी पाई या बार में हैं। PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। देखें **double**। |
| virtual **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() | निर्दिष्ट करता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। केवल-पढ़ने योग्य **bool**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | प्रेजेंटेशन लौटाता है। केवल-पढ़ने योग्य [IPresentation](../../aspose.slides/ipresentation/)। |
| virtual **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() | pie-of-pie या bar-of-pie चार्ट में दूसरी पाई या बार का आकार निर्दिष्ट करता है, जिसे पहली पाई के आकार का प्रतिशत (5 से 200 प्रतिशत) के रूप में दर्शाया जाता है। देखें **uint16_t**। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() | चार्ट श्रृंखलाओं का केवल-पढ़ने योग्य संग्रह लौटाता है। केवल-पढ़ने योग्य [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | बेस स्लाइड लौटाता है। केवल-पढ़ने योग्य [IBaseSlide](../../aspose.slides/ibaseslide/)। |
| virtual [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() | इस श्रृंखला समूह का प्रकार लौटाता है। केवल-पढ़ने योग्य [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() | Line- या Stock-चार्ट के up/down बार तक पहुँच प्रदान करता है। केवल-पढ़ने योग्य [IUpDownBarsManager](../iupdownbarsmanager/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियालाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियालाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियालाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाए, यह निर्दिष्ट करता है। लिखें [BubbleSizeRepresentationType](../bubblesizerepresentationtype/)। |
| virtual void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत के बीच)। लिखें **int32_t**। |
| virtual void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट एरिया के आकार के 10 से 90 प्रतिशत के बीच)। लिखें **uint8_t**। |
| virtual void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) | पहले पाई या डोनट चार्ट स्लाइस का कोण सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री तक)। लिखें **uint16_t**। |
| virtual void [set_GapDepth](./set_gapdepth/)(**uint16_t**) | 3D चार्ट में डेटा श्रृंखलाओं के बीच दूरी को मार्कर चौड़ाई के प्रतिशत में सेट करता है। लिखें **uint16_t**। |
| virtual void [set_GapWidth](./set_gapwidth/)(**uint16_t**) | बार या कॉलम क्लस्टर्स के बीच स्थान को सेट करता है ... लिखें **uint16_t**। |
| virtual void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। लिखें **bool**। |
| virtual void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) | निर्दिष्ट करता है कि श्रृंखला में प्रत्येक डेटा मार्कर का रंग अलग हो। लिखें **bool**। |
| virtual void [set_Overlap](./set_overlap/)(**int8_t**) | 2-D चार्ट में बार और कॉलम कितनी ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है (-100% से 100% तक)। |
| virtual void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) | pie-of-pie या bar-of-pie चार्ट में दूसरी पाई या बार में कौन से डेटा पॉइंट हैं, निर्धारित करने का तरीका निर्दिष्ट करता है। लिखें [PieSplitType](../piesplittype/)। |
| virtual void [set_PieSplitPosition](./set_piesplitposition/)(**double**) | एक मान निर्दिष्ट करता है ... लिखें **double**। |
| virtual void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) | pie-of-pie या bar-of-pie चार्ट में दूसरी पाई या बार का आकार लिखें **uint16_t**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टिप्पणियाँ

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एन्नम के लिए सारांश और टिप्पणियों को देखें। 2) श्रृंखलाओं का समूह कुछ श्रृंखला गुणों को शामिल करता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं ("series group properties")। [ChartSeriesGroup](../chartseriesgroup/) क्लास में "series group properties" पढ़ने/लिखने योग्य है। "series group properties" में से प्रत्येक का एक केवल-पढ़ने योग्य प्रोजेक्शन [ChartSeries](../chartseries/) क्लास में हो सकता है।

## संबंधित देखें

* क्लास [IChartComponent](../ichartcomponent/)
* नामस्थान [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: ChartSeriesGroup
second_title: Aspose.Slides for C++ API संदर्भ
description: श्रृंखलाओं के समूह को दर्शाता है।
type: docs
weight: 300
url: /hi/aspose.slides.charts/chartseriesgroup/
---
## ChartSeriesGroup क्लास

श्रृंखलाओं के समूह को दर्शाता है।

```cpp
class ChartSeriesGroup : public Aspose::Slides::Charts::IChartSeriesGroup,
                         public Aspose::Slides::IDOMObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यु टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) [get_BubbleSizeRepresentation](./get_bubblesizerepresentation/)() override | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, इसे निर्दिष्ट करता है। [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) पढ़ें। |
| **int32_t** [get_BubbleSizeScale](./get_bubblesizescale/)() override | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। **int32_t** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | पैरेंट चार्ट लौटाता है। केवल पढ़ने योग्य [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [get_ChartSeries](./get_chartseries/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर समूह में चार्ट श्रृंखला लौटाता है। |
| **uint8_t** [get_DoughnutHoleSize](./get_doughnutholesize/)() override | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। **uint8_t** पढ़ें। |
| **uint16_t** [get_FirstSliceAngle](./get_firstsliceangle/)() override | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में प्राप्त करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। **uint16_t** पढ़ें। |
| **uint16_t** [get_GapDepth](./get_gapdepth/)() override | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी, मार्कर की चौड़ाई के प्रतिशत के रूप में, लौटाता है। **uint16_t** पढ़ें। |
| **uint16_t** [get_GapWidth](./get_gapwidth/)() override | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत में निर्दिष्ट करता है। **uint16_t** पढ़ें। |
| **bool** [get_HasSeriesLines](./get_hasserieslines/)() override | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। **bool** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartLinesFormat](../ichartlinesformat/)\> [get_HiLowLinesFormat](./get_hilowlinesformat/)() override | HiLowLines स्वरूप निर्दिष्ट करता है। HiLowLines को HiLowClose, OpenHiLowClose, VolumeHiLowClose और VolumeOpenHiLowClose चार्ट प्रकारों के साथ लागू किया जाता है। |
| **bool** [get_IsColorVaried](./get_iscolorvaried/)() override | श्रृंखला में प्रत्येक डेटा मार्कर का अलग रंग है, यह निर्दिष्ट करता है। **bool** पढ़ें। |
| **int8_t** [get_Overlap](./get_overlap/)() override | 2D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| [PieSplitType](../piesplittype/) [get_PieSplitBy](./get_piesplitby/)() override | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। [PieSplitType](../piesplittype/) पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\> [get_PieSplitCustomPoint](./get_piesplitcustompoint/)(**int32_t**) override | एक कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट जानकारी। इंडेक्स द्वारा दूसरे पाई या बार में चित्रित किए जाने वाले डेटा पॉइंट को लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPieSplitCustomPointCollection](../ipiesplitcustompointcollection/)\> [get_PieSplitCustomPoints](./get_piesplitcustompoints/)() override | एक कस्टम स्प्लिट वाले pie-of-pie या bar-of-pie चार्ट के लिए कस्टम स्प्लिट जानकारी। इसमें वह डेटा पॉइंट्स होते हैं जो दूसरे पाई या बार में चित्रित किए जाएंगे। केवल पढ़ने योग्य [PieSplitCustomPointCollection](../piesplitcustompointcollection/)। |
| **double** [get_PieSplitPosition](./get_piesplitposition/)() override | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में हैं। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। **double** पढ़ें। |
| **bool** [get_PlotOnSecondAxis](./get_plotonsecondaxis/)() override | बताता है कि इस समूह की श्रृंखलाएँ द्वितीयक अक्ष पर प्लॉट की गई हैं या नहीं। केवल पढ़ने योग्य **bool**। |
| **uint16_t** [get_SecondPieSize](./get_secondpiesize/)() override | pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच)। **uint16_t** पढ़ें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)\> [get_Series](./get_series/)() override | श्रृंखलाओं का संग्रह लौटाता है। केवल पढ़ने योग्य [IChartSeriesReadonlyCollection](../ichartseriesreadonlycollection/)। |
| [CombinableSeriesTypesGroup](../combinableseriestypesgroup/) [get_Type](./get_type/)() override | इस श्रृंखला समूह का प्रकार लौटाता है। केवल पढ़ने योग्य [CombinableSeriesTypesGroup](../combinableseriestypesgroup/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IUpDownBarsManager](../iupdownbarsmanager/)\> [get_UpDownBars](./get_updownbars/)() override | Line या Stock-चार्ट के अप/डाउन बार तक पहुंच प्रदान करता है। केवल पढ़ने योग्य [IUpDownBarsManager](../iupdownbarsmanager/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartSeries](../ichartseries/)\> [idx_get](./idx_get/)(**int32_t**) override | निर्दिष्ट इंडेक्स पर तत्व प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के साथ वैल्यु टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_BubbleSizeRepresentation](./set_bubblesizerepresentation/)([BubbleSizeRepresentationType](../bubblesizerepresentationtype/)) override | बबल चार्ट पर बबल आकार मानों को कैसे प्रदर्शित किया जाता है, इसे निर्दिष्ट करता है। [BubbleSizeRepresentationType](../bubblesizerepresentationtype/) लिखें। |
| void [set_BubbleSizeScale](./set_bubblesizescale/)(**int32_t**) override | बबल चार्ट के लिए स्केल फ़ैक्टर निर्दिष्ट करता है (डिफ़ॉल्ट आकार के 0 से 300 प्रतिशत तक)। **int32_t** लिखें। |
| void [set_DoughnutHoleSize](./set_doughnutholesize/)(**uint8_t**) override | डोनट चार्ट में छेद का आकार निर्दिष्ट करता है (प्लॉट क्षेत्र के आकार के 0 से 90 प्रतिशत तक)। **uint8_t** लिखें। |
| void [set_FirstSliceAngle](./set_firstsliceangle/)(**uint16_t**) override | पहले पाई या डोनट चार्ट स्लाइस का कोण डिग्री में सेट करता है (ऊपर से घड़ी की दिशा में, 0 से 360 डिग्री)। **uint16_t** लिखें। |
| void [set_GapDepth](./set_gapdepth/)(**uint16_t**) override | 3D चार्ट में डेटा श्रृंखलाओं के बीच की दूरी को मार्कर की चौड़ाई के प्रतिशत में सेट करता है। **uint16_t** लिखें। |
| void [set_GapWidth](./set_gapwidth/)(**uint16_t**) override | बार या कॉलम क्लस्टर के बीच की जगह को बार या कॉलम की चौड़ाई के प्रतिशत में सेट करता है। **uint16_t** लिखें। |
| void [set_HasSeriesLines](./set_hasserieslines/)(**bool**) override | यदि चार्ट में श्रृंखला रेखाएँ हैं तो सत्य। स्टैक्ड बार और OfPie चार्ट पर लागू। **bool** लिखें। |
| void [set_IsColorVaried](./set_iscolorvaried/)(**bool**) override | श्रृंखला में प्रत्येक डेटा मार्कर का अलग रंग है, यह निर्दिष्ट करता है। **bool** लिखें। |
| void [set_Overlap](./set_overlap/)(**int8_t**) override | 2D चार्ट पर बार और कॉलम कितनी ओवरलैप करेंगे, इसे प्रतिशत में निर्दिष्ट करता है ( -100% से 100% तक)। |
| void [set_PieSplitBy](./set_piesplitby/)([PieSplitType](../piesplittype/)) override | pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में कौन से डेटा पॉइंट हैं, इसे निर्धारित करने का तरीका निर्दिष्ट करता है। [PieSplitType](../piesplittype/) लिखें। |
| void [set_PieSplitPosition](./set_piesplitposition/)(**double**) override | एक मान निर्दिष्ट करता है जिसका उपयोग यह निर्धारित करने के लिए किया जाएगा कि कौन से डेटा पॉइंट्स pie-of-pie या bar-of-pie चार्ट में दूसरे पाई या बार में हैं। यह PieSplitBy प्रॉपर्टी के साथ उपयोग किया जाता है। **double** लिखें। |
| void [set_SecondPieSize](./set_secondpiesize/)(**uint16_t**) override | pie-of-pie या bar-of-pie चार्ट के दूसरे पाई या बार का आकार, पहले पाई के आकार के प्रतिशत में (5 से 200 प्रतिशत के बीच)। **uint16_t** लिखें। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्गुमेंट को एक weak पॉइंटर सेट करें (shared के बजाय)। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## टिप्पणी

1) ChartSeriesGroupCollection क्लास और CombinableSeriesTypesGroup एन्‍युम के लिए सारांश और टिप्पणी देखें। 2) श्रृंखला का समूह कुछ श्रृंखला गुणों को शामिल करता है जो समूह में प्रत्येक श्रृंखला के लिए सामान्य हैं (\"series group properties\"). [ChartSeriesGroup](./) क्लास में \"series group properties\" पढ़ने/लिखने योग्य हैं। \"series group properties\" में से प्रत्येक [ChartSeries](../chartseries/) क्लास में केवल-पढ़ने योग्य प्रोजेक्शन रख सकता है। 

## देखें

* क्लास [IChartSeriesGroup](../ichartseriesgroup/)
* क्लास [IDOMObject](../../aspose.slides/idomobject/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
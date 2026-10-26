---
title: DataLabelFormat
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: DataLabel के लिए फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।
type: docs
weight: 391
url: /hi/aspose.slides.charts/datalabelformat/
---
## DataLabelFormat वर्ग

[DataLabel](../datalabel/) के लिए फ़ॉर्मेटिंग विकल्पों का प्रतिनिधित्व करता है।

```cpp
class DataLabelFormat : public Aspose::Slides::PVIObject,
                        public Aspose::Slides::Charts::IDataLabelFormat
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](../../aspose.slides/pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्दिष्ट वस्तु के साथ तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंज़ प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली का फ्लोटिंग पॉइंट तुलना को अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है, फिर भी दो NaN को बराबर माना जाता है, इस प्रकार C#-शैली का फ्लोटिंग पॉइंट तुलना को अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | चार्ट लौटाता है। केवल-पढ़ने योग्य [IChart](../ichart/)। |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | डेटा लेबल के फ़ॉर्मेट का प्रतिनिधित्व करता है। केवल-पढ़ने योग्य [IFormat](../iformat/)। |
| **bool** [get_IsNumberFormatLinkedToSource](./get_isnumberformatlinkedtosource/)() override | पढ़ें **bool**। |
| [System::String](../../system/string/) [get_NumberFormat](./get_numberformat/)() override | DataLabels ऑब्जेक्ट के लिए फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। पढ़ें [System::String](../../system/string/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | Parent_Immediate ऑब्जेक्ट लौटाता है। केवल-पढ़ने योग्य [IDOMObject](../../aspose.slides/idomobject/)। |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | पैरेंट [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) लौटाता है। केवल-पढ़ने योग्य [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)। |
| [LegendDataLabelPosition](../legenddatalabelposition/) [get_Position](./get_position/)() override | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। पढ़ें [LegendDataLabelPosition](../legenddatalabelposition/)। |
| [System::String](../../system/string/) [get_Separator](./get_separator/)() override | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले सेपरेटर का प्रतिनिधित्व करने वाले Variant को सेट करता है या लौटाता है। पढ़ें [System::String](../../system/string/)। |
| **bool** [get_ShowBubbleSize](./get_showbubblesize/)() override | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True बबल आकार मान दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowCategoryName](./get_showcategoryname/)() override | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowLabelAsDataCallout](./get_showlabelasdatacallout/)() override | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| **bool** [get_ShowLabelValueFromCell](./get_showlabelvaluefromcell/)() override | निर्दिष्ट चार्ट के डेटा लेबल सेल मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True सेल मान दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowLeaderLines](./get_showleaderlines/)() override | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइनों के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True लीडर लाइनों को दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowLegendKey](./get_showlegendkey/)() override | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। यदि डेटा लेबल लेजेंड कुंजी दिखाई देती है तो True। पढ़ें **bool**। |
| **bool** [get_ShowPercentage](./get_showpercentage/)() override | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowSeriesName](./get_showseriesname/)() override | एक Boolean लौटाता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम के प्रदर्शन व्यवहार को दर्शाता है। True श्रृंखला नाम दिखाने के लिए। False छिपाने के लिए। पढ़ें **bool**। |
| **bool** [get_ShowValue](./get_showvalue/)() override | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाने के लिए। पढ़ें **bool**। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | चार्ट टेक्स्ट फ़ॉर्मेट लौटाता है। केवल-पढ़ने योग्य [IChartTextFormat](../icharttextformat/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](../../aspose.slides/pviobject/gethashcode/)() const override | हैश कोड लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि क्या ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों को क्लोन करने में सक्षम बनाता है। |
| [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है मूल्य प्रकार ऑब्जेक्ट को nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकृत संस्करण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकृत संस्करण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_IsNumberFormatLinkedToSource](./set_isnumberformatlinkedtosource/)(**bool**) override | लिखें **bool**। |
| void [set_NumberFormat](./set_numberformat/)([System::String](../../system/string/)) override | DataLabels ऑब्जेक्ट के फ़ॉर्मेट स्ट्रिंग का प्रतिनिधित्व करता है। लिखें [System::String](../../system/string/)। |
| void [set_Position](./set_position/)([LegendDataLabelPosition](../legenddatalabelposition/)) override | डेटा लेबल की स्थिति का प्रतिनिधित्व करता है। लिखें [LegendDataLabelPosition](../legenddatalabelposition/)। |
| void [set_Separator](./set_separator/)([System::String](../../system/string/)) override | चार्ट पर डेटा लेबल के लिए उपयोग किए जाने वाले सेपरेटर का प्रतिनिधित्व करने वाले Variant को सेट करता है या लौटाता है। लिखें [System::String](../../system/string/)। |
| void [set_ShowBubbleSize](./set_showbubblesize/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल बबल आकार मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True बबल आकार मान दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowCategoryName](./set_showcategoryname/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल श्रेणी नाम के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True चार्ट पर डेटा लेबल के लिए श्रेणी नाम दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowLabelAsDataCallout](./set_showlabelasdatacallout/)(**bool**) override | निर्धारित करता है कि निर्दिष्ट चार्ट का डेटा लेबल डेटा कॉलआउट के रूप में या डेटा लेबल के रूप में प्रदर्शित होगा। |
| void [set_ShowLabelValueFromCell](./set_showlabelvaluefromcell/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल सेल मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True सेल मान दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowLeaderLines](./set_showleaderlines/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल लीडर लाइनों के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True लीडर लाइनों को दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowLegendKey](./set_showlegendkey/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल लेजेंड कुंजी के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। यदि डेटा लेबल लेजेंड कुंजी दिखाई देती है तो True। लिखें **bool**। |
| void [set_ShowPercentage](./set_showpercentage/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowSeriesName](./set_showseriesname/)(**bool**) override | एक Boolean सेट करता है जो चार्ट पर डेटा लेबल के लिए श्रृंखला नाम के प्रदर्शन व्यवहार को दर्शाता है। True श्रृंखला नाम दिखाने के लिए। False छिपाने के लिए। लिखें **bool**। |
| void [set_ShowValue](./set_showvalue/)(**bool**) override | निर्दिष्ट चार्ट के डेटा लेबल प्रतिशत मान के प्रदर्शन व्यवहार का प्रतिनिधित्व करता है। True प्रतिशत मान दिखाता है। False छिपाने के लिए। लिखें **bool**। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्प्लेट आर्ग्यूमेंट **uint32_t** को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## संबंधित देखें

* क्लास [PVIObject](../../aspose.slides/pviobject/)
* क्लास [IDataLabelFormat](../idatalabelformat/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
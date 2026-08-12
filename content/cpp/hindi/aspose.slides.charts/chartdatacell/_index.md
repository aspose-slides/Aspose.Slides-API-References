---
title: ChartDataCell
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: चार्ट डेटा के लिए सेल का प्रतिनिधित्व करता है।
type: docs
weight: 131
url: /hi/aspose.slides.charts/chartdatacell/
---
## ChartDataCell क्लास

चार्ट डेटा के लिए सेल का प्रतिनिधित्व करता है।

```cpp
class ChartDataCell : public Aspose::Slides::Charts::IChartDataCell
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Calculate](./calculate/)(**bool**) override | यदि सेल में फ़ॉर्मूला है, तो मूल्य उस फ़ॉर्मूला के आधार पर अपडेट किया जाएगा। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके करती है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करती है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() override | वर्कशीट प्राप्त करता है। केवल-पठन [IChartDataWorksheet](../ichartdataworksheet/)। |
| **int32_t** [get_Column](./get_column/)() override | वह कॉलम इंडेक्स लौटाता है जिस वर्कशीट में सेल स्थित है। केवल-पठन **int32_t**। |
| [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() override | संख्याओं और तिथियों का कस्टम डिस्प्ले फॉर्मेट प्राप्त करता है। यदि मान खाली है तो PresetNumberFormat मान उपयोग किया जाएगा। पढ़ें [System::String](../../system/string/)। |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | A1-शैली में फ़ॉर्मूला प्राप्त करता है। |
| **bool** [get_IsHidden](./get_ishidden/)() override | निर्धारित करता है कि सेल छिपा है या नहीं। केवल-पठन **bool**। |
| **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() override | संख्याओं और तिथियों का बिल्ट-इन डिस्प्ले फॉर्मेट प्राप्त करता है। प्रीसेट संख्या [0..22] या [37..49] के भीतर होनी चाहिए। पढ़ें **uint8_t**। |
| [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() override | R1C1-शैली में फ़ॉर्मूला प्राप्त करता है। |
| **int32_t** [get_Row](./get_row/)() override | वह पंक्ति इंडेक्स लौटाता है जिस वर्कशीट में सेल स्थित है। केवल-पठन **int32_t**। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | सेल का मान प्राप्त करता है। पढ़ें [System::Object](../../system/object/)। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स मामले के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) override | संख्याओं और तिथियों का कस्टम डिस्प्ले फॉर्मेट सेट करता है। यदि मान खाली है तो PresetNumberFormat मान उपयोग किया जाएगा। लिखें [System::String](../../system/string/)। |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | A1-शैली में फ़ॉर्मूला सेट करता है। |
| void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) override | संख्याओं और तिथियों का बिल्ट-इन डिस्प्ले फॉर्मेट सेट करता है। प्रीसेट संख्या [0..22] या [37..49] के भीतर होनी चाहिए। लिखें **uint8_t**। |
| void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) override | R1C1-शैली में फ़ॉर्मूला सेट करता है। |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | सेल का मान सेट करता है। लिखें [System::Object](../../system/object/)। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करें। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर घटाता है और वापस करता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [IChartDataCell](../ichartdatacell/)
* नेमस्पेस [Aspose::Slides::Charts](../)
* लाइब्रेरी [Aspose.Slides](../../)
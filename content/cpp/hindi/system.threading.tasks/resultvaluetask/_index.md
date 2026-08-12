---
title: ResultValueTask
second_title: Aspose.Slides for C++ API संदर्भ
description: एक हाइब्रिड टास्क-समान प्रकार का प्रतिनिधित्व करता है जो सीधे परिणाम मान या ResultTask<T> को रैप कर सकता है।
type: docs
weight: 53
url: /hi/system.threading.tasks/resultvaluetask/
---
## ResultValueTask क्लास

एक हाइब्रिड टास्क-समतुल्य प्रकार का प्रतिनिधित्व करता है जो सीधे परिणाम मान या ResultTask<T> को रैप कर सकता है।

```cpp
template<typename T>class ResultValueTask : public System::IEquatable<ResultValueTask<T>>,
                                            public System::Details::BoxableObjectBase
```

### टेम्पलेट पैरामीटर्स

| पैरामीटर | विवरण |
| --- | --- |
| T | टास्क द्वारा उत्पन्न परिणाम का प्रकार। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [RTaskPtr](../../system/rtaskptr/)\<T\> [AsTask](./astask/)() const | इस [ResultValueTask](./) को ResultTask<T> के एक साझा पॉइंटर में परिवर्तित करता है। |
| [Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable](../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)\<T\> [ConfigureAwait](./configureawait/)(**bool**) const | इस टास्क के लिए एक अवेटर कॉन्फ़िगर करता है। |
| **bool** [Equals](./equals/)([ResultValueTask](./)) override | निर्धारित करता है कि यह इंस्टेंस अन्य [ResultValueTask](./) इंस्टेंस के बराबर है या नहीं। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | निर्धारित करता है कि यह इंस्टेंस अन्य ऑब्जेक्ट के बराबर है या नहीं। |
| virtual **bool** [Equals](../../system/iequatable/equals/)(T) | निर्धारित करता है कि वर्तमान और निर्दिष्ट ऑब्जेक्ट समान हैं या नहीं। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, NaN सहित। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, NaN सहित। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_IsCanceled](./get_iscanceled/)() const | एक मान प्राप्त करता है जो यह दर्शाता है कि टास्क रद्द होने के कारण पूरा हुआ। |
| **bool** [get_IsCompleted](./get_iscompleted/)() const | एक मान प्राप्त करता है जो यह दर्शाता है कि टास्क पूरा हो चुका है। |
| **bool** [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | एक मान प्राप्त करता है जो यह दर्शाता है कि टास्क सफलतापूर्वक पूरा हुआ। |
| **bool** [get_IsFaulted](./get_isfaulted/)() const | एक मान प्राप्त करता है जो यह दर्शाता है कि टास्क अनहैंडल्ड एक्सेप्शन के कारण पूरा हुआ। |
| T [get_Result](./get_result/)() | पूरा हुए टास्क का परिणाम प्राप्त करता है। |
| [Runtime::CompilerServices::ResultValueTaskAwaiter](../../system.runtime.compilerservices/resultvaluetaskawaiter/)\<T\> [GetAwaiter](./getawaiter/)() const | await अभिव्यक्तियों का समर्थन करने के लिए इस टास्क के लिए एक अवेटर प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस कاؤن्टर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समतुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समतुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समतुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| **bool** [operator!=](./operator_not_equal/)(const [ResultValueTask](./)\&) const | [ResultValueTask](./) के लिए असमानता ऑपरेटर। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [ResultValueTask](./)\&) const | [ResultValueTask](./) के लिए समानता ऑपरेटर। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट कम करता है। |
|  [ResultValueTask](./resultvaluetask/)() | एक खाली, अनइनिशियलाइज़्ड [ResultValueTask](./) बनाता है। |
|  [ResultValueTask](./resultvaluetask/)(const T\&) | निर्दिष्ट परिणाम के साथ एक पूर्ण [ResultValueTask](./) बनाता है। |
|  [ResultValueTask](./resultvaluetask/)(const [RTaskPtr](../../system/rtaskptr/)\<T\>\&) | ResultTask<T> के एक साझा पॉइंटर से एक [ResultValueTask](./) बनाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समतुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टिप्पणी

[ResultValueTask](./) [ValueTask](../valuetask/) के लाभ (सिंक्रोनस परिणामों के लिए घटित एलोकेशन) को मौजूदा ResultTask<T> ऑब्जेक्ट्स को रैप करने की क्षमता के साथ जोड़ता है। यह एक awaitable इंटरफ़ेस और विभिन्न टास्क स्थिति निरीक्षण मेथड प्रदान करता है।

## देखें

* क्लास [IEquatable](../../system/iequatable/)
* नामस्थान [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)
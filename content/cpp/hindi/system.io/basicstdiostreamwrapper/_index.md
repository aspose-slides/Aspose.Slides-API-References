---
title: BasicSTDIOStreamWrapper
second_title: Aspose.Slides for C++ API संदर्भ
description: "यह std::basic_iostream और उसके व्युत्पन्न वस्तुओं के लिए System.IO.Stream समान रैपर का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन टाइम त्रुटियाँ और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों को तर्क के रूप में पास करने के लिए उपयोग करें।"
type: docs
weight: 1
url: /hi/system.io/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper क्लास


एक [System.IO.Stream](../stream/)-समान रैपर को std::basic_iostream और उसके व्युत्पन्न वस्तुओं के लिए दर्शाता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
template<typename T,typename>class BasicSTDIOStreamWrapper : public System::IO::BasicSTDIStreamWrapper<T>,
                                                             public System::IO::BasicSTDOStreamWrapper<T>
```

## मेथड्स

| Method | Description |
| --- | --- |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(std::basic_iostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/), [STDIOStreamPositionPreference](../stdiostreampositionpreference/)) | नया [BasicSTDIOStreamWrapper](./) का एक नया उदाहरण बनाता है। |
|  [BasicSTDIOStreamWrapper](./basicstdiostreamwrapper/)(const [BasicSTDIOStreamWrapper](./)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | नया [BasicSTDIStreamWrapper](../basicstdistreamwrapper/) का एक नया उदाहरण बनाता है। |
|  [BasicSTDIStreamWrapper](../basicstdistreamwrapper/basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(std::basic_ostream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | नया [BasicSTDOStreamWrapper](../basicstdostreamwrapper/) का एक नया उदाहरण बनाता है। |
|  [BasicSTDOStreamWrapper](../basicstdostreamwrapper/basicstdostreamwrapper/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस रीड ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस राइट ऑपरेशन शुरू करता है। |
| virtual void [Close](../stream/close/)() | स्ट्रीम को बंद करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](../stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूर्ण होने तक इंतज़ार करता है। |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | असिंक्रोनस राइट ऑपरेशन को समाप्त करता है। निर्दिष्ट असिंक्रोनस राइट ऑपरेशन के पूर्ण होने तक इंतज़ार करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को एमुलेट करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ्लोटिंग पॉइंट तुलना को एमुलेट करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के साथ भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [Flush](./flush/)() override | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र किए गए डेटा को अंतर्निहित स्टोरेज में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, बफ़र किए गए डेटा को अंतर्निहित डिवाइस में लिखता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, बफ़र किए गए डेटा को अंतर्निहित डिवाइस में लिखता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | निर्धारित करता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | यह मान लौटाता है कि वर्तमान स्ट्रीम टाइम-आउट कर सकता है या नहीं। |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | निर्धारित करता है कि स्ट्रीम लिखने का समर्थन करता है या नहीं। |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | स्ट्रीम की लंबाई लौटाता है। |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम पढ़ने का प्रयास कितनी देर तक करेगा इससे पहले कि टाइम-आउट हो। |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम लिखने का प्रयास कितनी देर तक करेगा इससे पहले कि टाइम-आउट हो। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य टाइप द्वारा वर्णित टाइप का उदाहरण है या नहीं। C# के 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। कुछ नहीं कॉपी करता, वास्तव में, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस के कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [BasicSTDIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIOStreamWrapper](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\& [operator=](../basicstdistreamwrapper/operator_equal/)(const [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ नहीं कॉपी करता, वास्तव में, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस के कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\& [operator=](../basicstdostreamwrapper/operator_equal/)(const [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट बाइट्स की संख्या पढ़ता है, अन्यथा निर्दिष्ट कैरेक्टर्स की संख्या पढ़ता है और उन्हें **uint8_t** टाइप में बदलता है। पढ़े गए परिणाम को निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट बाइट्स की संख्या पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट बाइट्स की संख्या पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट बाइट्स की संख्या पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से वर्तमान स्ट्रीम से बाइट्स की श्रृंखला पढ़ता है, पढ़ी गई बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से वर्तमान स्ट्रीम से बाइट्स की श्रृंखला पढ़ता है, पढ़ी गई बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| int [ReadByte](./readbyte/)() override | यदि रैपिंग मोड बाइनरी है, तो अंतिम डिकोडेड कैरेक्टर संग्रह से एक बाइट पढ़ता है, अन्यथा स्ट्रीम से एक कैरेक्टर पढ़ता है और उसे **uint8_t** टाइप में बदलता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr से रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशिष्टकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | साझा रेफ़रेंस काउंट को निर्दिष्ट मान द्वारा घटाता है। |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI जानकारी। |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्वित स्ट्रीम की स्थिति सेट करता है। |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | यह मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट कर सकता है या नहीं। |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | मिलीसेकंड में वह मान सेट करता है जो निर्धारित करता है कि स्ट्रीम पढ़ने का प्रयास कितनी देर तक करेगा इससे पहले कि टाइम-आउट हो। |
| void [SetLength](./setlength/)(**int64_t**) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्वित स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्प्लेट के n-वें आर्ग्यूमेंट को वीक पॉइंटर सेट करता है (शेयर्ड के बजाय)। कंटेनर में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट एरे की निर्दिष्ट उप-रेंज को स्ट्रीम में लिखता है, अन्यथा बाइट एरे की उप-रेंज को char_type टाइप में बदलता है और फिर परिणाम को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे की निर्दिष्ट उप-रेंज को स्ट्रीम में लिखता है। |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे की निर्दिष्ट उप-रेंज को स्ट्रीम में लिखता है। |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन की निर्दिष्ट उप-रेंज को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से वर्तमान स्ट्रीम में बाइट्स की श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या के अनुसार वर्तमान स्थिति को आगे बढ़ाता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से वर्तमान स्ट्रीम में बाइट्स की श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या के अनुसार वर्तमान स्थिति को आगे बढ़ाता है, और कैंसलेशन अनुरोधों की निगरानी करता है। |
| void [WriteByte](./writebyte/)(**uint8_t**) override | यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट unsigned 8-bit इंटीजर मान को स्ट्रीम में लिखता है, अन्यथा उसे char_type टाइप में बदलता है और फिर परिणाम को स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [Null](../stream/null/) | कोई अंतर्निहित स्टोरेज न वाला स्ट्रीम। |
## टाइपडिफ़्स

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [BaseIType](./baseitype/) |  |
| [BaseOType](./baseotype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
## देखें

* Class [BasicSTDIStreamWrapper](../basicstdistreamwrapper/)
* Class [BasicSTDOStreamWrapper](../basicstdostreamwrapper/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)
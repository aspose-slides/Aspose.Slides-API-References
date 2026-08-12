---
title: BasicSTDIStreamWrapper
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "std::basic_istream और उसके व्युत्पन्न ऑब्जेक्ट्स के लिए System.IO.Stream-सम प्रकार का रैपर दर्शाता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 14
url: /hi/system.io/basicstdistreamwrapper/
---
## BasicSTDIStreamWrapper क्लास

Represents a [System.IO.Stream](../stream/)-like wrapper for std::basic_istream and its derived objects. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
template<typename T,typename>class BasicSTDIStreamWrapper : public virtual System::IO::STDIOStreamWrapperBase<T>
```

## विधियां

| मेथड | विवरण |
| --- | --- |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(std::basic_istream\<[char_type](../stdiostreamwrapperbase/char_type/), [traits_type](../stdiostreamwrapperbase/traits_type/)\>\&, [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)) | [BasicSTDIStreamWrapper](./) का एक नया इंस्टेंस बनाता है। |
|  [BasicSTDIStreamWrapper](./basicstdistreamwrapper/)(const [BasicSTDIStreamWrapper](./)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस रीड ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस राइट ऑपरेशन शुरू करता है। |
| virtual void [Close](../stream/close/)() | स्ट्रीम को बंद करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](../stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूरा होने की प्रतीक्षा करता है। |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस राइट ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस राइट ऑपरेशन के पूरे होने की प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| void [Flush](./flush/)() override | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र्ड डेटा को आधारभूत स्टोरेज में लिखता है। समर्थित नहीं! |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, किसी भी बफ़र्ड डेटा को आधारभूत डिवाइस में लिखने का कारण बनता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र्स को साफ़ करता है, किसी भी बफ़र्ड डेटा को आधारभूत डिवाइस में लिखने का कारण बनता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| **bool** [get_CanSeek](../stdiostreamwrapperbase/get_canseek/)() const override | स्ट्रीम की सीकिंग समर्थन की जांच करता है। |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | वर्तमान स्ट्रीम के टाइम-आउट होने की स्थिति निर्धारित करने वाला मान प्राप्त करता है। |
| **bool** [get_CanWrite](../stdiostreamwrapperbase/get_canwrite/)() const override | स्ट्रीम की लेखन समर्थन की जांच करता है। |
| **int64_t** [get_Length](../stdiostreamwrapperbase/get_length/)() const override | स्ट्रीम की लंबाई लौटाता है। |
| **int64_t** [get_Position](../stdiostreamwrapperbase/get_position/)() const override | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर पढ़ने की कोशिश करेगा। |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर लिखने की कोशिश करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [BasicSTDIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSTDIStreamWrapper](./)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\& [operator=](../stdiostreamwrapperbase/operator_equal/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | कॉपी असाइनमेंट ऑपरेटर। हटाया गया। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | यदि रैपिंग मोड बाइनरी है, तो स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है, अन्यथा निर्दिष्ट संख्या में कैरेक्टर्स पढ़ता है और उन्हें **uint8_t** टाइप में परिवर्तित करता है। पढ़ने का परिणाम निर्दिष्ट बाइट ऐरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है। |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है। |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक क्रम पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक क्रम पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| int [ReadByte](./readbyte/)() override | यदि रैपिंग मोड बाइनरी है, तो अंतिम डिकोडेड कैरेक्टर स्टोरेज से एक बाइट पढ़ता है, अन्यथा स्ट्रीम से एक कैरेक्टर पढ़ता है और उसे **uint8_t** टाइप में परिवर्तित करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
|  [RTTI_INFO_TEMPLATE_CLASS](./rtti_info_template_class/)([ThisType](../stdiostreamwrapperbase/thistype/), [ThisTypeBaseTypesInfo](../stdiostreamwrapperbase/thistypebasetypesinfo/)) | RTTI जानकारी। |
| **int64_t** [Seek](../stdiostreamwrapperbase/seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है। |
| void [set_Position](../stdiostreamwrapperbase/set_position/)(**int64_t**) override | स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | मिलीसेकंड में वह मान सेट करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर पढ़ने की कोशिश करेगा। |
| void [SetLength](./setlength/)(**int64_t**) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की लंबाई सेट करता है। समर्थित नहीं! |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वाँ टेम्पलेट आर्ग्युमेंट एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [STDIOStreamWrapperBase](../stdiostreamwrapperbase/stdiostreamwrapperbase/)(const [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)\&) | कॉपी कंस्ट्रक्टर। हटाया गया। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट बाइट ऐरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है, अन्यथा निर्दिष्ट बाइट ऐरे से उप-रेंज के बाइट्स को char_type टाइप में परिवर्तित करके परिणाम को स्ट्रीम में लिखता है। समर्थित नहीं! |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट ऐरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट ऐरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम में असिंक्रोनस रूप से बाइट्स की एक क्रम लिखता है, लिखे गए बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम में असिंक्रोनस रूप से बाइट्स की एक क्रम लिखता है, लिखे गए बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| void [WriteByte](./writebyte/)(**uint8_t**) override | यदि रैपिंग मोड बाइनरी है, तो निर्दिष्ट unsigned 8-bit integer मान को स्ट्रीम में लिखता है, अन्यथा इसे char_type टाइप में परिवर्तित करके परिणाम को स्ट्रीम में लिखता है। समर्थित नहीं! |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Null](../stream/null/) | बिना आधारभूत स्टोरेज वाला स्ट्रीम। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ThisType](./thistype/) |  |
| [BaseType](./basetype/) |  |
| [ThisTypeBaseTypesInfo](./thistypebasetypesinfo/) |  |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |

## देखें भी

* क्लास [STDIOStreamWrapperBase](../stdiostreamwrapperbase/)
* नेमस्पेस [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)
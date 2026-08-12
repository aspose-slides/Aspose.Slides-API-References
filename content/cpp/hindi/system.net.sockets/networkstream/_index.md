---
title: NetworkStream
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "नेटवर्क एक्सेस के लिए डेटा की अंतर्निहित स्ट्रीम प्रदान करता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फ़ॉल्ट का कारण बन सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों में पास करें।"
type: docs
weight: 40
url: /hi/system.net.sockets/networkstream/
---
## NetworkStream class

नेटवर्क एक्सेस के लिए डेटा की अंतर्निहित स्ट्रीम प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों में पास करें।

```cpp
class NetworkStream : public System::IO::Stream
```

## विधियाँ

| विधि | वर्णन |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एक असिंक्रोनस पढ़ने का ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस पढ़ने का ऑपरेशन शुरू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है। |
| void [Close](./close/)(int) | निर्दिष्ट समय समाप्त होने के बाद वर्तमान इंस्टेंस को बंद करता है। |
| virtual void [Close](../../system.io/stream/close/)() | स्ट्रीम को बंद करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स की कॉपी करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके, निर्दिष्ट स्ट्रीम में बाइट्स की कॉपी करता है। |
| void [Dispose](../../system.io/stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और स्ट्रीम को बंद करता है। |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | निर्दिष्ट असिंक्रोनस पढ़ने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस पढ़ने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | एक असिंक्रोनस लिखने का ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस लिखने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस लिखने का ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस लिखने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| void [Flush](./flush/)() override | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र किए गए डेटा को अंतर्निहित स्टोरेज में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए गए डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| **bool** [get_CanRead](./get_canread/)() const override | स्ट्रीम पढ़ने योग्य है या नहीं, निर्धारित करता है। |
| **bool** [get_CanSeek](./get_canseek/)() const override | स्ट्रीम सीकिंग का समर्थन करता है या नहीं, निर्धारित करता है। |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | एक मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम आउट हो सकता है या नहीं। |
| **bool** [get_CanWrite](./get_canwrite/)() const override | स्ट्रीम लिखने योग्य है या नहीं, निर्धारित करता है। |
| **bool** [get_DataAvailable](./get_dataavailable/)() const | एक मान लौटाता है जो संकेत करता है कि पढ़ने के लिए डेटा उपलब्ध है या नहीं। |
| **int64_t** [get_Length](./get_length/)() const override | स्ट्रीम की लंबाई बाइट्स में लौटाता है। |
| **int64_t** [get_Position](./get_position/)() const override | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | मिलीसेकंड में एक मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम आउट होने से पहले कितनी देर पढ़ने का प्रयास करेगा। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\> [get_Socket](./get_socket/)() | अंतर्निहित [Socket](../socket/) प्राप्त करता है। |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | मिलीसेकंड में एक मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम आउट होने से पहले कितनी देर लिखने का प्रयास करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>) | एक नया इंस्टेंस बनाता है। |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, [System::IO::FileAccess](../../system.io/fileaccess/), **bool**) | एक नया इंस्टेंस बनाता है। |
|  [NetworkStream](./networkstream/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Sockets::Socket](../socket/)\>, **bool**) | एक नया इंस्टेंस बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी नहीं कॉपी करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से बाइट्स की श्रृंखला पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम की स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से बाइट्स की श्रृंखला पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम की स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | स्ट्रीम से एकल बाइट पढ़ता है और पढ़े हुए बाइट के मान के समान 32-बिट पूर्णांक मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है। |
| void [set_Position](./set_position/)(**int64_t**) override | स्ट्रीम की स्थिति सेट करता है। |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम आउट हो सकता है या नहीं। |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम आउट हो सकता है या नहीं। |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | मिलीसेकंड में एक मान सेट करता है जो निर्धारित करता है कि स्ट्रीम टाइम आउट होने से पहले कितनी देर पढ़ने का प्रयास करेगा। |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | मिलीसेकंड में एक मान सेट करता है जो निर्धारित करता है कि स्ट्रीम टाइम आउट होने से पहले कितनी देर पढ़ने का प्रयास करेगा। |
| void [SetLength](./setlength/)(**int64_t**) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट उप-रेंज के बाइट्स को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से बाइट्स की श्रृंखला लिखता है, लिखे गए बाइट्स की संख्या से स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से बाइट्स की श्रृंखला लिखता है, लिखे गए बाइट्स की संख्या से स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | स्ट्रीम में निर्दिष्ट अनसाइन्ड 8-बिट पूर्णांक मान लिखता है। |
| virtual  [~NetworkStream](./~networkstream/)() | वर्तमान इंस्टेंस को नष्ट करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | वर्णन |
| --- | --- |
| static [Null](../../system.io/stream/null/) | कोई अंतर्निहित स्टोरेज नहीं वाला स्ट्रीम। |

## संबंधित देखें

* क्लास [Stream](../../system.io/stream/)
* नामस्थान [System::Net::Sockets](../)
* लाइब्रेरी [Aspose.Slides](../../)
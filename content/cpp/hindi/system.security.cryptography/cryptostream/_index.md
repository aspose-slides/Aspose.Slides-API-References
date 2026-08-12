---
title: CryptoStream
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "क्रिप्टोग्राफिक फ़ंक्शन के साथ मौजूदा स्ट्रीम को लपेटने वाला स्ट्रीम कार्यान्वयन। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 53
url: /hi/system.security.cryptography/cryptostream/
---
## CryptoStream वर्ग

क्रिप्टोग्राफिक फ़ंक्शन के साथ मौजूदा स्ट्रीम को लपेटने वाला स्ट्रीम कार्यान्वयन। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। स्टैक पर या operator new का उपयोग करके इस प्रकार का उदाहरण कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन दोष उत्पन्न होंगे। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को तर्क के रूप में फ़ंक्शन को पास करने के लिए उपयोग करें।

```cpp
class CryptoStream : public System::IO::Stream
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस पढ़ने ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस लिखने ऑपरेशन शुरू करता है। |
| void [Close](./close/)() override | कनेक्शन बंद करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करते हुए निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
|  [CryptoStream](./cryptostream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\>\&, [CryptoStreamMode](../cryptostreammode/)) | निर्माता। |
| void [Dispose](../../system.io/stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | जब तक निर्दिष्ट असिंक्रोनस पढ़ने ऑपरेशन पूरा नहीं हो जाता, तब तक इंतजार करता है। |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस लिखने ऑपरेशन समाप्त करता है। जब तक निर्दिष्ट असिंक्रोनस लिखने ऑपरेशन पूरा नहीं हो जाता, तब तक इंतजार करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| void [Flush](./flush/)() override | रैप्ड स्ट्रीम में बफ़र को खाली करता है। कुछ नहीं करता क्योंकि ट्रांसफ़ॉर्म एल्गोरिद्म अभी भी अधिक डेटा की प्रतीक्षा कर सकता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र को साफ़ करता है, कोई भी बफ़र्ड डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | असिंक्रोनस रूप से इस स्ट्रीम के सभी बफ़र को साफ़ करता है, कोई भी बफ़र्ड डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| void [FlushFinalBlock](./flushfinalblock/)() | बफ़र में अभी भी मौजूद डेटा को स्ट्रीम में लिखता है। |
| **bool** [get_CanRead](./get_canread/)() const override | जांचता है कि स्ट्रीम पढ़ने योग्य है या नहीं। |
| **bool** [get_CanSeek](./get_canseek/)() const override | जांचता है कि स्ट्रीम seekable है या नहीं। |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | एक मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| **bool** [get_CanWrite](./get_canwrite/)() const override | जांचता है कि स्ट्रीम लिखने योग्य है या नहीं। |
| **int64_t** [get_Length](./get_length/)() const override | स्ट्रीम की लंबाई प्राप्त करता है। समर्थित नहीं है। |
| **int64_t** [get_Position](./get_position/)() const override | स्ट्रीम में वर्तमान स्थिति प्राप्त करता है। समर्थित नहीं है। |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | एक मान (मिलीसेकंड में) प्राप्त करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम पढ़ने का प्रयास कितनी देर तक करेगा। |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | एक मान (मिलीसेकंड में) प्राप्त करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम लिखने का प्रयास कितनी देर तक करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के एक इंस्टेंस को दर्शाता है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से डेटा पढ़ता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से डेटा पढ़ता है। |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक श्रृंखला पढ़ता है, पढ़ी गई बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक श्रृंखला पढ़ता है, पढ़ी गई बाइट्स की संख्या से स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और पढ़े गए बाइट के मान के समान 32-बिट पूर्णांक मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | स्ट्रीम में स्थिति की खोज करता है। समर्थित नहीं है। |
| void [set_Position](./set_position/)(**int64_t**) override | स्ट्रीम में स्थिति की खोज करता है। समर्थित नहीं है। |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | एक मान (मिलीसेकंड में) सेट करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम पढ़ने का प्रयास कितनी देर तक करेगा। |
| void [SetLength](./setlength/)(**int64_t**) override | स्ट्रीम का आकार खोजता है। समर्थित नहीं है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | टेम्पलेट के n-वें तर्क को एक वीक पॉइंटर (शेयर किया हुआ नहीं) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | डेटा को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | डेटा को स्ट्रीम में लिखता है। |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट सबरेन्ज बाइट्स को स्ट्रीम में लिखता है। |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट सबरेन्ज बाइट्स को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से बाइट्स की एक श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से बाइट्स की एक श्रृंखला लिखता है, लिखी गई बाइट्स की संख्या से इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | निर्दिष्ट unsigned 8-bit पूर्णांक मान को स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Null](../../system.io/stream/null/) | कोई अंतर्निहित स्टोरेज नहीं वाला स्ट्रीम। |

## देखें

* वर्ग [Stream](../../system.io/stream/)
* नामस्थान [System::Security::Cryptography](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: FileStream
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: "फ़ाइल स्ट्रीम का प्रतिनिधित्व करता है जो समकालिक और असिंक्रोनस पढ़ने और लिखने के ऑपरेशनों का समर्थन करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या assertion faults का कारण बन सकता है। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 287
url: /hi/system.io/filestream/
---
## FileStream वर्ग

एक फ़ाइल स्ट्रीम का प्रतिनिधित्व करता है जो सिंक्रोनस और असिंक्रोनस पढ़ने और लिखने के ऑपरेशनों का समर्थन करता है। इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या assertion faults का कारण बन सकता है। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें।

```cpp
class FileStream : public System::IO::Stream
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस पढ़ने ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस लिखने ऑपरेशन शुरू करता है। |
| void [Close](./close/)() override | वर्तमान [FileStream](./) ऑब्जेक्ट को बंद करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](../stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](../stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | जब तक निर्दिष्ट असिंक्रोनस पढ़ने ऑपरेशन पूरा न हो, तब तक प्रतीक्षा करता है। |
| virtual void [EndWrite](../stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस लिखने ऑपरेशन समाप्त करता है। जब तक निर्दिष्ट असिंक्रोनस लिखने ऑपरेशन पूरा न हो, तब तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/)) | [FileStream](./) वर्ग की नई इंस्टेंस बनाता है और इसे निर्दिष्ट पैरामीटर्स के साथ आरंभ करता है। |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, [FileOptions](../fileoptions/)) | [FileStream](./) वर्ग की नई इंस्टेंस बनाता है और इसे निर्दिष्ट पैरामीटर्स के साथ आरंभ करता है। |
|  [FileStream](./filestream/)(const [String](../../system/string/)\&, [FileMode](../filemode/), [FileAccess](../fileaccess/), [FileShare](../fileshare/), **int32_t**, **bool**) | [FileStream](./) वर्ग की नई इंस्टेंस बनाता है और इसे निर्दिष्ट पैरामीटर्स के साथ आरंभ करता है। |
|  [FileStream](./filestream/)(const [FileStream](./)\&) |  |
| void [Flush](./flush/)() override | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र्ड डेटा को अंतर्निहित फ़ाइल में लिखता है। |
| void [Flush](./flush/)(**bool**) | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र्ड डेटा को अंतर्निहित फ़ाइल में लिखता है। [Flush()](./flush/) मेथड का पर्याय है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र्ड डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../stream/flushasync/)() | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र्ड डेटा को अंतर्निहित डिवाइस में लिखता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| **bool** [get_CanRead](./get_canread/)() const override | निर्धारित करता है कि स्ट्रीम पढ़ी जा सकती है या नहीं। |
| **bool** [get_CanSeek](./get_canseek/)() const override | निर्धारित करता है कि स्ट्रीम सर्चिंग का समर्थन करती है या नहीं। |
| virtual **bool** [get_CanTimeout](../stream/get_cantimeout/)() const | एक मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकती है या नहीं। |
| **bool** [get_CanWrite](./get_canwrite/)() const override | निर्धारित करता है कि स्ट्रीम लिखने योग्य है या नहीं। |
| **int64_t** [get_Length](./get_length/)() const override | स्ट्रीम की लंबाई बाइट्स में लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() const | [FileStream](./) ऑब्जेक्ट द्वारा संलग्न फ़ाइल का नाम लौटाता है। |
| **int64_t** [get_Position](./get_position/)() const override | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| virtual int [get_ReadTimeout](../stream/get_readtimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर तक पढ़ने का प्रयास करेगी। |
| virtual int [get_WriteTimeout](../stream/get_writetimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर तक लिखने का प्रयास करेगी। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [FileStream](./)\& [operator=](./operator_equal/)(const [FileStream](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](../stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](../stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | वर्तमान स्ट्रीम से बाइट्स की एक अनुक्रम असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को अग्रसर करता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से बाइट्स की एक अनुक्रम असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिति को अग्रसर करता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| **int32_t** [ReadByte](./readbyte/)() override | स्ट्रीम से एकल बाइट पढ़ता है और पढ़े गए बाइट के मान के बराबर 32-बिट पूर्णांक मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है। |
| void [set_Position](./set_position/)(**int64_t**) override | स्ट्रीम को फ्लश करता है और फिर स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_ReadTimeout](../stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकती है या नहीं। |
| virtual void [set_WriteTimeout](../stream/set_writetimeout/)(int) | मिलीसेकंड में वह मान सेट करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर तक पढ़ने का प्रयास करेगी। |
| void [SetLength](./setlength/)(**int64_t**) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है। |
| void [Write](../stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है। |
| virtual void [Write](../stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट बाइट्स की उप-श्रेणी को स्ट्रीम में लिखता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) override | वर्तमान स्ट्रीम में बाइट्स की अनुक्रम असिंक्रोनस रूप से लिखता है, लिखे गए बाइट्स की संख्या से स्ट्रीम में वर्तमान स्थिति को अग्रसर करता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम में बाइट्स की अनुक्रम असिंक्रोनस रूप से लिखता है, लिखे गए बाइट्स की संख्या से स्ट्रीम में वर्तमान स्थिति को अग्रसर करता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| void [WriteByte](./writebyte/)(**uint8_t**) override | निर्दिष्ट unsigned 8-bit पूर्णांक मान को स्ट्रीम में लिखता है। |
|  [~FileStream](./~filestream/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static constexpr [DefaultBufferSize](./defaultbuffersize/) | पढ़ने और लिखने के ऑपरेशनों के दौरान बफ़र किए गए बाइट्स की संख्या का डिफ़ॉल्ट मान। |
| static [Null](../stream/null/) | कोई अंतर्निहित स्टोरेज नहीं वाला स्ट्रीम। |

## संबंधित देखें

* वर्ग [Stream](../stream/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)
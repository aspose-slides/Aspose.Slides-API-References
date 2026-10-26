---
title: AuthenticatedStream
second_title: "Aspose.Slides for C++ API संदर्भ"
description: "स्ट्रीम के पार प्रमाणपत्र पास करने के लिए विधियों को सम्मिलित करता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि यह रन-टाइम त्रुटियाँ और/या असेर्शन दोष का कारण बनेगा। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों में आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 1
url: /hi/system.net.security/authenticatedstream/
---
## AuthenticatedStream क्लास

स्ट्रीम के पार प्रमाणपत्र पास करने के लिए विधियों को सम्मिलित करता है। Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class AuthenticatedStream : public System::IO::Stream
```

## विधियां

| विधि | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस पढ़ने के ऑपरेशन को आरंभ करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस लिखने के ऑपरेशन को आरंभ करता है। |
| virtual void [Close](../../system.io/stream/close/)() | स्ट्रीम को बंद करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके, निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](../../system.io/stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस पढ़ने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस लिखने के ऑपरेशन को समाप्त करता है। निर्दिष्ट असिंक्रोनस लिखने के ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| virtual void [Flush](../../system.io/stream/flush/)() | इस स्ट्रीम के बफ़र्स को साफ़ करता है और सभी बफ़र्ड डेटा को मूल संग्रहण में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, बफ़र्ड डेटा को मूल डिवाइस में लिखता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, बफ़र्ड डेटा को मूल डिवाइस में लिखता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| virtual **bool** [get_CanRead](../../system.io/stream/get_canread/)() const | निर्धारित करता है कि स्ट्रीम पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_CanSeek](../../system.io/stream/get_canseek/)() const | निर्धारित करता है कि स्ट्रीम सीकिंग का समर्थन करती है या नहीं। |
| virtual **bool** [get_CanTimeout](../../system.io/stream/get_cantimeout/)() const | एक मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual **bool** [get_CanWrite](../../system.io/stream/get_canwrite/)() const | निर्धारित करता है कि स्ट्रीम लिखने योग्य है या नहीं। |
| virtual **bool** [get_IsAuthenticated](./get_isauthenticated/)() const | एक मान लौटाता है जो दर्शाता है कि प्रमाणीकरण सफलतापूर्वक पास हुआ है या नहीं। |
| virtual **bool** [get_IsEncrypted](./get_isencrypted/)() const | एक मान लौटाता है जो दर्शाता है कि इस स्ट्रीम का उपयोग करके भेजा गया डेटा एन्क्रिप्टेड है या नहीं। |
| virtual **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const | एक मान लौटाता है जो दर्शाता है कि सर्वर और क्लाइंट प्रमाणित हैं या नहीं। |
| virtual **bool** [get_IsServer](./get_isserver/)() const | एक मान लौटाता है जो दर्शाता है कि कनेक्शन की स्थानीय तरफ सर्वर है या नहीं। |
| virtual **bool** [get_IsSigned](./get_issigned/)() const | एक मान लौटाता है जो दर्शाता है कि इस स्ट्रीम का उपयोग करके भेजा गया डेटा साइन किया गया है या नहीं। |
| **bool** [get_LeaveInnerStreamOpen](./get_leaveinnerstreamopen/)() const | वर्तमान क्लास इंस्टेंस द्वारा डेटा भेजने और प्राप्त करने के लिए उपयोग की जाने वाली स्ट्रीम को लौटाता है। |
| virtual **int64_t** [get_Length](../../system.io/stream/get_length/)() const | स्ट्रीम की लंबाई को बाइट में लौटाता है। |
| virtual **int64_t** [get_Position](../../system.io/stream/get_position/)() const | स्ट्रीम की वर्तमान स्थिति को लौटाता है। |
| virtual int [get_ReadTimeout](../../system.io/stream/get_readtimeout/)() const | एक मान (मिलीसेकंड में) प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर पढ़ने का प्रयास करेगा। |
| virtual int [get_WriteTimeout](../../system.io/stream/get_writetimeout/)() const | एक मान (मिलीसेकंड में) प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले कितनी देर लिखने का प्रयास करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से सम्बंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स का हेशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लासेज़ की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है। |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट ऐरे में लिखता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक अनुक्रम पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिती को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक अनुक्रम पढ़ता है, पढ़े गए बाइट्स की संख्या से स्ट्रीम में स्थिती को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और पढ़े गए बाइट के समान 32-बिट पूर्णांक मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual **int64_t** [Seek](../../system.io/stream/seek/)(**int64_t**, [SeekOrigin](../../system.io/seekorigin/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_Position](../../system.io/stream/set_position/)(**int64_t**) | स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | एक मान (मिलीसेकंड में) सेट करता है जो निर्धारित करता है कि स्ट्रीम टाइम-आउट होने से पहले पढ़ने का प्रयास कितनी देर करेगा। |
| virtual void [SetLength](../../system.io/stream/setlength/)(**int64_t**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व की गई स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [Write](../../system.io/stream/write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-रेंज को स्ट्रीम में लिखता है। |
| virtual void [Write](../../system.io/stream/write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-रेंज को स्ट्रीम में लिखता है। |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट्स की उप-रेंज को स्ट्रीम में लिखता है। |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट बाइट्स की उप-रेंज को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम में असिंक्रोनस रूप से बाइट्स की एक अनुक्रम लिखता है, लिखे गए बाइट्स की संख्या से इस स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम में असिंक्रोनस रूप से बाइट्स की एक अनुक्रम लिखता है, लिखे गए बाइट्स की संख्या से इस स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्द करने के अनुरोधों की निगरानी करता है। |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | निर्दिष्ट अनसाइनड 8-बिट पूर्णांक मान को स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Null](../../system.io/stream/null/) | बिना मूल स्टोरेज के एक स्ट्रीम। |

## देखें

* क्लास [Stream](../../system.io/stream/)
* नेमस्पेस [System::Net::Security](../)
* लाइब्रेरी [Aspose.Slides](../../)
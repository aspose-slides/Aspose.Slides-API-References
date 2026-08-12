---
title: Stream
second_title: Aspose.Slides for C++ API रेफ़रेंस
description: "विविध स्ट्रीम इम्प्लीमेंटेशन के लिए एक बेस क्लास। इस क्लास के ऑब्जेक्ट को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्युमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 365
url: /hi/system.io/stream/
---
## Stream क्लास

एक बेस क्लास विभिन्न स्ट्रीम कार्यान्वयनों के लिए। इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या ऑपरेटर new का उपयोग करके न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्युमेंट के रूप में पास करने के लिए करें।

```cpp
class Stream : public System::IDisposable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस पढ़ने का ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस लिखने का ऑपरेशन शुरू करता है। |
| virtual void [Close](./close/)() | स्ट्रीम को बंद करता है। |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](./copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](./)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](./dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है और स्ट्रीम को बंद करता है। |
| virtual int [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस पढ़ने ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है। |
| virtual void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस लिखने ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस लिखने ऑपरेशन के समाप्त होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual void [Flush](./flush/)() | इस स्ट्रीम के बफ़र को साफ़ करता है और सभी बफ़र किए डेटा को अंतर्निहित स्टोरेज में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | इस स्ट्रीम के सभी बफ़र को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए डेटा को अंतर्निहित डिवाइस में लिखवाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](./flushasync/)() | इस स्ट्रीम के सभी बफ़र को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए डेटा को अंतर्निहित डिवाइस में लिखवाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual **bool** [get_CanRead](./get_canread/)() const | निर्धारित करता है कि स्ट्रीम पढ़ने योग्य है या नहीं। |
| virtual **bool** [get_CanSeek](./get_canseek/)() const | निर्धारित करता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| virtual **bool** [get_CanTimeout](./get_cantimeout/)() const | ऐसा मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual **bool** [get_CanWrite](./get_canwrite/)() const | निर्धारित करता है कि स्ट्रीम लिखने योग्य है या नहीं। |
| virtual **int64_t** [get_Length](./get_length/)() const | स्ट्रीम की लंबाई बाइट्स में लौटाता है। |
| virtual **int64_t** [get_Position](./get_position/)() const | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| virtual int [get_ReadTimeout](./get_readtimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम पढ़ने का प्रयास कितनी देर करेगा। |
| virtual int [get_WriteTimeout](./get_writetimeout/)() const | मिलीसेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम लिखने का प्रयास कितनी देर करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का तुल्य। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का तुल्य। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का तुल्य। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कन्स्ट्रक्शन सक्षम करता है। |
| virtual **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](./read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक श्रृंखला पढ़ता है, पढ़े गए बाइट्स की संख्या द्वारा स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](./readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से असिंक्रोनस रूप से बाइट्स की एक श्रृंखला पढ़ता है, पढ़े गए बाइट्स की संख्या द्वारा स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual int [ReadByte](./readbyte/)() | स्ट्रीम से एक एकल बाइट पढ़ता है और पढ़े गये बाइट के समान 32-बिट पूर्णांक मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual **int64_t** [Seek](./seek/)(**int64_t**, [SeekOrigin](../seekorigin/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_Position](./set_position/)(**int64_t**) | स्ट्रीम की स्थिति सेट करता है। |
| virtual void [set_ReadTimeout](./set_readtimeout/)(int) | ऐसा मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम टाइम-आउट हो सकता है या नहीं। |
| virtual void [set_WriteTimeout](./set_writetimeout/)(int) | मिलीसेकंड में वह मान सेट करता है जो निर्धारित करता है कि टाइम-आउट होने से पहले स्ट्रीम पढ़ने का प्रयास कितनी देर करेगा। |
| virtual void [SetLength](./setlength/)(**int64_t**) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का तुल्य। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज बाइट्स को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज बाइट्स को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से निर्दिष्ट उप-रेंज बाइट्स को स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से निर्दिष्ट उप-रेंज बाइट्स को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | असिंक्रोनस रूप से बाइट्स की एक श्रृंखला लिखता है, लिखे गए बाइट्स की संख्या द्वारा इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](./writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | असिंक्रोनस रूप से बाइट्स की एक श्रृंखला लिखता है, लिखे गए बाइट्स की संख्या द्वारा इस स्ट्रीम में वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual void [WriteByte](./writebyte/)(**uint8_t**) | निर्दिष्ट unsigned 8-bit इंटीजर मान को स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Null](./null/) | कोई अंतर्निहित स्टोरेज वाला एक स्ट्रीम। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के लिए साझा पॉइंटर का एक उपनाम। |
## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)
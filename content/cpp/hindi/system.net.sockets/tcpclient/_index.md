---
title: TcpClient
second_title: Aspose.Slides for C++ API संदर्भ
description: "TCP नेटवर्क सेवाओं के लिए एक क्लाइंट का प्रतिनिधित्व करता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शनों को तर्क के रूप में पास करने के लिए उपयोग करें।"
type: docs
weight: 66
url: /hi/system.net.sockets/tcpclient/
---
## TcpClient क्लास

TCP नेटवर्क सेवाओं के लिए एक क्लाइंट का प्रतिनिधित्व करता है। इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस कभी भी स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को तर्क के रूप में फ़ंक्शनों को पास करने के लिए उपयोग करें।

```cpp
class TcpClient : public System::IDisposable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | एक असिंक्रोनस कनेक्ट ऑपरेशन को प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | एक असिंक्रोनस कनेक्ट ऑपरेशन को प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | एक असिंक्रोनस कनेक्ट ऑपरेशन को प्रारंभ करता है। |
| void [Close](./close/)() | कनेक्शन को बंद करता है और वर्तमान इंस्टेंस को नष्ट करता है। |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | निर्दिष्ट रिमोट होस्ट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | निर्दिष्ट रिमोट होस्ट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | निर्दिष्ट रिमोट होस्ट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | निर्दिष्ट रिमोट होस्ट से कनेक्शन स्थापित करता है। |
| virtual void [Dispose](../../system/idisposable/dispose/)() | कुछ नहीं करता। |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | तब तक प्रतीक्षा करता है जब तक निर्दिष्ट असिंक्रोनस कनेक्ट ऑपरेशन पूरा नहीं हो जाता। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को दर्शाता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलनात्मक को दर्शाता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **int32_t** [get_Available](./get_available/)() | प्राप्त बाइट्स की संख्या लौटाता है जो पढ़ने के लिये तैयार हैं। |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | सॉकेट प्राप्त करता है। |
| **bool** [get_Connected](./get_connected/)() | एक मान लौटाता है जो दर्शाता है कि सॉकेट रिमोट होस्ट से जुड़ा है या नहीं। |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान इंस्टेंस एक पोर्ट को केवल एक क्लाइंट द्वारा उपयोग की अनुमति देता है या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | एक मान प्राप्त करता है जो दर्शाता है कि सॉकेट सभी पेंडिंग डेटा भेजने के प्रयास में बंद होने में देरी करेगा या नहीं। |
| **bool** [get_NoDelay](./get_nodelay/)() | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान इंस्टेंस Nagle एल्गोरिद्म का उपयोग कर रहा है या नहीं। |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | डेटा प्राप्त करने के लिए उपयोग किए जाने वाले बफ़र का आकार प्राप्त करता है। |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | एक मान प्राप्त करता है जो दर्शाता है कि डेटा प्राप्ति कब टाइमआउट होगी, यानी कितने समय बाद। |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | डेटा भेजने के लिये उपयोग किए जाने वाले बफ़र का आकार प्राप्त करता है। |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | एक मान प्राप्त करता है जो दर्शाता है कि डेटा भेजना कब टाइमआउट होगा, यानी कितने समय बाद। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | डेटा भेजने और प्राप्त करने के लिये उपयोग किए जाने वाले स्ट्रीम को लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित टाइप का इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट आरंभ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस-तुलना करता है वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिये विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिये विशिष्टीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | सॉकेट सेट करता है। |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि वर्तमान इंस्टेंस एक पोर्ट को केवल एक क्लाइंट द्वारा उपयोग की अनुमति देता है या नहीं। |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | एक मान सेट करता है जो दर्शाता है कि सॉकेट सभी पेंडिंग डेटा भेजने के प्रयास में बंद होने में देरी करेगा या नहीं। |
| void [set_NoDelay](./set_nodelay/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि वर्तमान इंस्टेंस Nagle एल्गोरिद्म का उपयोग कर रहा है या नहीं। |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | डेटा प्राप्त करने के लिये उपयोग किए जाने वाले बफ़र का आकार सेट करता है। |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | एक मान सेट करता है जो दर्शाता है कि डेटा प्राप्ति कब टाइमआउट होगी, यानी कितने समय बाद। |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | डेटा भेजने के लिये उपयोग किए जाने वाले बफ़र का आकार सेट करता है। |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | एक मान सेट करता है जो दर्शाता है कि डेटा भेजना कब टाइमआउट होगा, यानी कितने समय बाद। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | एक नया इंस्टेंस बनाता है। |
|  [TcpClient](./tcpclient/)() | एक नया इंस्टेंस बनाता है। |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | एक नया इंस्टेंस बनाता है। |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
| virtual  [~TcpClient](./~tcpclient/)() | वर्तमान इंस्टेंस को डिस्ट्रक्ट करता है। |
## देखें भी

* क्लास [IDisposable](../../system/idisposable/)
* नेमस्पेस [System::Net::Sockets](../)
* लाइब्रेरी [Aspose.Slides](../../)
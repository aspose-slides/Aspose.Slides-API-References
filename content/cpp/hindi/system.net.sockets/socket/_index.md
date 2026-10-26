---
title: Socket
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: Socket क्लास Berkeley सॉकेट्स इंटरफ़ेस को लागू करती है।
type: docs
weight: 53
url: /hi/system.net.sockets/socket/
---
## Socket वर्ग

[Socket](./) क्लास Berkeley sockets इंटरफ़ेस को लागू करता है।

```cpp
class Socket : public System::IDisposable
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](./)\> [Accept](./accept/)() | नई कनेक्शन के लिए नया सॉकेट बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस कनेक्ट ऑपरेशन प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस कनेक्ट ऑपरेशन प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस कनेक्ट ऑपरेशन प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस कनेक्ट ऑपरेशन प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginReceive](./beginreceive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस लिखने वाला ऑपरेशन प्रारंभ करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginSend](./beginsend/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | असिंक्रोनस भेजने वाला ऑपरेशन प्रारंभ करता है। |
| void [Bind](./bind/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | सॉकेट को निर्दिष्ट स्थानीय एन्डपॉइंट के साथ बाइंड करता है। |
| void [Close](./close/)() | सॉकेट कनेक्शन को बंद करता है। |
| void [Close](./close/)(int) | निर्दिष्ट टाइम-आउट के साथ सॉकेट कनेक्शन को बंद करता है ताकि कतारबद्ध डेटा भेजा जा सके। |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट रिमोट एन्डपॉइंट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | निर्दिष्ट रिमोट एन्डपॉइंट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | निर्दिष्ट रिमोट एन्डपॉइंट से कनेक्शन स्थापित करता है। |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | निर्दिष्ट रिमोट एन्डपॉइंट से कनेक्शन स्थापित करता है। |
| void [Dispose](./dispose/)() override | कुछ नहीं करता। |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस कनेक्ट ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस रिसीव ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| **int32_t** [EndReceive](./endreceive/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | निर्दिष्ट असिंक्रोनस रिसीव ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस सेंड ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| **int32_t** [EndSend](./endsend/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>, [SocketError](../socketerror/)\&) | निर्दिष्ट असिंक्रोनस सेंड ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स के साथ ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं है, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ़्लोटिंग-पॉइंट तुलना का अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिये। |
| [System::Net::Sockets::AddressFamily](../addressfamily/) [get_AddressFamily](./get_addressfamily/)() | पता परिवार लौटाता है। |
| **int32_t** [get_Available](./get_available/)() | नेटवर्क से प्राप्त बाइट्स की मात्रा लौटाता है जो पढ़ने हेतु उपलब्ध है। |
| **bool** [get_Blocking](./get_blocking/)() | यह दर्शाता है कि सॉकेट ब्लॉकिंग मोड में है या नहीं। |
| **bool** [get_Connected](./get_connected/)() | यह दर्शाता है कि सॉकेट रिमोट होस्ट से जुड़ा है या नहीं। |
| **bool** [get_DontFragment](./get_dontfragment/)() | यह दर्शाता है कि सॉकेट IP डेटाग्राम को फ्रैगमेंट करने की अनुमति देता है या नहीं। |
| **bool** [get_DualMode](./get_dualmode/)() | यह दर्शाता है कि सॉकेट ड्यूल-मोड में है या नहीं। |
| **bool** [get_EnableBroadcast](./get_enablebroadcast/)() | यह दर्शाता है कि सॉकेट ब्रॉडकास्ट पैकेट की अनुमति देता है या नहीं। |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | यह दर्शाता है कि केवल एक प्रक्रिया पोर्ट को बाइंड कर सकती है या नहीं। |
| **bool** [get_IsBound](./get_isbound/)() | यह दर्शाता है कि सॉकेट किसी विशिष्ट स्थानीय पोर्ट से बाइंड है या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | यह दर्शाता है कि सॉकेट सभी पेंडिंग डेटा भेजने के प्रयास में क्लोज़िंग को विलंबित करेगा या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_LocalEndPoint](./get_localendpoint/)() | स्थानीय एन्डपॉइंट लौटाता है। |
| **bool** [get_MulticastLoopback](./get_multicastloopback/)() | यह दर्शाता है कि सॉकेट आउटगोइंग मल्टिकास्ट पैकेट प्राप्त करता है या नहीं। |
| **bool** [get_NoDelay](./get_nodelay/)() | यह दर्शाता है कि सॉकेट Nagle एल्गोरिद्म उपयोग कर रहा है या नहीं। |
| static **bool** [get_OSSupportsIPv4](./get_ossupportsipv4/)() | यह दर्शाता है कि ऑपरेटिंग सिस्टम और नेटवर्क अडाप्टर IPv4 का समर्थन करते हैं या नहीं। |
| static **bool** [get_OSSupportsIPv6](./get_ossupportsipv6/)() | यह दर्शाता है कि ऑपरेटिंग सिस्टम और नेटवर्क अडाप्टर IPv6 का समर्थन करते हैं या नहीं। |
| [System::Net::Sockets::ProtocolType](../protocoltype/) [get_ProtocolType](./get_protocoltype/)() | प्रोटोकॉल प्रकार लौटाता है। |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | रिसीव बफ़र का आकार लौटाता है। |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | वह अवधि लौटाता है जिसके बाद ‘Receive’ कॉल टाइम-आउट हो जाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\> [get_RemoteEndPoint](./get_remoteendpoint/)() | रिमोट एन्डपॉइंट लौटाता है। |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | सेंड बफ़र का आकार लौटाता है। |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | वह अवधि लौटाता है जिसके बाद ‘Send’ कॉल टाइम-आउट हो जाता है। |
| [System::Net::Sockets::SocketType](../sockettype/) [get_SocketType](./get_sockettype/)() | सॉकेट प्रकार लौटाता है। |
| static **bool** [get_SupportsIPv4](./get_supportsipv4/)() | यह दर्शाता है कि वर्तमान होस्ट IPv4 का समर्थन करता है या नहीं। |
| **int16_t** [get_Ttl](./get_ttl/)() | TTL मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट की हैशिंग सक्षम करता है। |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | इम्प्लीमेंटेशन की पॉइंटर लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/)) | निर्दिष्ट विकल्प नाम से संबंधित मान लौटाता है। |
| void [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | निर्दिष्ट विकल्प नाम से संबंधित मान लौटाता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetSocketOption](./getsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | निर्दिष्ट विकल्प नाम से संबंधित मान लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप लौटाता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| **int32_t** [IOControl](./iocontrol/)(**int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | सॉकेट के निम्न-स्तरीय ऑपरेटिंग मोड सेट करता है। |
| **int32_t** [IOControl](./iocontrol/)([IOControlCode](../iocontrolcode/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | सॉकेट के निम्न-स्तरीय ऑपरेटिंग मोड सेट करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट लक्ष्य-टाइप द्वारा वर्णित इंस्टेंस है या नहीं। C# ‘is’ ऑपरेटर का समकक्ष। |
| void [Listen](./listen/)(**int32_t**) | सॉकेट की स्थिति को ‘listen’ में बदलता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कॉन्स्ट्रक्शन को सक्षम करता है। |
| **bool** [Poll](./poll/)(**int32_t**, [SelectMode](../selectmode/)) | निर्दिष्ट पोलिंग मोड के आधार पर सॉकेट की स्थिति लौटाता है। |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | सॉकेट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | सॉकेट से डेटा प्राप्त करता है और निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | सॉकेट से डेटा प्राप्त करता है और निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Receive](./receive/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | सॉकेट से डेटा प्राप्त करता है और निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एन्डपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एन्डपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एन्डपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एन्डपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एन्डपॉइंट से डेटा प्राप्त करता है और इसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveFrom](./receivefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [ReceiveMessageFrom](./receivemessagefrom/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>\&, [IPPacketInformation](../ippacketinformation/)\&) | निर्दिष्ट एंडपॉइंट से डेटा प्राप्त करता है और उसे निर्दिष्ट बाइट एरे में लिखता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और नलपॉइंट के मामले के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[ArraySegment](../../system/arraysegment/)\<**uint8_t**\>\>\>, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/)) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [Send](./send/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [SocketError](../socketerror/)\&) | निर्दिष्ट डेटा को सॉकेट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [SocketFlags](../socketflags/), [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::ArrayView\<**uint8_t**\>, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| **int32_t** [SendTo](./sendto/)(System::Details::StackArray\<**uint8_t**, N\>\&, [System::SharedPtr](../../system/sharedptr/)\<[EndPoint](../../system.net/endpoint/)\>) | निर्दिष्ट डेटा को निर्दिष्ट एंडपॉइंट पर भेजता है। |
| void [set_Blocking](./set_blocking/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट ब्लॉकिंग मोड में है या नहीं। |
| void [set_ConnectionTimeout](./set_connectiontimeout/)(**int32_t**) | कनेक्शन टाइमआउट सेट करता है। |
| void [set_DontFragment](./set_dontfragment/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट आईपी डेटाग्राम को फ्रैगमेंट करने की अनुमति देता है या नहीं। |
| void [set_DualMode](./set_dualmode/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट ड्यूल-मोड में है या नहीं। |
| void [set_EnableBroadcast](./set_enablebroadcast/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट ब्रॉडकास्ट पैकेट्स की अनुमति देता है या नहीं। |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि केवल एक प्रक्रिया सॉकेट को पोर्ट से बाइंड कर सकती है या नहीं। |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | एक मान सेट करता है जो दर्शाता है कि सॉकेट सभी पेंडिंग डेटा भेजने के प्रयत्न में बंद होने में देरी करेगा या नहीं। |
| void [set_MulticastLoopback](./set_multicastloopback/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट आउटगोइंग मल्टीकास्ट पैकेट्स प्राप्त करता है या नहीं। |
| void [set_NoDelay](./set_nodelay/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि सॉकेट नगेल एल्गोरिद्म उपयोग कर रहा है या नहीं। |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | रसीव बफ़र का आकार सेट करता है। |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | 'Receive' कॉल के टाइमआउट होने के बाद की अवधि सेट करता है। |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | सेंड बफ़र का आकार सेट करता है। |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | 'Send' कॉल के टाइमआउट होने के बाद की अवधि सेट करता है। |
| void [set_Ttl](./set_ttl/)(**int16_t**) | TTL मान सेट करता है। |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **int32_t**) | निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है। |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है। |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), **bool**) | निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है। |
| void [SetSocketOption](./setsocketoption/)([SocketOptionLevel](../socketoptionlevel/), [SocketOptionName](../socketoptionname/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | निर्दिष्ट सॉकेट विकल्प को निर्दिष्ट मान पर सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्गुमेंट को एक वीक पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [Shutdown](./shutdown/)([SocketShutdown](../socketshutdown/)) | सॉकेट के सेंड और रिसीव ऑपरेशन्स को निष्क्रिय करता है। |
|  [Socket](./socket/)([System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | एक नया इंस्टेंस बनाता है। |
|  [Socket](./socket/)([System::Net::Sockets::AddressFamily](../addressfamily/), [System::Net::Sockets::SocketType](../sockettype/), [System::Net::Sockets::ProtocolType](../protocoltype/)) | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानुपाती। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
| virtual  [~Socket](./~socket/)() | वर्तमान इंस्टेंस को डीस्ट्रक्ट करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [ImplPtr](./implptr/) | सॉकेट इम्प्लीमेंटेशन। |
## देखें भी

* क्लास [IDisposable](../../system/idisposable/)
* नेमस्पेस [System::Net::Sockets](../)
* लाइब्रेरी [Aspose.Slides](../../)
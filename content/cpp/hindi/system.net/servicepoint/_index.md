---
title: ServicePoint
second_title: Aspose.Slides for C++ API संदर्भ
description: "HTTP कनेक्शन प्रबंधन प्रदान करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग तर्क के रूप में फ़ंक्शनों को पास करने के लिए करें।"
type: docs
weight: 417
url: /hi/system.net/servicepoint/
---
## ServicePoint क्लास


HTTP कनेक्शन प्रबंधन प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरण को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को तर्क के रूप में फ़ंक्शन में पास करें।

```cpp
class ServicePoint : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| **bool** [CloseConnectionGroup](./closeconnectiongroup/)([String](../../system/string/)) | निर्दिष्ट कनेक्शन समूह से संबंधित कनेक्शनों को बंद करता है और हटाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अभिप्राय का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, यद्यपि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | वर्तमान उदाहरण जिस सर्वर URI से जुड़ता है, उसे वापस करता है। |
| [BindIPEndPoint](../bindipendpoint/) [get_BindIPEndPointDelegate](./get_bindipendpointdelegate/)() | वर्तमान उदाहरण के साथ स्थानीय [IPEndPoint](../ipendpoint/) को सम्बद्ध करने के लिए उपयोग किया जाने वाला delegate प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_Certificate](./get_certificate/)() | वर्तमान उदाहरण द्वारा उपयोग किया जाने वाला प्रमाणपत्र वापस करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_ClientCertificate](./get_clientcertificate/)() | आखिरी क्लाइंट प्रमाणपत्र को वापस करता है। |
| **int32_t** [get_ConnectionLeaseTimeout](./get_connectionleasetimeout/)() | सक्रिय [ServicePoint](./) बंद हो जाएगा, इसके बाद मिलीसेकंड में एक टाइमआउट प्राप्त करता है। |
| **int32_t** [get_ConnectionLimit](./get_connectionlimit/)() | वर्तमान उदाहरण द्वारा अनुमत अधिकतम कनेक्शन संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_ConnectionName](./get_connectionname/)() | कनेक्शन का नाम वापस करता है। |
| **int32_t** [get_CurrentConnections](./get_currentconnections/)() | खुले हुए कनेक्शनों की संख्या वापस करता है। |
| **bool** [get_Expect100Continue](./get_expect100continue/)() | एक मान प्राप्त करता है जो संकेत करता है कि 100-Continue व्यवहार उपयोग किया गया है या नहीं। |
| [DateTime](../../system/datetime/) [get_IdleSince](./get_idlesince/)() | होस्ट से नवीनतम कनेक्शन की तिथि और समय वापस करता है। |
| **int32_t** [get_MaxIdleTime](./get_maxidletime/)() | एक अवधि (मिलीसेकंड में) प्राप्त करता है, जिसके बाद निष्क्रिय कनेक्शन बंद हो जाएगा। |
| virtual [Version](../../system/version/) [get_ProtocolVersion](./get_protocolversion/)() | HTTP संस्करण को वापस करता है। |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | प्राप्त बफ़र का आकार प्राप्त करता है। |
| **bool** [get_SupportsPipelining](./get_supportspipelining/)() | एक मान वापस करता है जो दर्शाता है कि वर्तमान उदाहरण पाइपलाइन कनेक्शन को समर्थन देता है या नहीं। |
| **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | एक मान प्राप्त करता है जो दर्शाता है कि वर्तमान उदाहरण द्वारा प्रबंधित कनेक्शनों में Nagle एल्गोरिद्म उपयोग किया गया है या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से संबंधित रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। इसे सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और उपवर्गों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के मामले के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के मामले के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_BindIPEndPointDelegate](./set_bindipendpointdelegate/)([BindIPEndPoint](../bindipendpoint/)) | स्थानीय [IPEndPoint](../ipendpoint/) को वर्तमान उदाहरण से सम्बद्ध करने के लिए उपयोग किए जाने वाले delegate को सेट करता है। |
| void [set_ConnectionLeaseTimeout](./set_connectionleasetimeout/)(**int32_t**) | एक टाइमआउट (मिलीसेकंड में) सेट करता है, जिसके बाद सक्रिय [ServicePoint](./) बंद हो जाएगा। |
| void [set_ConnectionLimit](./set_connectionlimit/)(**int32_t**) | वर्तमान उदाहरण द्वारा अनुमत अधिकतम कनेक्शन संख्या सेट करता है। |
| void [set_Expect100Continue](./set_expect100continue/)(**bool**) | एक मान सेट करता है जो संकेत करता है कि 100-Continue व्यवहार उपयोग किया गया है या नहीं। |
| void [set_MaxIdleTime](./set_maxidletime/)(**int32_t**) | एक अवधि (मिलीसेकंड में) सेट करता है, जिसके बाद निष्क्रिय कनेक्शन बंद हो जाएगा। |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | प्राप्त बफ़र का आकार सेट करता है। |
| void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि वर्तमान उदाहरण द्वारा प्रबंधित कनेक्शनों में Nagle एल्गोरिद्म उपयोग किया गया है या नहीं। |
| void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' विकल्प सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और वापस करता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम वस्तुओं को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। इसे सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीनी वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## संबंधित देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
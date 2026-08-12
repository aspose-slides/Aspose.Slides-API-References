---
title: SoapHttpClientProtocol
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "जब SOAP का उपयोग किया जाता है, तो क्लाइंट प्रॉक्सी सेवाओं को इस क्लास को विरासत में लेना चाहिए। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियां और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 118
url: /hi/system.web.services.protocols/soaphttpclientprotocol/
---
## SoapHttpClientProtocol क्लास


The client proxy services must inherit this class when the SOAP is used. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class SoapHttpClientProtocol : public System::Web::Services::Protocols::HttpWebClientProtocol
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual void [Abort](../webclientprotocol/abort/)() | Cancels the request. |
| virtual void [CheckForCookies](../httpwebclientprotocol/checkforcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Net::HttpWebResponse](../../system.net/httpwebresponse/)\>) | Appends cookies from the specified request to the internal cookie container. |
| void [Discover](./discover/)() | Binds the current instance to the XML [Web](../../system.web/) service. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, यहाँ तक कि NaN से भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, यहाँ तक कि NaN से भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **bool** [get_AllowAutoRedirect](../httpwebclientprotocol/get_allowautoredirect/)() | क्लाइंट द्वारा सर्वर रिडायरेक्ट्स का पालन किया जाता है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](../httpwebclientprotocol/get_clientcertificates/)() | क्लाइंट प्रमाणपत्रों का संग्रह प्राप्त करता है। |
| [String](../../system/string/) [get_ConnectionGroupName](../webclientprotocol/get_connectiongroupname/)() | कनेक्शन समूह का नाम प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\> [get_CookieContainer](../httpwebclientprotocol/get_cookiecontainer/)() | कुकीज़ को संग्रहीत करने के लिए उपयोग किया जाने वाला कंटेनर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](../webclientprotocol/get_credentials/)() | प्रमाणीकरण जानकारी प्राप्त करता है। |
| **bool** [get_EnableDecompression](../httpwebclientprotocol/get_enabledecompression/)() | डिकम्प्रेशन सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| **bool** [get_PreAuthenticate](../webclientprotocol/get_preauthenticate/)() | प्री-ऑथेंटिकेशन सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\> [get_Proxy](../httpwebclientprotocol/get_proxy/)() | प्रॉक्सी जानकारी प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](../webclientprotocol/get_requestencoding/)() | क्लाइंट अनुरोध बनाने में प्रयुक्त एन्कोडिंग प्राप्त करता है। |
| [SoapProtocolVersion](../soapprotocolversion/) [get_SoapVersion](./get_soapversion/)() | SOAP संस्करण प्राप्त करता है। |
| **int32_t** [get_Timeout](../webclientprotocol/get_timeout/)() | अनुरोध के टाइम-आउट से पहले प्रतीक्षा करने के समयावधि को प्राप्त करता है। |
| **bool** [get_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/get_unsafeauthenticatedconnectionsharing/)() | जब क्लाइंट NTLM ऑथेंटिकेशन उपयोग करता है तो कनेक्शन शेयरिंग सक्षम है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](../webclientprotocol/get_uri/)() | XML [Web](../../system.web/) सेवा URI प्राप्त करता है। |
| [String](../../system/string/) [get_Url](../webclientprotocol/get_url/)() | XML [Web](../../system.web/) सेवा URL प्राप्त करता है। |
| **bool** [get_UseDefaultCredentials](../webclientprotocol/get_usedefaultcredentials/)() | 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| [String](../../system/string/) [get_UserAgent](../httpwebclientprotocol/get_useragent/)() | ‘User-Agent’ हेडर का मान प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान। |
| void [InitializeSerializers](./initializeserializers/)(const [System::TypeInfo](../../system/typeinfo/)\&, [System::SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerImplementation](../../system.xml.serialization/xmlserializerimplementation/)\>, [String](../../system/string/)) | आंतरिक फ़ील्ड को प्रारम्भ करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस दर्शाता है। C# 'is' ऑपरेटर का समान। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारम्भ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, बस नया ऑब्जेक्ट प्रारम्भ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशिष्ट रूप। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशिष्ट रूप। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AllowAutoRedirect](../httpwebclientprotocol/set_allowautoredirect/)(**bool**) | क्लाइंट द्वारा सर्वर रिडायरेक्ट्स का पालन किया जाता है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [set_ConnectionGroupName](../webclientprotocol/set_connectiongroupname/)([String](../../system/string/)) | कनेक्शन समूह का नाम सेट करता है। |
| void [set_CookieContainer](../httpwebclientprotocol/set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../../system.net/cookiecontainer/)\>) | कुकीज़ को स्टोर करने के लिए उपयोग किया जाने वाला कंटेनर सेट करता है। |
| void [set_Credentials](../webclientprotocol/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | प्रमाणीकरण जानकारी सेट करता है। |
| void [set_EnableDecompression](../httpwebclientprotocol/set_enabledecompression/)(**bool**) | डिकम्प्रेशन सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [set_PreAuthenticate](../webclientprotocol/set_preauthenticate/)(**bool**) | प्री-ऑथेंटिकेशन सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [set_Proxy](../httpwebclientprotocol/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[Net::IWebProxy](../../system.net/iwebproxy/)\>) | प्रॉक्सी जानकारी सेट करता है। |
| void [set_RequestEncoding](../webclientprotocol/set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | क्लाइंट अनुरोध बनाने में प्रयुक्त एन्कोडिंग सेट करता है। |
| void [set_SoapVersion](./set_soapversion/)([SoapProtocolVersion](../soapprotocolversion/)) | SOAP संस्करण सेट करता है। |
| void [set_Timeout](../webclientprotocol/set_timeout/)(**int32_t**) | अनुरोध के टाइम-आउट से पहले प्रतीक्षा करने का समयावधि सेट करता है। |
| void [set_UnsafeAuthenticatedConnectionSharing](../httpwebclientprotocol/set_unsafeauthenticatedconnectionsharing/)(**bool**) | जब क्लाइंट NTLM ऑथेंटिकेशन उपयोग करता है तो कनेक्शन शेयरिंग सक्षम है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [set_Uri](../webclientprotocol/set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | XML [Web](../../system.web/) सेवा URI सेट करता है। |
| void [set_Url](../webclientprotocol/set_url/)([String](../../system/string/)) | XML [Web](../../system.web/) सेवा URL सेट करता है। |
| void [set_UseDefaultCredentials](../webclientprotocol/set_usedefaultcredentials/)(**bool**) | 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| void [set_UserAgent](../httpwebclientprotocol/set_useragent/)([String](../../system/string/)) | ‘User-Agent’ हेडर का मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-th टेम्प्लेट आर्ग्युमेंट को वैक पॉइंटर (शेयर किए गए के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वैक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [SoapHttpClientProtocol](./soaphttpclientprotocol/)() | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [UnregisterMapping](../httpwebclientprotocol/unregistermapping/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) |  |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## संबंधित देखें

* क्लास [HttpWebClientProtocol](../httpwebclientprotocol/)
* नामस्थान [System::Web::Services::Protocols](../)
* लाइब्रेरी [Aspose.Slides](../../)
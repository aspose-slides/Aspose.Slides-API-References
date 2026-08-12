---
title: SslStream
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक स्ट्रीम जो SSL प्रोटोकॉल का उपयोग करके सर्वर को प्रमाणित करता है और वैकल्पिक रूप से क्लाइंट को भी प्रमाणित करता है।
type: docs
weight: 14
url: /hi/system.net.security/sslstream/
---
## SslStream क्लास

एक स्ट्रीम जो SSL प्रोटोकॉल का उपयोग करके सर्वर को प्रमाणित करता है और वैकल्पिक रूप से क्लाइंट को भी प्रमाणित करता है।

```cpp
class SslStream : public System::Net::Security::AuthenticatedStream
```
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/)) | कनेक्शन की क्लाइंट-साइड को प्रमाणित करता है। |
| virtual void [AuthenticateAsClient](./authenticateasclient/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>, [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/), **bool**) | कनेक्शन की क्लाइंट-साइड को प्रमाणित करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginRead](./beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एक असिंक्रोनस रीड ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginRead](../../system.io/stream/beginread/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस रीड ऑपरेशन शुरू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](./beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | एक असिंक्रोनस राइट ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\> [BeginWrite](../../system.io/stream/beginwrite/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [System::AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | एक असिंक्रोनस राइट ऑपरेशन शुरू करता है। |
| void [Close](./close/)() override | स्ट्रीम को बंद करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [CopyTo](../../system.io/stream/copyto/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../../system.io/stream/)\>\&, **int32_t**) | निर्दिष्ट बफ़र आकार का उपयोग करके निर्दिष्ट स्ट्रीम में बाइट्स कॉपी करता है। |
| void [Dispose](./dispose/)(**bool**) override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है और स्ट्रीम को बंद करता है। |
| void [Dispose](../../system.io/stream/dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है और स्ट्रीम को बंद करता है। |
| **int32_t** [EndRead](./endread/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual int [EndRead](../../system.io/stream/endread/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | निर्दिष्ट असिंक्रोनस रीड ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| void [EndWrite](./endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | एक असिंक्रोनस राइट ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस राइट ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual void [EndWrite](../../system.io/stream/endwrite/)([System::SharedPtr](../../system/sharedptr/)\<[System::IAsyncResult](../../system/iasyncresult/)\>) | एक असिंक्रोनस राइट ऑपरेशन समाप्त करता है। निर्दिष्ट असिंक्रोनस राइट ऑपरेशन के पूरा होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ़्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| void [Flush](./flush/)() override | इस स्ट्रीम के बफ़र्स साफ़ करता है और सभी बफ़र किए गए डेटा को आधारभूत संग्रहण में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)(const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए गए डेटा को आधारभूत डिवाइस में लिखने का कारण बनाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [FlushAsync](../../system.io/stream/flushasync/)() | इस स्ट्रीम के सभी बफ़र्स को असिंक्रोनस रूप से साफ़ करता है, किसी भी बफ़र किए गए डेटा को आधारभूत डिवाइस में लिखने का कारण बनाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| **bool** [get_CanRead](./get_canread/)() const override | निर्धारित करता है कि स्ट्रीम पठनीय है या नहीं। |
| **bool** [get_CanSeek](./get_canseek/)() const override | निर्धारित करता है कि स्ट्रीम सीकिंग का समर्थन करता है या नहीं। |
| **bool** [get_CanTimeout](./get_cantimeout/)() const override | एक मान प्राप्त करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम का टाइमआउट हो सकता है या नहीं। |
| **bool** [get_CanWrite](./get_canwrite/)() const override | निर्धारित करता है कि स्ट्रीम लिखने योग्य है या नहीं। |
| virtual **bool** [get_CheckCertRevocationStatus](./get_checkcertrevocationstatus/)() | एक मान लौटाता है जो दर्शाता है कि प्रमाणपत्र रिवोकेशन सूची प्रमाणपत्र वैधता प्रक्रिया के दौरान जांची जाती है या नहीं। |
| virtual [System::Security::Authentication::CipherAlgorithmType](../../system.security.authentication/cipheralgorithmtype/) [get_CipherAlgorithm](./get_cipheralgorithm/)() | एन्क्रिप्शन एल्गोरिद्म लौटाता है। |
| virtual **int32_t** [get_CipherStrength](./get_cipherstrength/)() | उपयोग किए गए एन्क्रिप्शन एल्गोरिद्म की शक्ति लौटाता है। |
| virtual [System::Security::Authentication::HashAlgorithmType](../../system.security.authentication/hashalgorithmtype/) [get_HashAlgorithm](./get_hashalgorithm/)() | हैश एल्गोरिद्म लौटाता है। |
| virtual **int32_t** [get_HashStrength](./get_hashstrength/)() | उपयोग किए गए हैश एल्गोरिद्म की शक्ति लौटाता है। |
| **bool** [get_IsAuthenticated](./get_isauthenticated/)() const override | एक मान लौटाता है जो दर्शाता है कि प्रमाणीकरण सफलतापूर्वक पारित हुआ है या नहीं। |
| **bool** [get_IsEncrypted](./get_isencrypted/)() const override | एक मान लौटाता है जो दर्शाता है कि इस स्ट्रीम का उपयोग करके भेजा गया डेटा एन्क्रिप्टेड है या नहीं। |
| **bool** [get_IsMutuallyAuthenticated](./get_ismutuallyauthenticated/)() const override | एक मान लौटाता है जो दर्शाता है कि सर्वर और क्लाइंट दोनों प्रमाणित हैं या नहीं। |
| **bool** [get_IsServer](./get_isserver/)() const override | एक मान लौटाता है जो दर्शाता है कि कनेक्शन की स्थानीय साइड सर्वर है या नहीं। |
| **bool** [get_IsSigned](./get_issigned/)() const override | एक मान लौटाता है जो दर्शाता है कि इस स्ट्रीम का उपयोग करके भेजा गया डेटा साइन किया गया है या नहीं। |
| virtual **int32_t** [get_KeyExchangeStrength](./get_keyexchangestrength/)() | उपयोग किए गए की एक्सचेंज एल्गोरिद्म की शक्ति लौटाता है। |
| **bool** [get_LeaveInnerStreamOpen](../authenticatedstream/get_leaveinnerstreamopen/)() const | वर्तमान क्लास इंस्टेंस द्वारा डेटा भेजने और प्राप्त करने के लिए उपयोग की जाने वाली स्ट्रीम लौटाता है। |
| **int64_t** [get_Length](./get_length/)() const override | स्ट्रीम की लंबाई बाइट्स में लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_LocalCertificate](./get_localcertificate/)() | स्थानीय एन्डपॉइंट को प्रमाणित करने के लिए उपयोग किया जाने वाला प्रमाणपत्र लौटाता है। |
| **int64_t** [get_Position](./get_position/)() const override | स्ट्रीम की वर्तमान स्थिति लौटाता है। |
| **int32_t** [get_ReadTimeout](./get_readtimeout/)() const override | मिलीसेकंड में एक मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम पढ़ने का प्रयास करने से पहले कितना समय प्रतीक्षा करेगा। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509Certificate](../../system.security.cryptography.x509certificates/x509certificate/)\> [get_RemoteCertificate](./get_remotecertificate/)() | रिमोट एन्डपॉइंट को प्रमाणित करने के लिए उपयोग किया जाने वाला प्रमाणपत्र लौटाता है। |
| virtual [System::Security::Authentication::SslProtocols](../../system.security.authentication/sslprotocols/) [get_SslProtocol](./get_sslprotocol/)() | SSL प्रोटोकॉल लौटाता है। |
| **int32_t** [get_WriteTimeout](./get_writetimeout/)() const override | मिलीसेकंड में एक मान प्राप्त करता है जो निर्धारित करता है कि स्ट्रीम लिखने का प्रयास करने से पहले कितना समय प्रतीक्षा करेगा। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनालॉग। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांच करता है कि ऑब्जेक्ट लक्ष्यटाइप द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनालॉग। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेन्ट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनालॉग। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। कुछ भी कॉपी नहीं करता, वास्तव में, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ भी कॉपी नहीं करता, वास्तव में, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सब-क्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **int32_t** [Read](./read/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](./read/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| **int32_t** [Read](../../system.io/stream/read/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट एरे में लिखता है। |
| virtual **int32_t** [Read](../../system.io/stream/read/)(const [System::Span](../../system/span/)\<**uint8_t**\>\&) | स्ट्रीम से निर्दिष्ट संख्या में बाइट्स पढ़ता है और उन्हें निर्दिष्ट बाइट स्पैन में लिखता है। |
| virtual [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [RTaskPtr](../../system/rtaskptr/)\<**int32_t**\> [ReadAsync](../../system.io/stream/readasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम से बाइट्स की एक श्रृंखला असिंक्रोनस रूप से पढ़ता है, पढ़े गए बाइट्स की संख्या के अनुसार स्ट्रीम में स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual int [ReadByte](../../system.io/stream/readbyte/)() | स्ट्रीम से एक बाइट पढ़ता है और पढ़े गए बाइट के मान के बराबर 32-बिट इंटीजर मान लौटाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नल पॉइंटर के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int64_t** [Seek](./seek/)(**int64_t**, [IO::SeekOrigin](../../system.io/seekorigin/)) override | स्ट्रीम की स्थिति को वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्वित स्थिति पर सेट करता है। |
| void [set_Position](./set_position/)(**int64_t**) override | स्ट्रीम की स्थिति सेट करता है। |
| void [set_ReadTimeout](./set_readtimeout/)(**int32_t**) override | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम का टाइमआउट हो सकता है या नहीं। |
| virtual void [set_ReadTimeout](../../system.io/stream/set_readtimeout/)(int) | एक मान सेट करता है जो निर्धारित करता है कि वर्तमान स्ट्रीम का टाइमआउट हो सकता है या नहीं। |
| void [set_WriteTimeout](./set_writetimeout/)(**int32_t**) override | मिलीसेकंड में एक मान सेट करता है जो निर्धारित करता है कि स्ट्रीम पढ़ने का प्रयास करने से पहले कितना समय प्रतीक्षा करेगा। |
| virtual void [set_WriteTimeout](../../system.io/stream/set_writetimeout/)(int) | मिलीसेकंड में एक मान सेट करता है जो निर्धारित करता है कि स्ट्रीम पढ़ने का प्रयास करने से पहले कितना समय प्रतीक्षा करेगा। |
| void [SetLength](./setlength/)(**int64_t**) override | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्वित स्ट्रीम की लंबाई सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को शयर पॉइंटर के बजाय एक weak पॉइंटर सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंट का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | एक नया इंस्टेंस बनाता है। |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**) | एक नया इंस्टेंस बनाता है। |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/)) | एक नया इंस्टेंस बनाता है। |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/)) | एक नया इंस्टेंस बनाता है। |
|  [SslStream](./sslstream/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../localcertificateselectioncallback/), [EncryptionPolicy](../encryptionpolicy/)) | एक नया इंस्टेंस बनाता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनालॉग। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेन्ट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट एरे को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से बाइट्स की निर्दिष्ट उप-सीमा को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&) | निर्दिष्ट बाइट एरे को स्ट्रीम में लिखता है। |
| void [Write](./write/)(const System::Details::ArrayView\<**uint8_t**\>\&, **int32_t**, **int32_t**) override | निर्दिष्ट बाइट एरे से बाइट्स की निर्दिष्ट उप-सीमा को स्ट्रीम में लिखता है। |
| void [Write](../../system.io/stream/write/)(const System::Details::StackArray\<**uint8_t**, N\>\&, **int32_t**, **int32_t**) | निर्दिष्ट बाइट एरे से बाइट्स की निर्दिष्ट उप-सीमा को स्ट्रीम में लिखता है। |
| virtual void [Write](../../system.io/stream/write/)(const [System::ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | निर्दिष्ट बाइट स्पैन से बाइट्स की निर्दिष्ट उप-सीमा को स्ट्रीम में लिखता है। |
| virtual [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**, const [Threading::CancellationToken](../../system.threading/cancellationtoken/)\&) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला असिंक्रोनस रूप से लिखता है, इस स्ट्रीम में लिखे गए बाइट्स की संख्या के अनुसार वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| [TaskPtr](../../system/taskptr/) [WriteAsync](../../system.io/stream/writeasync/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | वर्तमान स्ट्रीम में बाइट्स की एक श्रृंखला असिंक्रोनस रूप से लिखता है, इस स्ट्रीम में लिखे गए बाइट्स की संख्या के अनुसार वर्तमान स्थिति को आगे बढ़ाता है, और रद्दीकरण अनुरोधों की निगरानी करता है। |
| virtual void [WriteByte](../../system.io/stream/writebyte/)(**uint8_t**) | निर्दिष्ट unsigned 8-बिट इंटीजर मान को स्ट्रीम में लिखता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [Null](../../system.io/stream/null/) | कोई आधारभूत स्टोरज न होने वाली स्ट्रीम। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [AsyncResultType](./asyncresulttype/) | AsyncResultType का प्रकार। |
| [StreamImplementationPtr](./streamimplementationptr/) | इम्प्लीमेंटेशन की पॉइंटर का प्रकार। |
## संबंधित देखें

* क्लास [AuthenticatedStream](../authenticatedstream/)
* नेमस्पेस [System::Net::Security](../)
* लाइब्रेरी [Aspose.Slides](../../)
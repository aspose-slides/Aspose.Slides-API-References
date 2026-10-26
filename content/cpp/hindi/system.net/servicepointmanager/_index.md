---
title: ServicePointManager
second_title: Aspose.Slides for C++ API संदर्भ
description: "ServicePoint क्लास इंस्टैंसेज़ के जीवनचक्र चरणों (बनाना, बनाए रखना, और हटाना) को प्रबंधित करता है। इस क्लास के ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शनFaults हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।"
type: docs
weight: 430
url: /hi/system.net/servicepointmanager/
---
## ServicePointManager क्लास

[ServicePoint](../servicepoint/) क्लास इंस्टैंसेज़ के जीवनचक्र चरणों (निर्माण, रखरखाव, और हटाना) को प्रबंधित करता है। इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टैंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन दोषों का कारण बन सकता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शनों में तर्क के रूप में पास करें।

```cpp
class ServicePointManager : public System::Object
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैन्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# शैली की फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| static [System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\> [get_CertificatePolicy](./get_certificatepolicy/)() | एक प्रमाणपत्र नीति प्राप्त करता है। |
| static **bool** [get_CheckCertificateRevocationList](./get_checkcertificaterevocationlist/)() | एक मान प्राप्त करता है जो दर्शाता है कि प्रमाणपत्र को प्रमाणपत्र प्राधिकारी रिवोक्शन सूची के खिलाफ जाँचना चाहिए या नहीं। |
| static **int32_t** [get_DefaultConnectionLimit](./get_defaultconnectionlimit/)() | ServicePoint-क्लास इंस्टैंसेज़ द्वारा अनुमति प्राप्त अधिकतम समानांतर कनेक्शन संख्या प्राप्त करता है। |
| static **int32_t** [get_DnsRefreshTimeout](./get_dnsrefreshtimeout/)() | एक टाइमआउट मिलीसेकंड में प्राप्त करता है जिसके दौरान DNS रिज़ॉल्यूशन वैध माना जाता है। |
| static **bool** [get_EnableDnsRoundRobin](./get_enablednsroundrobin/)() | एक मान प्राप्त करता है जो दर्शाता है कि DNS रिज़ॉल्यूशन लागू IP पतों में घुमाव करता है या नहीं। |
| static [System::Net::Security::EncryptionPolicy](../../system.net.security/encryptionpolicy/) [get_EncryptionPolicy](./get_encryptionpolicy/)() | वर्तमान इंस्टैंस द्वारा उपयोग की जाने वाली एन्क्रिप्शन नीति लौटाता है। |
| static **bool** [get_Expect100Continue](./get_expect100continue/)() | एक मान प्राप्त करता है जो दर्शाता है कि ServicePoint-क्लास इंस्टैंसेज़ 100-Continue व्यवहार का उपयोग करती हैं या नहीं। |
| static **int32_t** [get_MaxServicePointIdleTime](./get_maxservicepointidletime/)() | ServicePoint-क्लास इंस्टैंसेज़ का अधिकतम निष्क्रिय समय प्राप्त करता है। |
| static **int32_t** [get_MaxServicePoints](./get_maxservicepoints/)() | वर्तमान इंस्टैंस द्वारा प्रबंधित किए जा सकने वाले ServicePoint-क्लास इंस्टैंसेज़ की अधिकतम संख्या प्राप्त करता है। |
| static **bool** [get_ReusePort](./get_reuseport/)() | एक मान प्राप्त करता है जो दर्शाता है कि आउटपुट कनेक्शन सॉकेट्स 'SO_REUSE_UNICASTPORT' विकल्प का उपयोग करते हैं या नहीं। |
| static [SecurityProtocolType](../securityprotocoltype/) [get_SecurityProtocol](./get_securityprotocol/)() | वर्तमान इंस्टैंस द्वारा प्रबंधित ServicePoint-क्लास इंस्टैंसेज़ द्वारा उपयोग किए जाने वाले सुरक्षा प्रोटोकॉल प्रकार को प्राप्त करता है। |
| static [Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/) [get_ServerCertificateValidationCallback](./get_servercertificatevalidationcallback/)() | एक कॉलबैक प्राप्त करता है जो सर्वर प्रमाणपत्र की वैधता के लिए उपयोग किया जाता है। |
| static **bool** [get_UseNagleAlgorithm](./get_usenaglealgorithm/)() | एक मान प्राप्त करता है जो दर्शाता है कि ServicePoint-क्लास इंस्टैंसेज़ Nagle एल्गोरिदम का उपयोग करती हैं या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काऊंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हॅशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के इंस्टैंस का प्रतिनिधित्व करता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रिफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामले के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स मामले के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| static void [set_CertificatePolicy](./set_certificatepolicy/)([System::SharedPtr](../../system/sharedptr/)\<ICertificatePolicy\>) | एक प्रमाणपत्र नीति सेट करता है। |
| static void [set_CheckCertificateRevocationList](./set_checkcertificaterevocationlist/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि प्रमाणपत्र को प्रमाणपत्र प्राधिकारी रिवोक्शन सूची के खिलाफ जाँचना चाहिए या नहीं। |
| static void [set_DefaultConnectionLimit](./set_defaultconnectionlimit/)(**int32_t**) | ServicePoint-क्लास इंस्टैंसेज़ द्वारा अनुमति प्राप्त अधिकतम समानांतर कनेक्शन संख्या सेट करता है। |
| static void [set_DnsRefreshTimeout](./set_dnsrefreshtimeout/)(**int32_t**) | एक टाइमआउट मिलीसेकंड में सेट करता है जिसके दौरान DNS रिज़ॉल्यूशन वैध माना जाता है। |
| static void [set_EnableDnsRoundRobin](./set_enablednsroundrobin/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि DNS रिज़ॉल्यूशन लागू IP पतों में घुमाव करता है या नहीं। |
| static void [set_Expect100Continue](./set_expect100continue/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि ServicePoint-क्लास इंस्टैंसेज़ 100-Continue व्यवहार का उपयोग करती हैं या नहीं। |
| static void [set_MaxServicePointIdleTime](./set_maxservicepointidletime/)(**int32_t**) | ServicePoint-क्लास इंस्टैंसेज़ का अधिकतम निष्क्रिय समय सेट करता है। |
| static void [set_MaxServicePoints](./set_maxservicepoints/)(**int32_t**) | वर्तमान इंस्टैंस द्वारा प्रबंधित किए जा सकने वाले ServicePoint-क्लास इंस्टैंसेज़ की अधिकतम संख्या सेट करता है। |
| static void [set_ReusePort](./set_reuseport/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि आउटपुट कनेक्शन सॉकेट्स 'SO_REUSE_UNICASTPORT' विकल्प का उपयोग करते हैं या नहीं। |
| static void [set_SecurityProtocol](./set_securityprotocol/)([SecurityProtocolType](../securityprotocoltype/)) | वर्तमान इंस्टैंस द्वारा प्रबंधित ServicePoint-क्लास इंस्टैंसेज़ द्वारा उपयोग किए जाने वाले सुरक्षा प्रोटोकॉल प्रकार को सेट करता है। |
| static void [set_ServerCertificateValidationCallback](./set_servercertificatevalidationcallback/)([Security::RemoteCertificateValidationCallback](../../system.net.security/remotecertificatevalidationcallback/)) | एक कॉलबैक सेट करता है जो सर्वर प्रमाणपत्र की वैधता के लिए उपयोग किया जाता है। |
| static void [set_UseNagleAlgorithm](./set_usenaglealgorithm/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि ServicePoint-क्लास इंस्टैंसेज़ Nagle एल्गोरिदम का उपयोग करती हैं या नहीं। |
| static void [SetTcpKeepAlive](./settcpkeepalive/)(**bool**, **int32_t**, **int32_t**) | 'Keep-Alive' विकल्प सक्रिय है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर में पॉइंटर को कमजोर मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंट का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [DefaultNonPersistentConnectionLimit](./defaultnonpersistentconnectionlimit/) | डिफ़ॉल्ट गैर-स्थायी कनेक्शनों की संख्या। |
| static [DefaultPersistentConnectionLimit](./defaultpersistentconnectionlimit/) | डिफ़ॉल्ट स्थायी कनेक्शनों की संख्या। |

## देखें

* क्लास [Object](../../system/object/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: WebClientProtocol
second_title: Aspose.Slides for C++ API संदर्भ
description: "यह बेस क्लास सभी XML वेब सेवा क्लाइंट प्रॉक्सी में उपयोग की जाती है जो ASP.NET का उपयोग करके बनाई गई थीं। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग कर ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग कर कभी न बनाएं, क्योंकि इससे रन-टाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ होंगी। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन के आर्ग्यूमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 144
url: /hi/system.web.services.protocols/webclientprotocol/
---
## WebClientProtocol क्लास


यह बेस क्लास सभी XML [Web](../../system.web/) सेवा क्लाइंट प्रॉक्सी में उपयोग की जाती है जो ASP.NET का उपयोग करके बनाई गई थीं। इस क्लास की ऑब्जेक्ट्स केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएं, क्योंकि इससे रन-टाइम एरर और/या एसेर्शन फ़ॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शन आर्ग्युमेंट के रूप में पास करें।

```cpp
class WebClientProtocol : public virtual System::Object
```

## मेथड्स

| Method | Description |
| --- | --- |
| virtual void [Abort](./abort/)() | अनुरोध को रद्द करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को बराबर माना जाता है, हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मूल्य के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() | कनेक्शन समूह का नाम प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\> [get_Credentials](./get_credentials/)() | प्रमाणीकरण जानकारी प्राप्त करता है। |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() | एक मान प्राप्त करता है जो दर्शाता है कि प्री-ऑथेंटिकेशन सक्षम है या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_RequestEncoding](./get_requestencoding/)() | क्लाइंट अनुरोध बनाने के लिए उपयोग में ली जाने वाली एन्कोडिंग प्राप्त करता है। |
| **int32_t** [get_Timeout](./get_timeout/)() | अनुरोध के टाइम-आउट से पहले प्रतीक्षा करने के समय-अवधि को प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Uri](./get_uri/)() | XML [Web](../../system.web/) सेवा URI प्राप्त करता है। |
| [String](../../system/string/) [get_Url](./get_url/)() | XML [Web](../../system.web/) सेवा URL प्राप्त करता है। |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | एक मान प्राप्त करता है जो दर्शाता है कि 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([String](../../system/string/)) | कनेक्शन समूह का नाम सेट करता है। |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[Net::ICredentials](../../system.net/icredentials/)\>) | प्रमाणीकरण जानकारी सेट करता है। |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि प्री-ऑथेंटिकेशन सक्षम है या नहीं। |
| void [set_RequestEncoding](./set_requestencoding/)([System::SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>) | क्लाइंट अनुरोध बनाने के लिए उपयोग की जाने वाली एन्कोडिंग सेट करता है। |
| void [set_Timeout](./set_timeout/)(**int32_t**) | अनुरोध के टाइम-आउट से पहले प्रतीक्षा करने की समय-अवधि सेट करता है। |
| void [set_Uri](./set_uri/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | XML [Web](../../system.web/) सेवा URI सेट करता है। |
| void [set_Url](./set_url/)([String](../../system/string/)) | XML [Web](../../system.web/) सेवा URL सेट करता है। |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे बुलाया नहीं जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे बुलाया नहीं जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट को बढ़ाता है। सीधे बुलाया नहीं जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट को घटाता है। सीधे बुलाया नहीं जाना चाहिए; बल्कि, स्मार्ट पॉइंटर्स और ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें भी

* Class [Object](../../system/object/)
* Namespace [System::Web::Services::Protocols](../)
* Library [Aspose.Slides](../../)
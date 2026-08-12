---
title: FtpWebRequest
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: File Transfer Protocol (FTP) क्लाइंट को लागू करता है। डमी क्लास जो अनूदित कोड को FtpWebRequest रेफ़रेंसेज़ के साथ लिंक करना संभव बनाती है, लेकिन इसे निष्पादित नहीं करती। इसमें कोई सही ढंग से लागू किए गये सदस्य नहीं हैं।
type: docs
weight: 170
url: /hi/system.net/ftpwebrequest/
---
## FtpWebRequest क्लास


File Transfer Protocol (FTP) क्लाइंट को लागू करता है। डमी क्लास जो [FtpWebRequest](./) रेफरेंसेज़ के साथ अनूदित कोड को लिंक करना संभव बनाती है, लेकिन इसे निष्पादित नहीं करती। इसमें कोई सही तरह से लागू किए गए सदस्य नहीं हैं।

```cpp
class FtpWebRequest : public System::Net::WebRequest
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [Abort](../webrequest/abort/)() | वर्तमान अनुरोध को समाप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](../webrequest/begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | संसाधन में डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु एक असिंक्रोनस ऑपरेशन शुरू करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](../webrequest/begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | संसाधन के लिए एक असिंक्रोनस अनुरोध शुरू करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास की नई इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास की नई इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI योजना के लिए एक [WebRequest](../webrequest/) वंशज बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास की नई इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](../httpwebrequest/)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास की नई इंस्टेंस बनाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](../webrequest/endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | स्ट्रीम प्राप्त करने के निर्दिष्ट असिंक्रोनस ऑपरेशन के पूर्ण होने तक प्रतीक्षा करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](../webrequest/endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | संसाधन के लिए निर्दिष्ट असिंक्रोनस अनुरोध के पूर्ण होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | कैश नीति प्राप्त करता है। |
| virtual [System::String](../../system/string/) [get_ConnectionGroupName](../webrequest/get_connectiongroupname/)() | कनेक्शन समूह का नाम प्राप्त करता है। |
| virtual **int64_t** [get_ContentLength](../webrequest/get_contentlength/)() | भेजे जाने वाले अनुरोध डेटा के बाइट्स की संख्या प्राप्त करता है। |
| virtual [String](../../system/string/) [get_ContentType](../webrequest/get_contenttype/)() | अनुरोध का MIME प्रकार प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](../webrequest/get_credentials/)() | वर्तमान अनुरोध से संबंधित प्रमाणीकरण जानकारी प्राप्त करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | वैश्विक HTTP प्रॉक्सी प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](../webrequest/get_headers/)() | HTTP हेडर संग्रह प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Method](../webrequest/get_method/)() | HTTP मेथड प्राप्त करता है। |
| virtual **bool** [get_PreAuthenticate](../webrequest/get_preauthenticate/)() | एक मान प्राप्त करता है जो दर्शाता है कि अनुरोध को पूर्व-प्रमाणित होना चाहिए या नहीं। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | प्रीफ़िक्स सूची प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](../webrequest/get_proxy/)() | HTTP प्रॉक्सी प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](../webrequest/get_requesturi/)() | अनुरोध URI को लौटाता है। |
| virtual **int32_t** [get_Timeout](../webrequest/get_timeout/)() | मिलिसेकंड में समय की मात्रा प्राप्त करता है जिसके बाद अनुरोध का समय समाप्त हो जायेगा। |
| virtual **bool** [get_UseDefaultCredentials](../webrequest/get_usedefaultcredentials/)() | एक मान प्राप्त करता है जो दर्शाता है कि 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के समान है या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](../webrequest/getrequeststream/)() | संसाधन में डेटा लिखने के लिए स्ट्रीम लौटाता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](../webrequest/getresponse/)() | वर्तमान वेब अनुरोध से जुड़े वेब प्रतिक्रिया को लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() कथन के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों के कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू प्रकार के ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के मामले के लिए विशिष्टीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामले के लिए विशिष्टीकरण। |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | निर्दिष्ट URI के लिए [WebRequest](../webrequest/) वंशज को पंजीकृत करता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान के द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | कैश नीति सेट करता है। |
| virtual void [set_ConnectionGroupName](../webrequest/set_connectiongroupname/)([System::String](../../system/string/)) | कनेक्शन समूह का नाम सेट करता है। |
| virtual void [set_ContentLength](../webrequest/set_contentlength/)(**int64_t**) | भेजे जाने वाले अनुरोध डेटा के बाइट्स की संख्या सेट करता है। |
| virtual void [set_ContentType](../webrequest/set_contenttype/)([String](../../system/string/)) | अनुरोध का MIME प्रकार सेट करता है। |
| virtual void [set_Credentials](../webrequest/set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | वर्तमान अनुरोध से संबंधित प्रमाणीकरण जानकारी सेट करता है। |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | वैश्विक HTTP प्रॉक्सी सेट करता है। |
| virtual void [set_Headers](../webrequest/set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) | HTTP हेडर संग्रह सेट करता है। |
| virtual void [set_Method](../webrequest/set_method/)([String](../../system/string/)) | HTTP मेथड सेट करता है। |
| virtual void [set_PreAuthenticate](../webrequest/set_preauthenticate/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि अनुरोध को पूर्व-प्रमाणित होना चाहिए या नहीं। |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | प्रीफ़िक्स सूची सेट करता है। |
| virtual void [set_Proxy](../webrequest/set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | HTTP प्रॉक्सी सेट करता है। |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | मिलिसेकंड में समय की मात्रा सेट करता है जिसके बाद अनुरोध का समय समाप्त हो जाएगा। |
| virtual void [set_UseDefaultCredentials](../webrequest/set_usedefaultcredentials/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के समान है या नहीं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को कमजोर पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउन्टर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() कथन के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें भी

* क्लास [WebRequest](../webrequest/)
* नामस्थान [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
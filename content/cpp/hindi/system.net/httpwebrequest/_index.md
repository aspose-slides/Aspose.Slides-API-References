---
title: HttpWebRequest
second_title: Aspose.Slides for C++ API संदर्भ
description: "HTTP वेब अनुरोध का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन त्रुटियां हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 274
url: /hi/system.net/httpwebrequest/
---
## HttpWebRequest क्लास

HTTP वेब अनुरोध का प्रतिनिधित्व करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि इससे रनटाइम त्रुटियां और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class HttpWebRequest : public System::Net::WebRequest
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| void [Abort](./abort/)() override | वर्तमान अनुरोध को समाप्त करता है। |
| virtual void [AddRange](./addrange/)(**int32_t**) | वर्तमान अनुरोध में '[Range](../../system/range/)' हेडर जोड़ता है। |
| virtual void [AddRange](./addrange/)([System::String](../../system/string/), **int32_t**, **int32_t**) | वर्तमान अनुरोध में '[Range](../../system/range/)' हेडर जोड़ता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetRequestStream](./begingetrequeststream/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | संसाधन में डेटा लिखने के लिए एक स्ट्रीम प्राप्त करने हेतु असिंक्रोनस ऑपरेशन शुरू करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginGetResponse](./begingetresponse/)([AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | संसाधन के लिये असिंक्रोनस अनुरोध शुरू करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([String](../../system/string/)) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास का नया इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [Create](../webrequest/create/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास का नया इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebRequest](../webrequest/)\> [CreateDefault](../webrequest/createdefault/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI स्कीम के लिये [WebRequest](../webrequest/) डीसेंडेंट बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([String](../../system/string/)) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास का नया इंस्टेंस बनाता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[HttpWebRequest](./)\> [CreateHttp](../webrequest/createhttp/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | निर्दिष्ट URI का उपयोग करके [WebRequest](../webrequest/) क्लास का नया इंस्टेंस बनाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [EndGetRequestStream](./endgetrequeststream/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | निर्दिष्ट असिंक्रोनस ऑपरेशन के समाप्त होने तक स्ट्रीम प्राप्त करने के लिये प्रतीक्षा करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [EndGetResponse](./endgetresponse/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) override | निर्दिष्ट असिंक्रोनस अनुरोध के समाप्त होने तक प्रतीक्षा करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN से भी बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली की फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN से भी बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिये। |
| [String](../../system/string/) [get_Accept](./get_accept/)() | 'Accept' HTTP हेडर का मान प्राप्त करता है। |
| virtual **bool** [get_AllowAutoRedirect](./get_allowautoredirect/)() | एक मान प्राप्त करता है जो दर्शाता है कि अनुरोध को रीडायरेक्शन का पालन करना चाहिए या नहीं। |
| virtual **bool** [get_AllowReadStreamBuffering](./get_allowreadstreambuffering/)() | एक मान प्राप्त करता है जो दर्शाता है कि संसाधन से प्राप्त डेटा को बफ़र किया जाना चाहिए या नहीं। |
| virtual **bool** [get_AllowWriteStreamBuffering](./get_allowwritestreambuffering/)() | एक मान प्राप्त करता है जो दर्शाता है कि डेटा भेजने के लिये बफ़रिंग सक्षम है या नहीं। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\> [get_CachePolicy](../webrequest/get_cachepolicy/)() | कैश नीति प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\> [get_ClientCertificates](./get_clientcertificates/)() | वर्तमान अनुरोध से जुड़े प्रमाणपत्रों का संग्रह प्राप्त करता है। |
| [System::String](../../system/string/) [get_ConnectionGroupName](./get_connectiongroupname/)() override | कनेक्शन समूह का नाम प्राप्त करता है। |
| **int64_t** [get_ContentLength](./get_contentlength/)() override | भेजे जाने वाले अनुरोध डेटा के बाइट्स की संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_ContentType](./get_contenttype/)() override | अनुरोध का MIME प्रकार प्राप्त करता है। |
| **int32_t** [get_ContinueTimeout](./get_continuetimeout/)() | 100-Continue स्टेटस कोड प्राप्त होने तक प्रतीक्षा के लिये टाइमआउट प्राप्त करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\> [get_CookieContainer](./get_cookiecontainer/)() | वर्तमान वेब अनुरोध से जुड़ा कुकी कंटेनर प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() override | वर्तमान अनुरोध से जुड़ी प्रमाणीकरण जानकारी प्राप्त करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_DefaultWebProxy](../webrequest/get_defaultwebproxy/)() | वैश्विक HTTP प्रॉक्सी प्राप्त करता है। |
| virtual **bool** [get_HaveResponse](./get_haveresponse/)() | एक मान लौटाता है जो दर्शाता है कि कोई प्रतिक्रिया प्राप्त हुई है या नहीं। |
| [System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\> [get_Headers](./get_headers/)() override | HTTP हेडरों का संग्रह प्राप्त करता है। |
| virtual **bool** [get_KeepAlive](./get_keepalive/)() | 'Keep-Alive' हेडर को शामिल करने के लिये वर्तमान अनुरोध को आवश्यक है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual int [get_MaximumAutomaticRedirections](./get_maximumautomaticredirections/)() | अनुमत अधिकतम रीडायरेक्शन की संख्या प्राप्त करता है। |
| [String](../../system/string/) [get_Method](./get_method/)() override | HTTP मेथड प्राप्त करता है। |
| **bool** [get_PreAuthenticate](./get_preauthenticate/)() override | अनुरोध के प्री-ऑथेंटिकेशन की आवश्यकता दर्शाने वाला मान प्राप्त करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\> [get_PrefixList](../webrequest/get_prefixlist/)() | प्रिफिक्स सूची प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\> [get_Proxy](./get_proxy/)() override | HTTP प्रॉक्सी प्राप्त करता है। |
| virtual [System::String](../../system/string/) [get_Referer](./get_referer/)() | 'Referer' हेडर का मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_RequestUri](./get_requesturi/)() override | अनुरोध का URI लौटाता है। |
| virtual **bool** [get_SendChunked](./get_sendchunked/)() | डेटाबे को खंडों में भेजने की आवश्यकता दर्शाने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[ServicePoint](../servicepoint/)\> [get_ServicePoint](./get_servicepoint/)() | संसाधन के नेटवर्क कनेक्शन को दर्शाने वाला सर्विस पॉइंट लौटाता है। |
| virtual **bool** [get_SupportsCookieContainer](./get_supportscookiecontainer/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान अनुरोध कुकी कंटेनर का उपयोग कर सकता है या नहीं। |
| **int32_t** [get_Timeout](./get_timeout/)() override | वह समय मिलीसेकंड में प्राप्त करता है जिसके बाद अनुरोध टाइमआउट हो जाएगा। |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() override | 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual [System::String](../../system/string/) [get_UserAgent](./get_useragent/)() | 'User-Agent' हेडर का मान प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\> [GetRequestStream](./getrequeststream/)() override | संसाधन में डेटा लिखने के लिये स्ट्रीम लौटाता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[WebResponse](../webresponse/)\> [GetResponse](./getresponse/)() override | वर्तमान वेब अनुरोध से जुड़ी वेब रिस्पॉन्स लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
|  [HttpWebRequest](./httpwebrequest/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | एक नया इंस्टेंस बनाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| static **bool** [RegisterPrefix](../webrequest/registerprefix/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IWebRequestCreate](../iwebrequestcreate/)\>) | निर्दिष्ट URI के लिये [WebRequest](../webrequest/) डीसेंडेंट को रजिस्टर करता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्देशित मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| void [set_Accept](./set_accept/)([String](../../system/string/)) | 'Accept' HTTP हेडर मान सेट करता है। |
| virtual void [set_AllowAutoRedirect](./set_allowautoredirect/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि अनुरोध को रीडायरेक्शन का पालन करना चाहिए या नहीं। |
| virtual void [set_AllowReadStreamBuffering](./set_allowreadstreambuffering/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि संसाधन से प्राप्त डेटा को बफ़र किया जाना चाहिए या नहीं। |
| virtual void [set_AllowWriteStreamBuffering](./set_allowwritestreambuffering/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि डेटा भेजने के लिये बफ़रिंग सक्षम है या नहीं। |
| virtual void [set_CachePolicy](../webrequest/set_cachepolicy/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::Cache::RequestCachePolicy](../../system.net.cache/requestcachepolicy/)\>) | कैश नीति सेट करता है। |
| virtual void [set_ClientCertificates](./set_clientcertificates/)([System::SharedPtr](../../system/sharedptr/)\<[System::Security::Cryptography::X509Certificates::X509CertificateCollection](../../system.security.cryptography.x509certificates/x509certificatecollection/)\>) | वर्तमान अनुरोध से जुड़े प्रमाणपत्रों के संग्रह को सेट करता है। |
| void [set_ConnectionGroupName](./set_connectiongroupname/)([System::String](../../system/string/)) override | कनेक्शन समूह का नाम सेट करता है। |
| void [set_ContentLength](./set_contentlength/)(**int64_t**) override | भेजे जाने वाले अनुरोध डेटा के बाइट्स की संख्या सेट करता है। |
| void [set_ContentType](./set_contenttype/)([String](../../system/string/)) override | अनुरोध का MIME प्रकार सेट करता है। |
| void [set_ContinueTimeout](./set_continuetimeout/)(**int32_t**) | 100-Continue स्टेटस कोड प्राप्त होने तक प्रतीक्षा के लिये टाइमआउट सेट करता है। |
| virtual void [set_CookieContainer](./set_cookiecontainer/)([System::SharedPtr](../../system/sharedptr/)\<[System::Net::CookieContainer](../cookiecontainer/)\>) | वर्तमान वेब अनुरोध से जुड़े कुकी कंटेनर को सेट करता है। |
| void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) override | वर्तमान अनुरोध से जुड़ी प्रमाणीकरण जानकारी सेट करता है। |
| static void [set_DefaultWebProxy](../webrequest/set_defaultwebproxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) | वैश्विक HTTP प्रॉक्सी सेट करता है। |
| void [set_Headers](./set_headers/)([System::SharedPtr](../../system/sharedptr/)\<[WebHeaderCollection](../webheadercollection/)\>) override | HTTP हेडरों के संग्रह को सेट करता है। |
| virtual void [set_KeepAlive](./set_keepalive/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि वर्तमान अनुरोध को 'Keep-Alive' हेडर शामिल करना चाहिए या नहीं। |
| virtual void [set_MaximumAutomaticRedirections](./set_maximumautomaticredirections/)(int) | अनुमत अधिकतम रीडायरेक्शन की संख्या सेट करता है। |
| void [set_Method](./set_method/)([String](../../system/string/)) override | HTTP मेथड सेट करता है। |
| void [set_PreAuthenticate](./set_preauthenticate/)(**bool**) override | एक मान सेट करता है जो दर्शाता है कि अनुरोध को प्री-ऑथेंटिकेशन आवश्यक है या नहीं। |
| static void [set_PrefixList](../webrequest/set_prefixlist/)([System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[System::SharedPtr](../../system/sharedptr/)\<**WebRequest::WebRequestPrefixElement**\>\>\>) | प्रिफिक्स सूची सेट करता है। |
| void [set_ProtocolVersion](./set_protocolversion/)([System::Version](../../system/version/)) | HTTP का संस्करण सेट करता है। |
| void [set_Proxy](./set_proxy/)([System::SharedPtr](../../system/sharedptr/)\<[IWebProxy](../iwebproxy/)\>) override | HTTP प्रॉक्सी सेट करता है। |
| virtual void [set_Referer](./set_referer/)([System::String](../../system/string/)) | 'Referer' हेडर का मान सेट करता है। |
| virtual void [set_SendChunked](./set_sendchunked/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि डेटा को खंडों में भेजा जाना चाहिए या नहीं। |
| void [set_Timeout](./set_timeout/)(int) override | वह समय मिलीसेकंड में सेट करता है जिसके बाद अनुरोध टाइमआउट हो जाएगा। |
| virtual void [set_Timeout](../webrequest/set_timeout/)(**int32_t**) | वह समय मिलीसेकंड में सेट करता है जिसके बाद अनुरोध टाइमआउट हो जाएगा। |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) override | 'Credential' प्रॉपर्टी 'DefaultCredentials' प्रॉपर्टी के बराबर है या नहीं, यह दर्शाने वाला मान सेट करता है। |
| virtual void [set_UserAgent](./set_useragent/)([System::String](../../system/string/)) | 'User-Agent' हेडर का मान सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को कार्यान्वित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [WebRequest](../webrequest/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
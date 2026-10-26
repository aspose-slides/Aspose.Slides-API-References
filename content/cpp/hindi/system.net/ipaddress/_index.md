---
title: IPAddress
second_title: Aspose.Slides for C++ API संदर्भ
description: "IP पते का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियां और/या assertion faults हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 326
url: /hi/system.net/ipaddress/
---
## IPAddress क्लास

IP पते का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या assertion faults उत्पन्न हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को तर्क के रूप में पास करने के लिए करें।

```cpp
class IPAddress : public System::Object
```

## मेथड्स

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर मान लिया जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर मान लिया जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [System::Net::Sockets::AddressFamily](../../system.net.sockets/addressfamily/) [get_AddressFamily](./get_addressfamily/)() | पता परिवार लौटाता है। |
| **bool** [get_IsIPv4MappedToIPv6](./get_isipv4mappedtoipv6/)() | एक मान लौटाता है जो दर्शाता है कि पता IPv4 पता है और यह IPv6 पते पर मैप किया गया है। |
| **bool** [get_IsIPv6LinkLocal](./get_isipv6linklocal/)() | एक मान लौटाता है जो दर्शाता है कि पता IPv6 लिंक-लोकल पता है। |
| **bool** [get_IsIPv6Multicast](./get_isipv6multicast/)() | एक मान लौटाता है जो दर्शाता है कि पता एक वैश्विक IPv6 मल्टिकास्ट पता है। |
| **bool** [get_IsIPv6SiteLocal](./get_isipv6sitelocal/)() | एक मान लौटाता है जो दर्शाता है कि पता IPv6 साइट-लोकल पता है। |
| **bool** [get_IsIPv6Teredo](./get_isipv6teredo/)() | एक मान लौटाता है जो दर्शाता है कि पता IPv6 टेर्डो पता है। |
| **int64_t** [get_ScopeId](./get_scopeid/)() | IPv6 पते का स्कोप पहचानकर्ता प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetAddressBytes](./getaddressbytes/)() | IP पते की बाइट एरे लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| [ImplPtr](./implptr/) [GetImpl](./getimpl/)() const | इम्प्लीमेंटेशन का पॉइंटर लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| static **int64_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int64_t**) | निर्देशित होस्ट बाइट क्रम को संबंधित नेटवर्क बाइट क्रम में परिवर्तित करता है। |
| static **int32_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int32_t**) | निर्देशित होस्ट बाइट क्रम को संबंधित नेटवर्क बाइट क्रम में परिवर्तित करता है। |
| static **int16_t** [HostToNetworkOrder](./hosttonetworkorder/)(**int16_t**) | निर्देशित होस्ट बाइट क्रम को संबंधित नेटवर्क बाइट क्रम में परिवर्तित करता है। |
|  [IPAddress](./ipaddress/)(**int64_t**) | एक नया इंस्टेंस बनाता है। |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int64_t**) | एक नया इंस्टेंस बनाता है। |
|  [IPAddress](./ipaddress/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एक नया इंस्टेंस बनाता है। |
|  [IPAddress](./ipaddress/)() | एक नया इंस्टेंस बनाता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के इंस्टेंस का प्रतिनिधित्व करता है। C# 'is' ऑपरेटर का समानार्थी। |
| static **bool** [IsLoopback](./isloopback/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>) | एक मान लौटाता है जो दर्शाता है कि निर्दिष्ट पता लूपबैक पता है। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv4](./maptoipv4/)() | पते को IPv4 पते में मैप करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [MapToIPv6](./maptoipv6/)() | पते को IPv6 पते में मैप करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
| static **int64_t** [NetworkToHostOrder](./networktohostorder/)(**int64_t**) | निर्देशित नेटवर्क बाइट क्रम को संबंधित होस्ट बाइट क्रम में परिवर्तित करता है। |
| static **int32_t** [NetworkToHostOrder](./networktohostorder/)(**int32_t**) | निर्देशित नेटवर्क बाइट क्रम को संबंधित होस्ट बाइट क्रम में परिवर्तित करता है। |
| static **int16_t** [NetworkToHostOrder](./networktohostorder/)(**int16_t**) | निर्देशित नेटवर्क बाइट क्रम को संबंधित होस्ट बाइट क्रम में परिवर्तित करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर्स को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट प्रारंभ करता है और सबक्लासों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\> [Parse](./parse/)([String](../../system/string/)) | एक पास की गई स्ट्रिंग को [IPAddress](./) क्लास के इंस्टेंस में परिवर्तित करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | निर्देशित मूल्य प्रकार ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्देशित मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_ScopeId](./set_scopeid/)(**int64_t**) | IPv6 पते का स्कोप पहचानकर्ता सेट करता है। |
| void [SetImpl](./setimpl/)([ImplPtr](./implptr/)) | इम्प्लीमेंटेशन का पॉइंटर सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एकवीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IPAddress](./)\>\&) | एक पास की गई स्ट्रिंग को [IPAddress](./) क्लास के इंस्टेंस में बदलने का प्रयास करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर्स को मुक्त करता है। |

## फ़ील्ड्स

| Field | Description |
| --- | --- |
| static [Any](./any/) | IPv4 पता जो दर्शाता है कि सर्वर को सभी नेटवर्क इंटरफेसेस पर सुनना चाहिए। |
| static [Broadcast](./broadcast/) | IPv4 ब्रॉडकास्ट पता। |
| static [IPv6Any](./ipv6any/) | IPv6 पता जो दर्शाता है कि सर्वर को सभी नेटवर्क इंटरफेसेस पर सुनना चाहिए। |
| static [IPv6Loopback](./ipv6loopback/) | IPv6 लूपबैक पता। |
| static [IPv6None](./ipv6none/) | IPv6 पता जो दर्शाता है कि सर्वर को कोई भी नेटवर्क इंटरफेस नहीं सुनना चाहिए। |
| static [Loopback](./loopback/) | IPv4 लूपबैक पता। |
| static [None](./none/) | IPv4 पता जो दर्शाता है कि सर्वर को कोई भी नेटवर्क इंटरफेस नहीं सुनना चाहिए। |

## टाइपडिफ़्स

| Typedef | Description |
| --- | --- |
| [ImplPtr](./implptr/) | इम्प्लीमेंटेशन प्रकार का पॉइंटर। |

## देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
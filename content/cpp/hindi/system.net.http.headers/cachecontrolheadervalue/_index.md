---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API संदर्भ
description: "'Cache-Control' हेडर का मान दर्शाता है। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या अभिकथन दोष उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।"
type: docs
weight: 14
url: /hi/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue क्लास

'Cache-Control' हेडर का मान दर्शाता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या अभिकथन दोष उत्पन्न होंगे। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शनों को तर्क के रूप में पास करने के लिए करें।

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | एक नया उदाहरण बनाता है। |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता, फिर भी दो NaN को बराबर मानते हुए C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | कैश-एक्सटेंशन टोकन्स का संग्रह लौटाता है। |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | क्लाइंट द्वारा प्रतिक्रिया स्वीकार करने के समय को निर्धारित करने वाली अधिकतम आयु मान (सेकंड में) प्राप्त करता है। |
| **bool** [get_MaxStale](./get_maxstale/)() | क्लाइंट द्वारा समाप्त प्रतिक्रिया को स्वीकार करने का निर्धारण करने वाला मान प्राप्त करता है। |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | सेकंड में वह मान प्राप्त करता है जो निर्धारित करता है कि क्लाइंट कब तक समाप्त प्रतिक्रियाएँ स्वीकार करेगा। |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | ताज़ा जीवनकाल निर्धारित करने वाला मान प्राप्त करता है। |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | सर्वर द्वारा जब कैश एंट्री पुरानी हो जाती है तो उसकी पुनः सत्यापन की आवश्यकता है या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है। |
| **bool** [get_NoCache](./get_nocache/)() | क्लाइंट द्वारा कैश्ड प्रतिक्रिया को स्वीकार करने का निर्धारण करने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | 'Cache-Control' हेडर में 'no-cache' निर्देश के फ़ील्डनामों का संग्रह प्राप्त करता है। |
| **bool** [get_NoStore](./get_nostore/)() | कैश द्वारा HTTP अनुरोध या प्रतिक्रिया के किसी भी भाग को न स्टोर करने का निर्धारण करने वाला मान प्राप्त करता है। |
| **bool** [get_NoTransform](./get_notransform/)() | कैश या प्रॉक्सी द्वारा एंटिटी बॉडी के किसी भी भाग को न बदलने का निर्धारण करने वाला मान प्राप्त करता है। |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | क्लाइंट द्वारा केवल कैश्ड एंट्रीज़ का उपयोग करने का निर्धारण करने वाला मान प्राप्त करता है। |
| **bool** [get_Private](./get_private/)() | HTTP प्रतिक्रिया संदेश या उसका भाग केवल एक उपयोगकर्ता के लिए है और इसे साझा कैश द्वारा कैश नहीं किया जाना चाहिए, यह निर्धारित करने वाला मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | 'Cache-Control' हेडर में 'private' निर्देश के फ़ील्डनामों का संग्रह प्राप्त करता है। |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | सर्वर द्वारा कैश एंट्री के पुराना होने पर पुनः सत्यापन की आवश्यकता है या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है। |
| **bool** [get_Public](./get_public/)() | किसी भी कैश द्वारा HTTP प्रतिक्रिया को कैश किया जा सकता है या नहीं, यह निर्धारित करने वाला मान प्राप्त करता है। |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | साझा कैश के लिए 'Cache-Control' हेडर के 'max-age' निर्देश या 'Expires' हेडर को ओवरराइड करने वाला साझा अधिकतम आयु मान (सेकंड में) प्राप्त करता है। |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | निर्दिष्ट इंडेक्स से पास की गई स्ट्रिंग को [CacheControlHeaderValue](./) क्लास के एक उदाहरण में परिवर्तित करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार के उदाहरण को दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट आरंभ करता है और उपवर्गों की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | पास की गई स्ट्रिंग को [CacheControlHeaderValue](./) क्लास के एक उदाहरण में परिवर्तित करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रीफ़रेंस के साथ वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | क्लाइंट द्वारा प्रतिक्रिया स्वीकार करने के समय को निर्धारित करने वाला अधिकतम आयु मान (सेकंड में) सेट करता है। |
| void [set_MaxStale](./set_maxstale/)(**bool**) | क्लाइंट द्वारा समाप्त प्रतिक्रिया को स्वीकार करने का निर्धारण करने वाला मान सेट करता है। |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | सेकंड में वह मान सेट करता है जो निर्धारित करता है कि क्लाइंट कब तक समाप्त प्रतिक्रियाएँ स्वीकार करेगा। |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | ताज़ा जीवनकाल निर्धारित करने वाला मान सेट करता है। |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | सर्वर द्वारा कैश एंट्री के पुराना होने पर पुनः सत्यापन की आवश्यकता है या नहीं, यह निर्धारित करने वाला मान सेट करता है। |
| void [set_NoCache](./set_nocache/)(**bool**) | क्लाइंट द्वारा कैश्ड प्रतिक्रिया को स्वीकार करने का निर्धारण करने वाला मान सेट करता है। |
| void [set_NoStore](./set_nostore/)(**bool**) | कैश द्वारा HTTP अनुरोध या प्रतिक्रिया के किसी भी भाग को न स्टोर करने का निर्धारण करने वाला मान सेट करता है। |
| void [set_NoTransform](./set_notransform/)(**bool**) | कैश या प्रॉक्सी द्वारा एंटिटी बॉडी के किसी भी भाग को न बदलने का निर्धारण करने वाला मान सेट करता है। |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | क्लाइंट द्वारा केवल कैश्ड एंट्रीज़ का उपयोग करने का निर्धारण करने वाला मान सेट करता है। |
| void [set_Private](./set_private/)(**bool**) | HTTP प्रतिक्रिया संदेश या उसका भाग केवल एक उपयोगकर्ता के लिए है और इसे साझा कैश द्वारा कैश नहीं किया जाना चाहिए, यह निर्धारित करने वाला मान सेट करता है। |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | सर्वर द्वारा कैश एंट्री के पुराना होने पर पुनः सत्यापन की आवश्यकता है या नहीं, यह निर्धारित करने वाला मान सेट करता है। |
| void [set_Public](./set_public/)(**bool**) | किसी भी कैश द्वारा HTTP प्रतिक्रिया को कैश किया जा सकता है या नहीं, यह निर्धारित करने वाला मान सेट करता है। |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | साझा कैश के लिए 'Cache-Control' हेडर के 'max-age' निर्देश या 'Expires' हेडर को ओवरराइड करने वाला साझा अधिकतम आयु मान (सेकंड में) सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'th' टेम्पलेट आर्ग्युमेंट को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | पास की गई स्ट्रिंग को [CacheControlHeaderValue](./) क्लास के एक उदाहरण में परिवर्तित करने का प्रयास करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें भी

* क्लास [ICloneable](../../system/icloneable/)
* नामस्थान [System::Net::Http::Headers](../)
* लाइब्रेरी [Aspose.Slides](../../)
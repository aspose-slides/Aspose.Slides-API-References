---
title: WebProxy
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "HTTP वेब-प्रॉक्सी सर्वर का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम त्रुटियाँ और/या असर्शन फ़ॉल्ट्स उत्पन्न हो सकते हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्युमेंट के रूप में पास करने के लिए करें।"
type: docs
weight: 495
url: /hi/system.net/webproxy/
---
## WebProxy क्लास

एक http वेब-प्रॉक्सी सर्वर का प्रतिनिधित्व करता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन Faults उत्पन्न होंगी। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों को आर्ग्युमेंट के रूप में पास करने के लिए करें।

```cpp
class WebProxy : public System::Net::IWebProxy
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_Address](./get_address/)() | वर्तमान प्रॉक्सी सर्वर का पता प्राप्त करता है। |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_BypassList](./get_bypasslist/)() | उन पते की सूची प्राप्त करता है जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |
| **bool** [get_BypassProxyOnLocal](./get_bypassproxyonlocal/)() | एक मान प्राप्त करता है जो दर्शाता है कि स्थानीय पते के लिए प्रॉक्सी सर्वर का उपयोग होना चाहिए या नहीं। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\> [get_Credentials](./get_credentials/)() | प्रॉक्सी सर्वर को प्रमाणीकरण के लिए भेजे जाने वाले क्रेडेंशियल्स प्राप्त करता है। |
| **bool** [get_UseDefaultCredentials](./get_usedefaultcredentials/)() | एक मान प्राप्त करता है जो दर्शाता है कि डिफ़ॉल्ट क्रेडेंशियल्स अनुरोधों के साथ भेजे जाने चाहिए या नहीं। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| static [System::SharedPtr](../../system/sharedptr/)\<[WebProxy](./)\> [GetDefaultProxy](./getdefaultproxy/)() | इंटरनेट एक्सप्लोरर के गैर-डायनामिक सेटिंग्स का उपयोग करने वाला प्रॉक्सी लौटाता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स का हेशिंग सक्षम करता है। |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [GetProxy](./getproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | वेब अनुरोध के लिए प्रॉक्सी किया गया URI लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचें कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| virtual **bool** [IsBypassed](./isbypassed/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | जाँचता है कि निर्दिष्ट URI के लिए प्रॉक्सी सर्वर का उपयोग नहीं किया गया है या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानार्थी। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्टिंग को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Address](./set_address/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | वर्तमान प्रॉक्सी सर्वर का पता सेट करता है। |
| void [set_BypassList](./set_bypasslist/)([System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | उन पते की सूची सेट करता है जो प्रॉक्सी सर्वर का उपयोग नहीं करते। |
| void [set_BypassProxyOnLocal](./set_bypassproxyonlocal/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि स्थानीय पते के लिए प्रॉक्सी सर्वर का उपयोग होना चाहिए या नहीं। |
| virtual void [set_Credentials](./set_credentials/)([System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | प्रॉक्सी सर्वर को प्रमाणीकरण के लिए भेजे जाने वाले क्रेडेंशियल्स सेट करता है। |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि डिफ़ॉल्ट क्रेडेंशियल्स अनुरोधों के साथ भेजे जाने चाहिए या नहीं। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-थ टेम्पलेट आर्ग्युमेंट को वेक पॉइंटर (शेयर किए गए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वेक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और लौटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वेक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वेक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [WebProxy](./webproxy/)() | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([String](../../system/string/), **int32_t**) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([String](../../system/string/)) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>) | एक नया इंस्टेंस बनाता है। |
|  [WebProxy](./webproxy/)([String](../../system/string/), **bool**, [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICredentials](../icredentials/)\>) | एक नया इंस्टेंस बनाता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* क्लास [IWebProxy](../iwebproxy/)
* नामस्थान [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
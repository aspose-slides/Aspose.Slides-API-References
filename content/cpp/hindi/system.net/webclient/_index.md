---
title: WebClient
second_title: "Aspose.Slides के लिए C++ API संदर्भ"
description: "WebClient सामान्य मेथड्स प्रदान करता है डेटा भेजने और प्राप्त करने के लिए। इस क्लास की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फॉल्ट्स का कारण बन सकता है। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों में आर्ग्युमेंट के रूप में पास करें।"
type: docs
weight: 469
url: /hi/system.net/webclient/
---
## WebClient क्लास

[WebClient](./) डेटा भेजने और प्राप्त करने के लिए सामान्य मेथड्स प्रदान करता है। इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि यह रनटाइम त्रुटियों और/या असर्शन फॉल्ट का कारण बन सकता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर को फ़ंक्शनों के आर्ग्युमेंट के रूप में पास करें।

```cpp
class WebClient : public System::ComponentModel::Component
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  [Component](../../system.componentmodel/component/component/)() | RTTI जानकारी। |
| void [Dispose](../../system.componentmodel/component/dispose/)(**bool**) | डिस्पोजेबल पैटर्न समर्थन; कुछ नहीं करता। |
| [ByteArrayPtr](../../system/bytearrayptr/) [DownloadData](./downloaddata/)(const [String](../../system/string/)\&) const | निर्दिष्ट संसाधन को बाइट एरे के रूप में डाउनलोड करता है। |
| [ByteArrayPtr](../../system/bytearrayptr/) [DownloadData](./downloaddata/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) const | निर्दिष्ट संसाधन को बाइट एरे के रूप में डाउनलोड करता है। |
| [String](../../system/string/) [DownloadString](./downloadstring/)(const [String](../../system/string/)\&) const | निर्दिष्ट संसाधन को स्ट्रिंग के रूप में डाउनलोड करता है। |
| [String](../../system/string/) [DownloadString](./downloadstring/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) const | निर्दिष्ट संसाधन को स्ट्रिंग के रूप में डाउनलोड करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| **bool** [get_DesignMode](../../system.componentmodel/component/get_designmode/)() | जाँचता है कि घटक डिजाइन मोड में है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() const | स्ट्रिंग्स को डाउनलोड या अपलोड करने के लिए उपयोग होने वाले एन्कोडिंग प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपवर्गों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और उपवर्गों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस के माध्यम से वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंटर को घटाता है। |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | स्ट्रिंग्स को डाउनलोड या अपलोड करने के लिए उपयोग होने वाले एन्कोडिंग को सेट करता है। |
| void [set_UseDefaultCredentials](./set_usedefaultcredentials/)(**bool**) | कार्यान्वित नहीं किया गया। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंटर को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंटर को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंटर को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [WebClient](./webclient/)() | एक नया उदाहरण बनाता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
|  [~WebClient](./~webclient/)() | वर्तमान उदाहरण को नष्ट करता है। |

## संबंधित देखें

* क्लास [Component](../../system.componentmodel/component/)
* नेमस्पेस [System::Net](../)
* लाइब्रेरी [Aspose.Slides](../../)
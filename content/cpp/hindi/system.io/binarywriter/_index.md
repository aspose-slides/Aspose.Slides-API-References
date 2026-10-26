---
title: BinaryWriter
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: "प्रिमिटिव प्रकारों के मानों को बाइट स्ट्रीम में लिखने वाले राइटर का प्रतिनिधित्व करता है। इस वर्ग की ऑब्जेक्ट्स को केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही अलोकेट किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन दोष हो सकते हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में घेरें और इस पॉइंटर को आर्ग्यूमेंट के रूप में फ़ंक्शन में पास करें।"
type: docs
weight: 105
url: /hi/system.io/binarywriter/
---
## BinaryWriter वर्ग

प्रिमिटिव प्रकारों के मानों को बाइट स्ट्रीम में लिखने वाले राइटर का प्रतिनिधित्व करता है। इस वर्ग की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही अलोकेट किया जाना चाहिए। इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या ऐसर्शन दोष हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में घेरें और इस पॉइंटर को फ़ंक्शन के आर्ग्यूमेंट के रूप में पास करें।

```cpp
class BinaryWriter : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | निर्दिष्ट एन्कोडिंग का उपयोग करके निर्दिष्ट स्ट्रीम में डेटा लिखने वाले [BinaryWriter](./) वर्ग की एक उदाहरण बनाता है। |
| void [Close](./close/)() | वर्तमान [BinaryWriter](./) ऑब्जेक्ट और अंतर्निहित आउटपुट स्ट्रीम को बंद करता है। |
| void [Dispose](./dispose/)() override | वर्तमान ऑब्जेक्ट द्वारा उपयोग किए गए सभी संसाधनों को जारी करता है और undelying स्ट्रीम को बंद करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सिमेंटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजन के लिए। |
| void [Flush](./flush/)() | आउटपुट स्ट्रीम को फ्लश करता है। |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | आउटपुट स्ट्रीम को वापस करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार की एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | एसेग्नमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए स्ट्रीम की स्थिति सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को डिक्रीमेंट करता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को इन्क्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को डिक्रीमेंट करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [Write](./write/)(**uint8_t**) | निर्दिष्ट अनसाइनड 8-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | निर्दिष्ट बाइट ऐरे से निर्दिष्ट बाइट रेंज को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | निर्दिष्ट कैरेक्टर ऐरे से निर्दिष्ट UTF-16 कैरेक्टर रेंज को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**bool**) | यदि **value** 'true' है तो मान 0 और यदि **value** 'false' है तो मान 1 के साथ एक बाइट को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(char16_t) | निर्दिष्ट 16-बिट वाइड कैरेक्टर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**int16_t**) | निर्दिष्ट 16-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(int) | निर्दिष्ट 32-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**int64_t**) | निर्दिष्ट 64-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**uint16_t**) | निर्दिष्ट अनसाइनड 16-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**uint32_t**) | निर्दिष्ट अनसाइनड 32-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**uint64_t**) | निर्दिष्ट अनसाइनड 64-बिट इंटेजर मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**float**) | निर्दिष्ट सिंगल-प्रिसीजन फ्लोटिंग पॉइंट मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(**double**) | निर्दिष्ट डबल-प्रिसीजन फ्लोटिंग पॉइंट मान को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | [Decimal](../../system/decimal/) मान का बाइट प्रतिनिधित्व आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | वर्तमान एन्कोडिंग में लंबाई-प्रिफ़़िक्स्ड स्ट्रिंग को आउटपुट स्ट्रीम में लिखता है। |
| virtual void [Write](./write/)(const char_t *) | वर्तमान एन्कोडिंग में लंबाई-प्रिफ़़िक्स्ड स्ट्रिंग को आउटपुट स्ट्रीम में लिखता है। |
|  [~BinaryWriter](./~binarywriter/)() | डिस्ट्रक्टर। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## देखें

* वर्ग [IDisposable](../../system/idisposable/)
* नामस्थान [System::IO](../)
* लाइब्रेरी [Aspose.Slides](../../)
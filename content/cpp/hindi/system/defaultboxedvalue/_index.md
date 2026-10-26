---
title: DefaultBoxedValue
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "BoxedValue क्लास कार्यान्वयन। सामान्य कोड को दोहराए बिना BoxingValue विशेषीकरणों को घोषित करने की अनुमति देता है। इस क्लास की वस्तुएँ केवल System::MakeObject() फ़ंक्शन का उपयोग करके ही आवंटित की जानी चाहिए। इस प्रकार का उदाहरण स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या दावे (assertion) त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन में तर्क के रूप में पास करें।"
type: docs
weight: 274
url: /hi/system/defaultboxedvalue/
---
## DefaultBoxedValue क्लास

[BoxedValue](../boxedvalue/) क्लास कार्यान्वयन। BoxingValue विशेषीकरणों को सामान्य कोड की प्रतिलिपि बनाए बिना घोषित करने की अनुमति देता है। इस क्लास की वस्तुएँ केवल [System::MakeObject()](../makeobject/) फ़ंक्शन का उपयोग करके संग्रहित की जानी चाहिए। इस प्रकार का उदाहरण कभी भी स्टैक पर या ऑपरेटर new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या दावा त्रुटियाँ उत्पन्न होंगी। इस क्लास को हमेशा [System::SmartPtr](../smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन में तर्क के रूप में पास करें।

```cpp
template<class T>class DefaultBoxedValue : public System::Object
```

## विधियाँ

| Method | Description |
| --- | --- |
|  [DefaultBoxedValue](./defaultboxedvalue/)(const T\&) | निर्दिष्ट मान का प्रतिनिधित्व करने वाले [DefaultBoxedValue](./) क्लास का नया उदाहरण बनाता है। |
| **bool** [Equals](./equals/)([ptr](../object/ptr/)) override | वर्तमान और निर्दिष्ट वस्तुओं द्वारा प्रतिनिधित्व किए गए बॉक्स्ड मानों की समानता निर्धारित करता है। |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | वस्तु से संबंधित रेफरेंस काउंटर डेटा संरचना को प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const override | वर्तमान वस्तु के लिए हैश कोड लौटाता है। |
| const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const override | वस्तु का वास्तविक प्रकार प्राप्त करता है। |
| **bool** [is](./is/)() const | निर्धारित करता है कि वर्तमान वस्तु द्वारा प्रतिनिधित्व किया गया बॉक्स्ड मान का प्रकार **V** है या नहीं। |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार के उदाहरण का प्रतिनिधित्व करती है या नहीं। C# 'is' ऑपरेटर के समान। |
| void [Lock](../object/lock/)() | C# lock() स्टेटमेंट के लॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंत्री वस्तु का उपयोग करें। |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../object/memberwiseclone/) मेथड का समान। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../object/object/)([Object](../object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया वस्तु प्रारंभ करता है और उपवर्गों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया वस्तु प्रारंभ करता है और उपवर्गों के कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | वस्तुओं की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | nullptr के साथ वैल्यू टाइप वस्तु की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | स्ट्रिंग्स के मामले के लिए [Object::ReferenceEquals](../object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट को घटाता है। |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) |  n'th टेम्पलेट तर्क को एक कमजोर पॉइंटर (साझा के बजाय) सेट करता है। कंटेनरों में पॉइंटर को कमजोर मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे बुलाया न जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे बुलाया न जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| [String](../string/) [ToString](./tostring/)() const override | बॉक्स्ड मान के स्ट्रिंग प्रतिनिधित्व को लौटाता है। |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) संरचना को लागू करता है। |
| const T\& [unbox](./unbox/)() const | बॉक्स्ड मान को अनबॉक्स करता है। |
| void [Unlock](../object/unlock/)() | C# lock() स्टेटमेंट के अनलॉक को लागू करता है। सीधे कॉल करें या [LockContext](../lockcontext/) सेंत्री वस्तु का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | कमजोर रेफ़रेंस काउंट को बढ़ाता है। सीधे बुलाया न जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../object/weakrefremoved/)() | कमजोर रेफ़रेंस काउंट को घटाता है। सीधे बुलाया न जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [Object](../object/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
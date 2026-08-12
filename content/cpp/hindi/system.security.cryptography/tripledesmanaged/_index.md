---
title: TripleDESManaged
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Managed TripleDES कार्यान्वयन। केवल ECB और CFB मोडों को None पैडिंग के साथ और CBC मोड को None, Zeros और PKCS7 पैडिंग के साथ समर्थन करता है। इस वर्ग की वस्तुओं को केवल System::MakeObject() फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन त्रुटियाँ हो सकती हैं। हमेशा इस वर्ग को System::SmartPtr पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके फ़ंक्शनों को आर्ग्यूमेंट के रूप में पास करें।"
type: docs
weight: 690
url: /hi/system.security.cryptography/tripledesmanaged/
---
## TripleDESManaged वर्ग

Managed [TripleDES](../tripledes/) implementation. Only supports ECB and CFB modes with None padding and CBC mode with None, Zeros and PKCS7 paddings. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class TripleDESManaged : public System::Security::Cryptography::TripleDES
```
## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [SharedPtr](../../system/sharedptr/)\<[SymmetricAlgorithm](../symmetricalgorithm/)\> [Create](../symmetricalgorithm/create/)(const [String](../../system/string/)\&) | एल्गोरिदम का उदाहरण बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | स्पष्ट पैरामीटर के साथ डिक्रिप्टर वस्तु बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)() | एल्गोरिदम वस्तु द्वारा परिभाषित पैरामीटर के साथ डिक्रिप्टर वस्तु बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateDecryptor](./createdecryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एल्गोरिदम वस्तु द्वारा परिभाषित पैरामीटर के साथ डिक्रिप्टर वस्तु बनाता है। |
| [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | स्पष्ट पैरामीटर के साथ एनक्रिप्टर वस्तु बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)() | एल्गोरिदम वस्तु द्वारा परिभाषित पैरामीटर के साथ एनक्रिप्टर वस्तु बनाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICryptoTransform](../icryptotransform/)\> [CreateEncryptor](./createencryptor/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | एल्गोरिदम वस्तु द्वारा परिभाषित पैरामीटर के साथ एनक्रिप्टर वस्तु बनाता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | सिर्फ आंतरिक उपयोग के लिए। |
| void [GenerateIV](./generateiv/)() override | रैंडम प्रारंभिक मान बनाता है और इसे एल्गोरिदम के आंतरिक भाग में संग्रहीत करता है। |
| void [GenerateKey](./generatekey/)() override | रैंडम कुंजी बनाता है और इसे एल्गोरिदम के आंतरिक भाग में संग्रहीत करता है। |
| virtual int [get_BlockSize](../symmetricalgorithm/get_blocksize/)() | क्रिप्टोग्राफ़िक ऑपरेशन का ब्लॉक आकार प्राप्त करता है। |
| virtual int [get_FeedbackSize](../symmetricalgorithm/get_feedbacksize/)() | क्रिप्टोग्राफ़िक ऑपरेशन का फ़ीडबैक आकार प्राप्त करता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_IV](../symmetricalgorithm/get_iv/)() | क्रिप्टोग्राफ़िक ऑपरेशन का प्रारंभिक मान प्राप्त करता है। यदि अभी तक नहीं बनाया गया है तो नया बनाता है। |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_Key](../symmetricalgorithm/get_key/)() | क्रिप्टोग्राफ़िक ऑपरेशन की कुंजी प्राप्त करता है। यदि अभी तक नहीं बनाया गया है तो नया बनाता है। |
| virtual int [get_KeySize](../symmetricalgorithm/get_keysize/)() | क्रिप्टोग्राफ़िक ऑपरेशन की कुंजी आकार प्राप्त करता है। |
| virtual [CipherMode](../ciphermode/) [get_Mode](../symmetricalgorithm/get_mode/)() | क्रिप्टोग्राफ़िक ऑपरेशन का मोड प्राप्त करता है। |
| virtual [PaddingMode](../paddingmode/) [get_Padding](../symmetricalgorithm/get_padding/)() | क्रिप्टोग्राफ़िक ऑपरेशन का पैडिंग प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | वस्तु से जुड़ा रेफ़रेंस काउंटर डाटा संरचना प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समान रूप। कस्टम वस्तुओं की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | वस्तु का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समान रूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि वस्तु targetType द्वारा वर्णित प्रकार की इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समान रूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट का लॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समान रूप। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | वस्तु बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नई वस्तु को प्रारंभ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप वस्तु की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| virtual void [set_BlockSize](../symmetricalgorithm/set_blocksize/)(int) | क्रिप्टोग्राफ़िक ऑपरेशन का ब्लॉक आकार सेट करता है। |
| virtual void [set_FeedbackSize](../symmetricalgorithm/set_feedbacksize/)(int) | क्रिप्टोग्राफ़िक ऑपरेशन का फ़ीडबैक आकार सेट करता है। |
| virtual void [set_IV](../symmetricalgorithm/set_iv/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | क्रिप्टोग्राफ़िक ऑपरेशन का प्रारंभिक मान सेट करता है। |
| virtual void [set_Key](../symmetricalgorithm/set_key/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | क्रिप्टोग्राफ़िक ऑपरेशन की कुंजी सेट करता है। |
| virtual void [set_KeySize](../symmetricalgorithm/set_keysize/)(int) | क्रिप्टोग्राफ़िक ऑपरेशन की कुंजी आकार सेट करता है। |
| virtual void [set_Mode](../symmetricalgorithm/set_mode/)([CipherMode](../ciphermode/)) | क्रिप्टोग्राफ़िक ऑपरेशन का मोड सेट करता है। |
| virtual void [set_Padding](../symmetricalgorithm/set_padding/)([PaddingMode](../paddingmode/)) | क्रिप्टोग्राफ़िक ऑपरेशन का पैडिंग सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट तर्क को एक weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर को weak मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान रूप। कस्टम वस्तुओं को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्रि ऑब्जेक्ट का उपयोग करें। |
| **bool** [ValidKeySize](../symmetricalgorithm/validkeysize/)(int) | जाँचता है कि कुंजी आकार वैध है या नहीं। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | वस्तु को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## देखें

* क्लास [TripleDES](../tripledes/)
* नेमस्पेस [System::Security::Cryptography](../)
* लाइब्रेरी [Aspose.Slides](../../)
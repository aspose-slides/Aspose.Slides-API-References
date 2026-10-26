---
title: SortedDictionaryPtr
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक्सेस ऑपरेटरों के साथ सॉर्टेड डिक्शनरी पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट के हटाने को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को वैल्यू या कॉन्स्ट रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 534
url: /hi/system.collections.generic/sorteddictionaryptr/
---
## SortedDictionaryPtr क्लास

एक्सेस ऑपरेटर्स के साथ सॉर्टेड डिक्शनरी पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट के हटाने को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर एलोकेट किया जाना चाहिए और फ़ंक्शन्स को वैल्यू या कॉन्स्ट रेफ़रेंस द्वारा पास किया जाना चाहिए।

```cpp
template<typename T,typename V>class SortedDictionaryPtr : public System::SmartPtr<SortedDictionary<T, V>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसके स्वयं के टाइप में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस टाइप में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेरिव्ड टाइप में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेरिव्ड टाइप में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक अंतर्निहित संग्रह की [cbegin()](../../system/smartptr/cbegin/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक अंतर्निहित संग्रह की [cend()](../../system/smartptr/cend/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [cend()](../../system/smartptr/cend/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग टाइप में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग टाइप में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| auto [end](../../system/smartptr/end/)() const | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) मेथड के लिये एक्सेसर। केवल तब ही संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड के साथ स्पेशलाइज़ेशन टाइप हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह मानता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | रेफ़रेंस किए गए ऑब्जेक्ट के लिए मौजूद साझा पॉइंटर्स की संख्या प्राप्त करता है, जिसमें वर्तमान पॉइंटर भी शामिल है। यह मानता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंटेड ऑब्जेक्ट पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में रेफ़रेंस किया गया ऑब्जेक्ट प्राप्त करता है (यदि कोई है) या एक्सेप्शन उछालता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई है) या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | रेफ़रेंस किया गया ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई है) या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंटेड ऑब्जेक्ट निर्दिष्ट टाइप या उसके चाइल्ड टाइप का है या नहीं। C# 'is' सिमैंटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट को पॉइंट कर रहा है जो स्वामित्व में नहीं है (एलियासिंग कंस्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है या नहीं। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर वीक़ मोड में है या नहीं। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह मानता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | रेफ़रेंस किए गए ऑब्जेक्ट के मेंबर्स तक पहुँच की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिये कम-तुलना सेमेंटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिये कम-तुलना सेमेंटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक टाइप रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | रॉ पॉइंटर को [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर वैल्यू को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि पॉइंटर nullptr की ओर इशारा कर रहा है या नहीं। |
| V\& [operator[]](./operator[]/)(const T\&) const | एक्सेसर फ़ंक्शन। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से एलियासिंग (एलियासिंग कंस्ट्रक्टर द्वारा बनाया गया) हटाता है, यह सुनिश्चित करता है कि वह वही ऑब्जेक्ट मैनेज (यदि साझा) या ट्रैक (यदि वीक़) करता है जिसे वह पॉइंट कर रहा है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करने वाला बनाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। रेफ़रेंस किए गए ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि कोई है) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या रॉ पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | कॉपी कंस्ट्रक्ट करके [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इशारा करते हैं। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | कॉपी कंस्ट्रक्ट करके [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इशारा करते हैं। यदि अनुमति है तो टाइप रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | मूव कंस्ट्रक्ट करके [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। प्रभावी रूप से दो पॉइंटर को स्वैप करता है, यदि दोनों का मोड समान हो। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | एक अलग टाइप के नए एरे बनाकर रेफ़रेंस किए गए एरे का टाइप बदलता है। यह उपयोगी है जब C# में ऐसा एरे टाइप कास्ट हो जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे इनिशियलाइज़ करता है। कुछ C# कोड कंस्ट्रक्ट्स को ट्रांसलेट करने के लिये उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक वैल्यू के साथ ओनरशिप जानकारी साझा करता है, परन्तु एक अलग और अनमैनेज्ड पॉइंटर p रखता है। |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)() | null पॉइंटर बनाता है। |
|  [SortedDictionaryPtr](./sorteddictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedDictionary](../sorteddictionary/)\<T, V\>\>\&) | निर्दिष्ट सॉर्टेड डिक्शनरी की ओर इशारा करने वाला पॉइंटर बनाता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग टाइप में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर टाइप को [Object](../../system/object/) की ओर पॉइंट करने वाले टाइप में बदलता है। Pointee_ टाइप को पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ टाइप के लिये [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो तो पॉइंटेड ऑब्जेक्ट की रेफ़रेंस काउंट घटाता है और ऑब्जेक्ट को हटाता है। |

## देखें भी

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
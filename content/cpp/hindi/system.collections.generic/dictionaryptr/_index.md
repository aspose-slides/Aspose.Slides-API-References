---
title: DictionaryPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑपरेटर ओवरलोड्स के साथ डिक्शनरी पॉइंटर क्लास। यह प्रकार अन्य ऑब्जेक्ट की डिलीशन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 170
url: /hi/system.collections.generic/dictionaryptr/
---
## DictionaryPtr क्लास

[Dictionary](../dictionary/) पॉइंटर क्लास जिसमें ऑपरेटर ओवरलोड्स हैं। यह प्रकार अन्य वस्तु की डिलीशन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन्स को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।

```cpp
template<typename T,typename V>class DictionaryPtr : public System::SmartPtr<Dictionary<T, V>>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | कुंजी प्रकार। |
| V | मान प्रकार। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाले विशेषीकरण प्रकार हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसी प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक अंतर्निहित संग्रह की [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक अंतर्निहित संग्रह की [cend()](../../system/smartptr/cend/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [cend()](../../system/smartptr/cend/) मेथड वाले विशेषीकरण प्रकार हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटर को विभिन्न प्रकार में कास्ट करता है, पॉइंट किए गए वस्तु पर const_cast का उपयोग करके। |
|  [DictionaryPtr](./dictionaryptr/)() | नल पॉइंटर को प्रारंभ करता है। |
|  [DictionaryPtr](./dictionaryptr/)(const [SharedPtr](../../system/sharedptr/)\<[Dictionary](../dictionary/)\<T, V\>\>\&) | पॉइंटर प्रकार को परिवर्तित करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटर को विभिन्न प्रकार में कास्ट करता है, पॉइंट किए गए वस्तु पर dynamic_cast का उपयोग करके। |
| auto [end](../../system/smartptr/end/)() | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [end](../../system/smartptr/end/)() const | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाले विशेषीकरण प्रकार हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंट किए गए वस्तु को प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंट किए गए वस्तु को प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित वस्तु के लिए मौजूदा साझा पॉइंटर्स की संख्या प्राप्त करता है, जिसमें वर्तमान पॉइंटर भी शामिल है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंट किए गए वस्तु पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित वस्तु प्राप्त करता है (यदि मौजूद हो) या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंट किए गए वस्तु को प्राप्त करता है (यदि मौजूद हो) या nullptr। यह [get()](../../system/smartptr/get/) के समान है। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित वस्तु को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंट किए गए वस्तु को प्राप्त करता है (यदि मौजूद हो) या nullptr। यह [get()](../../system/smartptr/get/) के समान है। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | पॉइंट किए गए वस्तु के विशिष्ट प्रकार या उसके चाइल्ड प्रकार के होने की जाँच करता है। C# 'is' सेमांटिक्स का अनुसरण करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य वस्तु की ओर इशारा कर रहा है जो मालिकाना (aliasing कंस्ट्रक्टर द्वारा बनाया गया) नहीं है। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर कमजोर मोड में है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंट किए गए वस्तु का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित वस्तु के सदस्य तक पहुँचने की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमांटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) वस्तु को मूव-ऐसाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-ऐसाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-ऐसाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) वस्तु को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि पॉइंटर nullptr की ओर इशारा कर रहा है। |
| V\& [operator[]](./operator[]/)(const X\&) const | की प्रकार रूपांतरण के साथ काम करने के लिए एक्सेस ऑपरेटर। |
| V\& [operator[]](./operator[]/)(const T\&) const | एक्सेस ऑपरेटर। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कंस्ट्रक्टर द्वारा बनाया गया) हटाता है, सुनिश्चित करता है कि यह वही वस्तु प्रबंधित (यदि साझा) या ट्रैक (यदि कमजोर) करता है जिसपर यह इशारा करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंट किए गए वस्तु को सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करने बनाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित वस्तु के रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंट किए गए वस्तु (यदि मौजूद हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट वस्तु की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु की कॉपी कंस्ट्रक्ट करता है। दोनो पॉइंटर बाद में उसी वस्तु की ओर इशारा करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु की कॉपी कंस्ट्रक्ट करता है। दोनो पॉइंटर बाद में उसी वस्तु की ओर इशारा करेंगे। यदि अनुमत हो तो प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु की मूव कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों समान मोड में हैं तो दो पॉइंटरों का स्वैप करता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित ऐरे के प्रकार को विभिन्न प्रकार के नये ऐरे बनाकर परिवर्तित करता है। उपयोगी जब C# में ऐरे टाइप कास्ट मौजूद हो जो C++ में असमर्थित है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली ऐरे को प्रारंभ करता है। कुछ C# कोड निर्माण को अनुवाद करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटर को विभिन्न प्रकार में कास्ट करता है, पॉइंट किए गए वस्तु पर static_cast का उपयोग करके। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में परिवर्तित करता है। Pointee_ प्रकार के संपूर्ण होने की आवश्यकता नहीं होती। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) वस्तु प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) वस्तु को नष्ट करता है। यदि आवश्यक हो, पॉइंट किए गए वस्तु के रेफ़रेंस काउंटर को घटाता है और वस्तु को हटाता है। |

## संबंधित देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
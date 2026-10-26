---
title: StackPtr
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: स्टैक पॉइंटर। यह प्रकार अन्य वस्तु के विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान द्वारा या कॉन्स्ट रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 612
url: /hi/system.collections.generic/stackptr/
---
## StackPtr क्लास

[Stack](../stack/) पॉइंटर। यह प्रकार अन्य वस्तु की विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मूल्य द्वारा या कॉन्स्ट रेफ़रेंस द्वारा पास किया जाना चाहिए।
```cpp
template<typename T>class StackPtr : public System::SmartPtr<Stack<T>>
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | तत्व प्रकार। |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | अंडरलाइंग संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| auto [begin](../../system/smartptr/begin/)() const | अंडरलाइंग संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसी प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को बेस टाइप में static_cast का उपयोग करके कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को डेराइव्ड टाइप में dynamic_cast के द्वारा कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को डेराइव्ड टाइप में dynamic_cast के द्वारा कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | अंडरलाइंग संग्रह के [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [cbegin()](../../system/smartptr/cbegin/) मेथड हो। |
| auto [cend](../../system/smartptr/cend/)() const | अंडरलाइंग संग्रह के [cend()](../../system/smartptr/cend/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [cend()](../../system/smartptr/cend/) मेथड हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड वस्तु पर const_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड वस्तु पर dynamic_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | अंडरलाइंग संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [end()](../../system/smartptr/end/) मेथड हो। |
| auto [end](../../system/smartptr/end/)() const | अंडरलाइंग संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगामी। केवल तभी संकलित होता है जब SmartPtr_ एक विशेषीकरण प्रकार हो और उसमें [end()](../../system/smartptr/end/) मेथड हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड वस्तु प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड वस्तु प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित वस्तु के लिए मौजूद साझा पॉइंटर्स की संख्या प्राप्त करता है, जिसमें वर्तमान भी शामिल है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंटेड वस्तु पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित वस्तु (यदि कोई हो) प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड वस्तु (यदि कोई हो) या nullptr प्राप्त करता है। समान है [get()](../../system/smartptr/get/) के। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित वस्तु प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड वस्तु (यदि कोई हो) या nullptr प्राप्त करता है। समान है [get()](../../system/smartptr/get/) के। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंटेड वस्तु विशिष्ट प्रकार या उसकी चाइल्ड टाइप का है। C# 'is' सेमांटिक्स का अनुसरण करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य वस्तु की ओर इंगित कर रहा है जो स्वामित्व वाली नहीं है (aliasing कंस्ट्रक्टर द्वारा बनाई गई)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर weak मोड में है। |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड वस्तु का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित वस्तु के सदस्यों तक पहुँच प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमेंटिक प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमेंटिक प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) वस्तु को मूव-असाइन करता है। x उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-असाइन करता है। आवश्यक प्रकार परिवर्तनों को करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) वस्तु को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr पर सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि पॉइंटर nullptr की ओर इशारा करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कंस्ट्रक्टर द्वारा बनाई गई) हटाता है, सुनिश्चित करता है कि वह वही वस्तु प्रबंधित (यदि shared) या ट्रैक (यदि weak) करे जिसके पास वह इंगित करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड वस्तु सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इंगित करता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित वस्तु की रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड वस्तु (यदि कोई हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट वस्तु की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में उसी वस्तु की ओर इशारा करते हैं। |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में उसी वस्तु की ओर इशारा करते हैं। यदि अनुमति हो तो प्रकार रूपांतरण करता है। |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को मूव-कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों समान मोड में हैं तो दो पॉइंटर स्वैप करता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | विभिन्न प्रकार के नए एरे बनाकर संदर्भित एरे के प्रकार को बदलता है। उपयोगी जब C# में ऐसा एरे टाइप कास्ट हो जो C++ में असमर्थित है। |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को इनिशियलाइज़ करता है। कुछ C# कोड संरचनाओं के अनुवाद में उपयोग होता है। |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, परंतु एक असंबद्ध और अनमैनेज्ड पॉइंटर p रखता है। |
| [StackPtr](./stackptr/)() | null पॉइंटर बनाता है। |
| [StackPtr](./stackptr/)(const [SharedPtr](../../system/sharedptr/)\<[Stack](../stack/)\<T\>\>\&) | विशिष्ट स्टैक को संदर्भित करने वाला पॉइंटर बनाता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड वस्तु पर static_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) वस्तु प्राप्त करने का शॉर्टकट। |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) वस्तु को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड वस्तु का रेफ़रेंस काउंटर घटाता है और वस्तु को हटाता है। |

## देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
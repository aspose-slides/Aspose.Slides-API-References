---
title: SortedSetPtr
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: SortedSet संदर्भों को रखने के लिए पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट की हटाने को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में या तो वैल्यू द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 586
url: /hi/system.collections.generic/sortedsetptr/
---
## SortedSetPtr वर्ग

Pointer to keep [SortedSet](../sortedset/) references. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<typename T>class SortedSetPtr : public System::SmartPtr<SortedSet<T>>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) विधि वाली विशेषीकरण प्रकार हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक अंतर्निहित संग्रह की [begin()](../../system/smartptr/begin/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) विधि वाली विशेषीकरण प्रकार हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में बदलता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में बदलता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में बदलता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में बदलता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक अंतर्निहित संग्रह की [cbegin()](../../system/smartptr/cbegin/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) विधि वाली विशेषीकरण प्रकार हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक अंतर्निहित संग्रह की [cend()](../../system/smartptr/cend/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [cend()](../../system/smartptr/cend/) विधि वाली विशेषीकरण प्रकार हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में बदलता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में बदलता है। |
| auto [end](../../system/smartptr/end/)() | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) विधि वाली विशेषीकरण प्रकार हो। |
| auto [end](../../system/smartptr/end/)() const | एक अंतर्निहित संग्रह की [end()](../../system/smartptr/end/) विधि का अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) विधि वाली विशेषीकरण प्रकार हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह सत्यापित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूद साझा पॉइंटरों की संख्या प्राप्त करता है, जिसमें वर्तमान भी शामिल है। यह सत्यापित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंटेड ऑब्जेक्ट पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr। यह [get()](../../system/smartptr/get/) के समान है। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | सन्दर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr। यह [get()](../../system/smartptr/get/) के समान है। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि पॉइंटेड ऑब्जेक्ट विशिष्ट प्रकार का है या उसका चाइल्ड प्रकार। C# के 'is' सेमैंटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँच करता है कि पॉइंटर किसी अन्य ऑब्जेक्ट की ओर इशारा कर रहा है बनाम मालिक (जिसे aliasing कंस्ट्रक्टर द्वारा बनाया गया है)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँच करता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँच करता है कि पॉइंटर कमजोर मोड में है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँच करता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँच करता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का संदर्भ प्राप्त करता है। यह सत्यापित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | सन्दर्भित ऑब्जेक्ट के सदस्य तक पहुँचने की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) वर्ग के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) वर्ग के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपान्तरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मूल्य को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँच करता है कि पॉइंटर nullptr की ओर इशारा कर रहा है। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से aliasing (जो aliasing कंस्ट्रक्टर द्वारा बनाया गया) को हटाता है, सुनिश्चित करता है कि यह (यदि साझा हो) प्रबंधित करता है या (यदि कमजोर हो) वही ऑब्जेक्ट ट्रैक करता है जिसकी ओर यह इशारा करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करने के लिये बनाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह सन्दर्भित ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() विधि को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट की कॉपी कन्स्ट्रक्शन करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट की कॉपी कन्स्ट्रक्शन करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। यदि अनुमति हो तो प्रकार रूपान्तरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट की मूव कन्स्ट्रक्शन करता है। प्रभावी रूप से, दो पॉइंटर्स का अदला-बदली करता है, यदि दोनों समान मोड के हों। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | विभिन्न प्रकार का नया एरे बनाकर संदर्भित एरे के प्रकार को बदलता है। यदि C# में एरे टाइप कास्ट है जो C++ में समर्थित नहीं है, तो यह उपयोगी है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को प्रारंभ करता है। कुछ C# कोड संरचनाओं के अनुवाद में उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारम्भिक मान के साथ स्वामित्व जानकारी साझा करता है, परन्तु एक असंबद्ध और प्रबंधित न किया गया पॉइंटर p रखता है। |
|  [SortedSetPtr](./sortedsetptr/)() | null-pointer कन्स्ट्रक्टर। |
|  [SortedSetPtr](./sortedsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[SortedSet](../sortedset/)\<T\>\>\&) | कॉपी कन्स्ट्रक्टर। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में बदलता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं होती। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड ऑब्जेक्ट की रेफ़रेंस काउंटर को घटाता है और ऑब्जेक्ट डिलीट करता है। |

## See Also

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
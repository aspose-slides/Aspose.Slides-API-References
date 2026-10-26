---
title: HashSetPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: HashSet संदर्भों को रखने के लिये पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट की हटाने को प्रबंधित करने के लिये एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 235
url: /hi/system.collections.generic/hashsetptr/
---
## HashSetPtr क्लास

पॉइंटर [HashSet](../hashset/) संदर्भों को रखने के लिये। यह प्रकार अन्य वस्तु की हटाने को प्रबंधित करने के लिये एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या const रेफरेंस द्वारा पास किया जाना चाहिए।

```cpp
template<typename T>class HashSetPtr : public System::SmartPtr<HashSet<T>>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [begin()](../../system/smartptr/begin/) मेथड है। |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [begin()](../../system/smartptr/begin/) मेथड है। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कैस्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कैस्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कैस्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कैस्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [cbegin()](../../system/smartptr/cbegin/) मेथड है। |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [cend()](../../system/smartptr/cend/) मेथड है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कैस्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कैस्ट करता है। |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [end()](../../system/smartptr/end/) मेथड है। |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) मेथड के लिए अभिगमनकर्ता एक अधीनस्थ संग्रह का। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार है जिसमें [end()](../../system/smartptr/end/) मेथड है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंट किए गए ऑब्जेक्ट को प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंट किए गए ऑब्जेक्ट को प्राप्त करता है, परन्तु यह सत्यापित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौज़ूद साझा पॉइंटर्स की संख्या प्राप्त करता है, वर्तमान सहित। यह सत्यापित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंट किए गए ऑब्जेक्ट पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि कोई हो) प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंट किए गए ऑब्जेक्ट को (यदि कोई हो) प्राप्त करता है या nullptr लौटाता है। समान है [get()](../../system/smartptr/get/) के। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंट किए गए ऑब्जेक्ट को (यदि कोई हो) प्राप्त करता है या nullptr लौटाता है। समान है [get()](../../system/smartptr/get/) के। |
|  [HashSetPtr](./hashsetptr/)() | नल पॉइंटर कन्स्ट्रक्टर। |
|  [HashSetPtr](./hashsetptr/)(const [SharedPtr](../../system/sharedptr/)\<[HashSet](../hashset/)\<T\>\>\&) | कॉपी कन्स्ट्रक्टर। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंट किया गया ऑब्जेक्ट विशिष्ट प्रकार का है या उसका चाइल्ड प्रकार। C# 'is' सेमांटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट को पॉइंट कर रहा है बनिस्बत उसके स्वामित्व वाले (एक aliasing कन्स्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर वीक मोड में है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर नल नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर नल है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंट किए गए ऑब्जेक्ट का रेफरेंस प्राप्त करता है। यह सत्यापित करता है कि पॉइंटर नल नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्यों तक पहुँच प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिये लेस-तुलना सेमांटिक प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिये लेस-तुलना सेमांटिक प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को रॉ पॉइंटर असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर वैल्यू को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि पॉइंटर nullptr को पॉइंट करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कन्स्ट्रक्टर द्वारा बनाया गया) को हटाता है, सुनिश्चित करता है कि यह (यदि साझा है) प्रबंधित करे या (यदि वीक है) ट्रैक करे वही ऑब्जेक्ट जिसे यह पॉइंट करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंट किए गए ऑब्जेक्ट को सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इंगित करता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। इससे संदर्भित ऑब्जेक्ट की रेफरेंस काउंट बदल सकती है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंट किए गए ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) बनाता है जो निर्दिष्ट ऑब्जेक्ट की ओर इशारा करता है, या रॉ पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कन्स्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में उसी ऑब्जेक्ट को इंगित करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कन्स्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में उसी ऑब्जेक्ट को इंगित करेंगे। अनुमति मिलने पर प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव कन्स्ट्रक्ट करता है। प्रभावी रूप से, दो पॉइंटर्स को स्वैप करता है यदि दोनों समान मोड में हैं। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित ऐरे का प्रकार बदलता है विभिन्न प्रकार के नए ऐरे को बनाकर। उपयोगी जब C# में ऐरे टाइप कास्ट हो जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली ऐरे को प्रारंभ करता है। कुछ C# कोड संरचनाओं को अनुवादित करने के लिये उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, परन्तु एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कैस्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में परिवर्तित करता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट को Pointee_ प्रकार के लिये प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, पॉइंट किए गए ऑब्जेक्ट की रेफरेंस काउंटर घटाता है और ऑब्जेक्ट को हटाता है। |

## देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: ListPtr
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक्सेस ऑपरेटरों के साथ सूची पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट के विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 456
url: /hi/system.collections.generic/listptr/
---
## ListPtr क्लास

[List](../list/) पॉइंटर जिसमें एक्सेस ऑपरेटर होते हैं। यह प्रकार अन्य ऑब्जेक्ट के विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों में मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक्सेसर [begin()](../../system/smartptr/begin/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../../system/smartptr/begin/) विधि हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक्सेसर [begin()](../../system/smartptr/begin/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../../system/smartptr/begin/) विधि हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक्सेसर [cbegin()](../../system/smartptr/cbegin/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cbegin()](../../system/smartptr/cbegin/) विधि हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक्सेसर [cend()](../../system/smartptr/cend/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cend()](../../system/smartptr/cend/) विधि हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | एक्सेसर [end()](../../system/smartptr/end/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../../system/smartptr/end/) विधि हो। |
| auto [end](../../system/smartptr/end/)() const | एक्सेसर [end()](../../system/smartptr/end/) विधि के लिए एक अधीनस्थ संग्रह का। केवल तब कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../../system/smartptr/end/) विधि हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह दावे करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट पर मौजूद साझा पॉइंटर्स की संख्या प्राप्त करता है, वर्तमान पॉइंटर सहित। यह दावे करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) को पॉइंटेड ऑब्जेक्ट पर कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंटेड ऑब्जेक्ट विशिष्ट प्रकार का है या उसका चाइल्ड प्रकार। C# 'is' सेमांटिक का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट की ओर इशारा कर रहा है जो स्वामित्व में नहीं है (एलियासिंग कन्स्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है या नहीं। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर कमजोर मोड में है या नहीं। |
|  [ListPtr](./listptr/)(std::nullptr_t) | null-pointer को आरंभ करता है। |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | पॉइंटर को निर्दिष्ट सूची में आरंभ करता है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह दावे करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्य तक पहुँचने की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमेंटिक प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए less-compare सेमेंटिक प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग नहीं योग्य। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि [List](../list/) पॉइंटर null है या नहीं। |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | एक्सेसर। |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | एक्सेसर। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से एलियासिंग (एलियासिंग कन्स्ट्रक्टर द्वारा बनाया गया) हटाता है, यह सुनिश्चित करता है कि यह (यदि साझा है) प्रबंधित करता है या (यदि कमजोर है) उसी ऑब्जेक्ट को ट्रैक करता है जिस पर यह इशारा करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इंगित करता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट की रेफ़रेंस काउण्ट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() विधि को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। यदि अनुमति हो तो प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों समान मोड में हों तो दो पॉइंटरों की अदला-बदली करता है। कॉल के बाद x उपयोग नहीं योग्य हो सकता है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित एरे के प्रकार को विभिन्न प्रकार की नई एरे बनाकर परिवर्तित करता है। उपयोगी जब C# में एरे टाइप कास्ट हो जो C++ में असमर्थित है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को आरंभ करता है। कुछ C# कोड कंस्ट्रक्ट को ट्रांसलेट करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंट में बदलता है। Pointee_ प्रकार को पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड ऑब्जेक्ट का रेफ़रेंस काउंटर घटाता है और ऑब्जेक्ट को हटाता है। |

## देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नेमस्पेस [System::Collections::Generic](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: StringCollectionPtr
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: स्ट्रिंग संग्रह पॉइंटर एक्सेस ऑपरेटर के साथ।
type: docs
weight: 40
url: /hi/system.collections.specialized/stringcollectionptr/
---
## StringCollectionPtr वर्ग

Stirng collection poiner with access operator.

```cpp
class StringCollectionPtr : public System::SmartPtr<StringCollection>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | अधीन संग्रह की [begin()](../../system/smartptr/begin/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [begin()](../../system/smartptr/begin/) विधि रखता हो। |
| auto [begin](../../system/smartptr/begin/)() const | अधीन संग्रह की [begin()](../../system/smartptr/begin/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [begin()](../../system/smartptr/begin/) विधि रखता हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस टाइप में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड टाइप में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड टाइप में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | अधीन संग्रह की [cbegin()](../../system/smartptr/cbegin/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [cbegin()](../../system/smartptr/cbegin/) विधि रखता हो। |
| auto [cend](../../system/smartptr/cend/)() const | अधीन संग्रह की [cend()](../../system/smartptr/cend/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [cend()](../../system/smartptr/cend/) विधि रखता हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | अधीन संग्रह की [end()](../../system/smartptr/end/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [end()](../../system/smartptr/end/) विधि रखता हो। |
| auto [end](../../system/smartptr/end/)() const | अधीन संग्रह की [end()](../../system/smartptr/end/) विधि के लिए अभिगमक। केवल तभी संकलित होता है जब SmartPtr_ का विशिष्ट प्रकार [end()](../../system/smartptr/end/) विधि रखता हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंट किए गए ऑब्जेक्ट को प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंट किए गए ऑब्जेक्ट को प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौज़ूद साझा पॉइंटर्स की संख्या को प्राप्त करता है, जिसमें वर्तमान भी शामिल है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंट किए गए ऑब्जेक्ट पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि कोई हो) को प्राप्त करता है या अपवाद उत्पन्न करता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंट किए गए ऑब्जेक्ट को (यदि कोई हो) या nullptr को प्राप्त करता है। [get()](../../system/smartptr/get/) के समान। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंट किए गए ऑब्जेक्ट को (यदि कोई हो) या nullptr को प्राप्त करता है। [get()](../../system/smartptr/get/) के समान। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि पॉइंट किया गया ऑब्जेक्ट किसी विशिष्ट प्रकार या उसके चाइल्ड प्रकार का है या नहीं। C# 'is' सेमेंटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जांचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट को पॉइंट कर रहा है जो मालिक नहीं है (एलिएसिंग कंस्ट्रक्टर द्वारा निर्मित)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जांचता है कि पॉइंटर साझा मोड में है या नहीं। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जांचता है कि पॉइंटर कमजोर मोड में है या नहीं। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जांचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जांचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंट किए गए ऑब्जेक्ट का संदर्भ प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्य तक पहुंच प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम तुलना सेमेंटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम तुलना सेमेंटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक टाइप रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जांचता है कि पॉइंटर nullptr को पॉइंट करता है या नहीं। |
| [System::String](../../system/string/)\& [operator[]](./operator[]/)(int) const | अभिगमक फ़ंक्शन। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से एलिएसिंग (एलिएसिंग कंस्ट्रक्टर द्वारा निर्मित) को हटा देता है, यह सुनिश्चित करता है कि वह उसी ऑब्जेक्ट को प्रबंधित (यदि साझा) या ट्रैक (यदि कमजोर) करे जिसे वह पॉइंट करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंट किए गए ऑब्जेक्ट को सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इंगित करता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड को सेट करता है। यह संदर्भित ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकते हैं। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंट किए गए ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() विधि को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इंगित करके [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इंगित करते हैं। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर इंगित करते हैं। यदि अनुमति हो तो टाइप रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों एक ही मोड में हैं तो दो पॉइंटर्स का अदला-बदली करता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित एरे के प्रकार को अलग प्रकार के नए एरे बनाकर परिवर्तित करता है। यह उपयोगी है जब C# में एरे टाइप कास्ट हो जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे प्रारम्भ करता है। कुछ C# कोड संरचनाओं को अनुवादित करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारम्भिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p को रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंट किए गए ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को विभिन्न प्रकार में कास्ट करता है। |
|  [StringCollectionPtr](./stringcollectionptr/)() | null पॉइंटर बनाता है। |
|  [StringCollectionPtr](./stringcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[StringCollection](../stringcollection/)\>\&) | विशिष्ट संग्रह के लिए पॉइंटर बनाता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) की ओर पॉइंटर में परिवर्तित करता है। Pointee_ प्रकार को पूर्ण होने की आवश्यकता नहीं। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) प्रकार के लिए ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंट किए गए ऑब्जेक्ट के रेफ़रेंस काउंट को घटाता है और ऑब्जेक्ट को मिटा देता है। |

## देखें भी

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Collections::Specialized](../)
* लाइब्रेरी [Aspose.Slides](../../)
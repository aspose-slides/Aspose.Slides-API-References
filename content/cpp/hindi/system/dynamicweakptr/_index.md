---
title: DynamicWeakPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: एक स्मार्ट पॉइंटर क्लास जो संग्रहीत ऑब्जेक्ट के टेम्प्लेट आर्ग्युमेंट्स के पॉइंटर मोड को ट्रैक करता है और प्रत्येक असाइनमेंट के बाद उन्हें अपडेट करता है। यह प्रकार अन्य ऑब्जेक्ट के डिलीशन को प्रबंधित करने के लिये एक पॉइंटर है। इसे स्टैक पर एलोकेट किया जाना चाहिए और फ़ंक्शनों को वैल्यू या कॉन्स्ट रेफ़रेंस के द्वारा पास किया जाना चाहिए।
type: docs
weight: 781
url: /hi/system/dynamicweakptr/
---
## DynamicWeakPtr क्लास

स्मार्ट पॉइंटर क्लास जो संग्रहीत ऑब्जेक्ट के टेम्प्लेट आर्ग्युमेंट्स के पॉइंटर मोड को ट्रैक करता है और प्रत्येक असाइनमेंट के बाद उन्हें अपडेट करता है। यह प्रकार एक पॉइंटर है जो अन्य ऑब्जेक्ट के डिलीशन को प्रबंधित करता है। इसे स्टैक पर एलोकेट किया जाना चाहिए और फंक्शन्स को वैल्यू या कॉन्स्ट रेफरेंस के द्वारा पास किया जाना चाहिए।

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode of smart pointer itself, shared or weak. |
| weakLeafs | Indexes of template arguments of stored type which should be set to weak pointer mode. |

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../smartptr/begin/)() | एक अंडरलाइनिंग कलेक्शन के [begin()](../smartptr/begin/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../smartptr/begin/) मेथड हो। |
| auto [begin](../smartptr/begin/)() const | एक अंडरलाइनिंग कलेक्शन के [begin()](../smartptr/begin/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../smartptr/begin/) मेथड हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | पॉइंटर को static_cast का उपयोग करके बेस टाइप में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | पॉइंटर को dynamic_cast का उपयोग करके डेराइव्ड टाइप में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | पॉइंटर को dynamic_cast का उपयोग करके डेराइव्ड टाइप में कास्ट करता है। |
| auto [cbegin](../smartptr/cbegin/)() const | एक अंडरलाइनिंग कलेक्शन के [cbegin()](../smartptr/cbegin/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cbegin()](../smartptr/cbegin/) मेथड हो। |
| auto [cend](../smartptr/cend/)() const | एक अंडरलाइनिंग कलेक्शन के [cend()](../smartptr/cend/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cend()](../smartptr/cend/) मेथड हो। |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | पॉइंटर को const_cast का उपयोग करके पॉइंटेड ऑब्जेक्ट पर अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | पॉइंटर को dynamic_cast का उपयोग करके पॉइंटेड ऑब्जेक्ट पर अलग प्रकार में कास्ट करता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | एक नल स्मार्ट पॉइंटर बनाता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | दिए गए ऑब्जेक्ट की ओर इशारा करने वाला स्मार्ट पॉइंटर बनाता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | स्मार्ट पॉइंटर की कॉपी-निर्माण करता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | स्मार्ट पॉइंटर की कॉपी-निर्माण करता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | स्मार्ट पॉइंटर की कॉपी-निर्माण करता है। |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | स्मार्ट पॉइंटर की मूव-निर्माण करता है। |
| auto [end](../smartptr/end/)() | एक अंडरलाइनिंग कलेक्शन के [end()](../smartptr/end/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../smartptr/end/) मेथड हो। |
| auto [end](../smartptr/end/)() const | एक अंडरलाइनिंग कलेक्शन के [end()](../smartptr/end/) मेथड का एक्सेसर। केवल तभी कंपाइल होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../smartptr/end/) मेथड हो। |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर शेयर मोड में है। |
| int [get_shared_count](../smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूद शेयर किए गए पॉइंटर्स की संख्या (वर्तमान सहित) प्राप्त करता है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर शेयर मोड में है। |
| int [GetHashCode](../smartptr/gethashcode/)() const | [GetHashCode()](../smartptr/gethashcode/) को पॉइंटेड ऑब्जेक्ट पर कॉल करता है। |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि मौजूद हो) प्राप्त करता है या थ्रो करता है। |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट (यदि मौजूद हो) प्राप्त करता है या nullptr लौटाता है। [get()](../smartptr/get/) के समान। |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट (यदि मौजूद हो) प्राप्त करता है या nullptr लौटाता है। [get()](../smartptr/get/) के समान। |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | जाँच करता है कि पॉइंटेड ऑब्जेक्ट निर्दिष्ट प्रकार या उसके चाइल्ड प्रकार का है या नहीं। C# के 'is' सेमांटिक्स का अनुसरण करता है। |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | जाँच करता है कि पॉइंटर किसी अन्य ऑब्जेक्ट की ओर इशारा कर रहा है जो स्वामित्व में नहीं है (aliasing कन्स्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](../smartptr/isshared/)() const | जाँच करता है कि पॉइंटर शेयर मोड में है या नहीं। |
| **bool** [IsWeak](../smartptr/isweak/)() const | जाँच करता है कि पॉइंटर वीक मोड में है या नहीं। |
| explicit  [operator bool](../smartptr/operator_bool/)() const | जाँच करता है कि पॉइंटर नल नहीं है। |
| **bool** [operator!](../smartptr/operator_not/)() const | जाँच करता है कि पॉइंटर नल है या नहीं। |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर नल नहीं है। |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के मेंबर्स तक पहुँच प्रदान करता है। |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) क्लास के लिए less-compare सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) क्लास के लिए less-compare सेमांटिक्स प्रदान करता है। |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | स्मार्ट पॉइंटर को मूव-असाइन करता है। |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | स्मार्ट पॉइंटर को कॉपी-असाइन करता है। |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | स्मार्ट पॉइंटर को कॉपी-असाइन करता है। |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | स्मार्ट पॉइंटर को असाइन करता है। |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | स्मार्ट पॉइंटर को नल सेट करता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | जाँच करता है कि स्मार्ट पॉइंटर नल है या नहीं। |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कन्स्ट्रक्टर द्वारा बनाया गया) को हटाता है, यह सुनिश्चित करता है कि वह (यदि शेयर है तो) प्रबंधित करे या (यदि वीक है तो) ट्रैक करे वही ऑब्जेक्ट जिस ओर वह इशारा करता है। |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करने के लिए बनाता है। |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट की रेफरेंस काउण्ट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि मौजूद हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट आवश्यक मोड में बनाता है। |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | नल-पॉइंटर [SmartPtr](../smartptr/) ऑब्जेक्ट आवश्यक मोड में बनाता है। |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) बनाता है जो निर्दिष्ट ऑब्जेक्ट की ओर इशारा करता है, या रॉ पॉइंटर को [SmartPtr](../smartptr/) में बदलता है। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इशारा करेंगे। यदि अनुमति हो तो टाइप कन्वर्ज़न करता है। |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को मूव-कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों एक ही मोड में हैं तो दो पॉइंटर्स को स्वैप करता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | एक अलग प्रकार की नई एरे बनाकर संदर्भित एरे के टाइप को बदलता है। उपयोगी जब C# में एरे टाइप कास्ट हो जो C++ में समर्थन नहीं रखता। |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | खाली एरे इनिशियलाइज़ करता है। कुछ C# कोड कंस्ट्रक्ट्स को ट्रांसलेट करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ ओनरशिप जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | किसी भी पॉइंटर टाइप को [Object](../object/) के पॉइंटर में बदलता है। Pointee_ टाइप को पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | [System::TypeInfo](../typeinfo/) ऑब्जेक्ट को Pointee_ टाइप के लिए प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो तो पॉइंटेड ऑब्जेक्ट की रेफरेंस काउंटर घटाता है और ऑब्जेक्ट को डिलीट करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) बेसक्लास उपनाम। |
| [DynamicWeakPtr_](./dynamicweakptr_/) | सेल्फ टाइप उपनाम। |
| [Pointee_](./pointee_/) | पॉइंटेड टाइप। |

## देखें

* क्लास [SmartPtr](../smartptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
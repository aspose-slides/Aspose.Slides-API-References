---
title: GroupCollectionPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: समूह संग्रह पोइंटर। यह प्रकार अन्य वस्तु के विलोपन को प्रबंधित करने के लिए एक पोइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मूल्य द्वारा या स्थिर संदर्भ द्वारा पास किया जाना चाहिए।
type: docs
weight: 53
url: /hi/system.text.regularexpressions/groupcollectionptr/
---
## GroupCollectionPtr क्लास

[Group](../group/) संग्रह पोइंटर। यह प्रकार अन्य वस्तु के विलोपन को प्रबंधित करने के लिए एक पोइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन्स को मूल्य द्वारा या स्थिर संदर्भ द्वारा पास किया जाना चाहिए।

```cpp
class GroupCollectionPtr : public System::SmartPtr<GroupCollection>
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक अंतर्निहित संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक अंतर्निहित संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाला विशेषीकरण प्रकार हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक अंतर्निहित संग्रह के [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक अंतर्निहित संग्रह के [cend()](../../system/smartptr/cend/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [cend()](../../system/smartptr/cend/) मेथड वाला विशेषीकरण प्रकार हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | एक अंतर्निहित संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [end](../../system/smartptr/end/)() const | एक अंतर्निहित संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए एक्सेसर। केवल तभी संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाला विशेषीकरण प्रकार हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट को प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट को प्राप्त करता है, लेकिन पुष्टि करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूद साझा पॉइंटर्स की संख्या (वर्तमान सहित) प्राप्त करता है। पुष्टि करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | पॉइंटेड ऑब्जेक्ट पर [GetHashCode()](../../system/smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि हो) को प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट (यदि हो) को प्राप्त करता है या nullptr लौटाता है। [get()](../../system/smartptr/get/) के समान। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट (यदि हो) को प्राप्त करता है या nullptr लौटाता है। [get()](../../system/smartptr/get/) के समान। |
|  [GroupCollectionPtr](./groupcollectionptr/)() | नल पोइंटर कन्स्ट्रक्टर। |
|  [GroupCollectionPtr](./groupcollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[GroupCollection](../groupcollection/)\>\&) | टाइप रूपांतरण कन्स्ट्रक्टर। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँच करता है कि पॉइंटेड ऑब्जेक्ट विशिष्ट प्रकार या उसकी चाइल्ड प्रकार का है। C# के 'is' अभिप्राय को अपनाता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँच करता है कि पॉइंटर उस वस्तु की ओर इशारा कर रहा है जो स्वामित्व वाली नहीं है (एक एलाईसिंग कन्स्ट्रक्टर द्वारा बनाई गई)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँच करता है कि पॉइंटर साझा मोड में है या नहीं। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँच करता है कि पॉइंटर विंड मोड में है या नहीं। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँच करता है कि पॉइंटर नल नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँच करता है कि पॉइंटर नल है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। पुष्टि करता है कि पॉइंटर नल नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्य तक पहुँच की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए लेस-तुलना सेमान्टिक प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए लेस-तुलना सेमान्टिक प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब प्रयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चा पोइंटर [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँच करता है कि पॉइंटर nullptr की ओर इशारा कर रहा है। |
| [GroupPtr](../groupptr/) [operator[]](./operator[]/)(size_t) const | [Group](../group/) एक्सेसर। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से एलाईसिंग (एलाईसिंग कन्स्ट्रक्टर द्वारा बनाया गया) हटाता है, सुनिश्चित करता है कि वह उसी ऑब्जेक्ट को प्रबंधित (यदि साझा) या ट्रैक (यदि विंड) करता है जिस पर वह इशारा करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट को सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करवाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट के रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का नल-पॉइंटर [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इशारा करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पोइंटर को [SmartPtr](../../system/smartptr/) में बदलता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। बाद में दोनों पोइंटर एक ही ऑब्जेक्ट की ओर इशारा करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। बाद में दोनों पोइंटर एक ही ऑब्जेक्ट की ओर इशारा करेंगे। यदि अनुमति हो तो प्रकार परिवर्तन करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों एक ही मोड में हैं तो दो पोइंटर बदलते हैं। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित एरे के प्रकार को अलग प्रकार के नए एरे बनाकर परिवर्तित करता है। यह उपयोगी है जब C# में एरे टाइप कास्ट है जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को इनिशियलाइज़ करता है। कुछ C# कोड संरचनाओं का अनुवाद करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पोइंटर p को धारण करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड ऑब्जेक्ट का रेफ़रेंस काउंटर घटाता है और ऑब्जेक्ट को हटाता है। |

## संबंधित देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Text::RegularExpressions](../)
* लाइब्रेरी [Aspose.Slides](../../)
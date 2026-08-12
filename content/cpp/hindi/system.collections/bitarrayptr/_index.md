---
title: BitArrayPtr
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: BitArray के लिए पॉइंटर। यह प्रकार अन्य वस्तु की विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या स्थिर संदर्भ द्वारा पास किया जाना चाहिए।
type: docs
weight: 14
url: /hi/system.collections/bitarrayptr/
---
## BitArrayPtr क्लास

[BitArray](../bitarray/) के लिए पॉइंटर। यह प्रकार अन्य वस्तु की विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या स्थिर संदर्भ द्वारा पास किया जाना चाहिए।

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | [begin()](../../system/smartptr/begin/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [begin](../../system/smartptr/begin/)() const | [begin()](../../system/smartptr/begin/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [begin()](../../system/smartptr/begin/) मेथड वाले विशेषीकरण प्रकार हो। |
|  [BitArrayPtr](./bitarrayptr/)() | null पॉइंटर को आरंभ करता है। |
|  [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | परिवर्तन कन्स्ट्रक्टर। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को उसी प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को व्युत्पन्न प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | [cbegin()](../../system/smartptr/cbegin/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [cbegin()](../../system/smartptr/cbegin/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [cend](../../system/smartptr/cend/)() const | [cend()](../../system/smartptr/cend/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [cend()](../../system/smartptr/cend/) मेथड वाले विशेषीकरण प्रकार हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | [end()](../../system/smartptr/end/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाले विशेषीकरण प्रकार हो। |
| auto [end](../../system/smartptr/end/)() const | [end()](../../system/smartptr/end/) मेथड का एक्सेसर। अधीनस्थ संग्रह का। केवल तब संकलित होता है जब SmartPtr_ [end()](../../system/smartptr/end/) मेथड वाले विशेषीकरण प्रकार हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूद साझा पॉइंटर्स की संख्या प्राप्त करता है, जिसमें वर्तमान भी शामिल है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) को पॉइंटेड ऑब्जेक्ट पर कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या अपवाद उत्पन्न करता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr लौटाता है। [get()](../../system/smartptr/get/) के समान। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है (यदि कोई हो) या nullptr लौटाता है। [get()](../../system/smartptr/get/) के समान। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंटेड ऑब्जेक्ट विशिष्ट प्रकार का है या उसका चाइल्ड प्रकार। C# 'is' सेमांटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट को इंगित कर रहा है, न कि स्वयं के स्वामित (aliasing कंस्ट्रक्टर द्वारा निर्मित)। |
| **bool** [IsNull](./isnull/)() const | जाँचता है कि निर्दिष्ट मान null है। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि पॉइंटर वीकमोड में है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्यों तक पहुँच प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को रॉ पॉइंटर असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि पॉइंटर nullptr की ओर संकेत करता है। |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | बिट एक्सेसर। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कंस्ट्रक्टर द्वारा निर्मित) हटाता है, यह सुनिश्चित करता है कि यह उसी ऑब्जेक्ट को प्रबंधित (यदि साझा) या ट्रैक (यदि weak) करता है जिसे यह इंगित करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर संकेत करने के लिए बनाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट के रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | यदि कोई हो तो पॉइंटेड ऑब्जेक्ट पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर संकेत करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या रॉ पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर संकेत करते हैं। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में एक ही ऑब्जेक्ट की ओर संकेत करते हैं। यदि अनुमति हो तो प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव कंस्ट्रक्ट करता है। प्रभावी रूप से, दो पॉइंटरों को बदलता है, यदि दोनों एक ही मोड में हों। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | भिन्न प्रकार की नई एरे बनाकर संदर्भित एरे के प्रकार को परिवर्तित करता है। उपयोगी जब C# में एरे टाइप कास्ट हो लेकिन C++ में असमर्थित हो। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को प्रारम्भ करता है। कुछ C# कोड संरचनाओं के अनुवाद में उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारम्भिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में परिवर्तित करता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट को Pointee_ प्रकार के लिए प्राप्त करने की शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो तो पॉइंटेड ऑब्जेक्ट के रेफ़रेंस काउंटर को घटाता है और ऑब्जेक्ट को डिलीट करता है। |

## देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Collections](../)
* लाइब्रेरी [Aspose.Slides](../../)
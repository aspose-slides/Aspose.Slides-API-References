---
title: QueuePtr
second_title: Aspose.Slides for C++ API संदर्भ
description: Queue पॉइंटर। यह प्रकार अन्य ऑब्जेक्ट की हटाने को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 482
url: /hi/system.collections.generic/queueptr/
---
## QueuePtr वर्ग


[Queue](../queue/) सूचक। यह प्रकार अन्य ऑब्जेक्ट की मिटाने को प्रबंधित करने के लिए एक सूचक है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।

```cpp
template<typename T>class QueuePtr : public System::SmartPtr<Queue<T>>
```

## Methods

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | नीचे की संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| auto [begin](../../system/smartptr/begin/)() const | नीचे की संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | सूचक को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | static_cast का उपयोग करके सूचक को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके सूचक को व्युत्पन्न प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | dynamic_cast का उपयोग करके सूचक को व्युत्पन्न प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | नीचे की संग्रह के [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [cbegin()](../../system/smartptr/cbegin/) मेथड हो। |
| auto [cend](../../system/smartptr/cend/)() const | नीचे की संग्रह के [cend()](../../system/smartptr/cend/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [cend()](../../system/smartptr/cend/) मेथड हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके सूचक को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके सूचक को अलग प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | नीचे की संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [end()](../../system/smartptr/end/) मेथड हो। |
| auto [end](../../system/smartptr/end/)() const | नीचे की संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो और उसमें [end()](../../system/smartptr/end/) मेथड हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | सूचक मोड प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि सूचक साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूदा साझा सूचकों की संख्या प्राप्त करता है, जिसमें वर्तमान भी शामिल है। यह सुनिश्चित करता है कि वर्तमान सूचक साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) को पॉइंटेड ऑब्जेक्ट पर कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि कोई हो) प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) प्राप्त करता है या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) प्राप्त करता है या nullptr लौटाता है। यह [get()](../../system/smartptr/get/) के समान है। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि पॉइंटेड ऑब्जेक्ट निर्दिष्ट प्रकार या उसके उपप्रकार का है या नहीं। C# के 'is' सेमांटिक्स का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जाँचता है कि सूचक किसी अन्य ऑब्जेक्ट को इंगित करता है जो स्वामित्व वाला नहीं है (एक aliasing कॉन्स्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जाँचता है कि सूचक साझा मोड में है या नहीं। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जाँचता है कि सूचक कमजोर मोड में है या नहीं। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जाँचता है कि सूचक null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जाँचता है कि सूचक null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि सूचक null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्यों तक पहुँच की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक्स प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | कच्चे सूचक को [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | सूचक मान को nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि सूचक nullptr को इंगित करता है या नहीं। |
|  [QueuePtr](./queueptr/)() | null सूचक बनाता है। |
|  [QueuePtr](./queueptr/)(const [SharedPtr](../../system/sharedptr/)\<[Queue](../queue/)\<T\>\>\&) | विशिष्ट क्यू के लिए सूचक बनाता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | सूचक से aliasing (जो aliasing कॉन्स्ट्रक्टर द्वारा बनाया गया था) हटाता है, यह सुनिश्चित करता है कि यदि साझा हो तो वह प्रबंधित करे या यदि कमजोर हो तो समान ऑब्जेक्ट को ट्रैक करे जिस पर यह इंगित करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | सूचक को nullptr की ओर इंगित करता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | सूचक मोड सेट करता है। यह संदर्भित ऑब्जेक्ट की रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इंगित करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे सूचक को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों सूचक बाद में एक ही ऑब्जेक्ट की ओर इंगित करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को कॉपी कंस्ट्रक्ट करता है। दोनों सूचक बाद में एक ही ऑब्जेक्ट की ओर इंगित करेंगे। यदि अनुमति है तो प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को मूव कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों एक ही मोड में हैं तो दो सूचक बदल देता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | संदर्भित एरे का प्रकार बदल कर अलग प्रकार की नई एरे बनाकर परिवर्तित करता है। यह उपयोगी है जब C# में ऐसा एरे टाइप कास्ट हो जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को प्रारंभ करता है। कुछ C# कोड संरचनाओं को अनुवादित करने में उपयोग होता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | एक [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारम्भिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड सूचक p को रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके सूचक को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी प्रकार के सूचक को [Object](../../system/object/) के सूचक में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड ऑब्जेक्ट के रेफ़रेंस काउंट को घटाता है और ऑब्जेक्ट को डिलीट करता है। |

## संबंधित देखें

* वर्ग [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Collections::Generic](../)
* पुस्तकालय [Aspose.Slides](../../)
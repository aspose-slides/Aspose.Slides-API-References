---
title: WeakPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: "System::SmartPtr की सबक्लास जो निर्माण के समय खुद को weak मोड में सेट करती है। कृपया ध्यान दें कि यह क्लास यह गारंटी नहीं देती कि इसका इंस्टेंस हमेशा weak मोड में रहेगा क्योंकि set_Mode() अभी भी उपलब्ध है। यह प्रकार अन्य ऑब्जेक्ट के विलोपन को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।"
type: docs
weight: 1496
url: /hi/system/weakptr/
---
## WeakPtr क्लास


[System::SmartPtr](../smartptr/) की सबक्लास जो निर्माण के समय खुद को weak मोड में सेट करती है। कृपया ध्यान दें कि यह क्लास यह गारंटी नहीं देती कि इसका इंस्टेंस हमेशा weak मोड में रहेगा क्योंकि [set_Mode()](../smartptr/set_mode/) अभी भी सुलभ है। यह प्रकार एक पॉइंटर है जो अन्य ऑब्जेक्ट के विलोपन को प्रबंधित करता है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```


### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | पॉइंटिए टाइप। |
## Methods

| Method | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | [begin()](../smartptr/begin/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [begin()](../smartptr/begin/) मेथड हो। |
| auto [begin](../smartptr/begin/)() const | [begin()](../smartptr/begin/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [begin()](../smartptr/begin/) मेथड हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| auto [cbegin](../smartptr/cbegin/)() const | [cbegin()](../smartptr/cbegin/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [cbegin()](../smartptr/cbegin/) मेथड हो। |
| auto [cend](../smartptr/cend/)() const | [cend()](../smartptr/cend/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [cend()](../smartptr/cend/) मेथड हो। |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| auto [end](../smartptr/end/)() | [end()](../smartptr/end/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [end()](../smartptr/end/) मेथड हो। |
| auto [end](../smartptr/end/)() const | [end()](../smartptr/end/) मेथड के लिए एक्सेसर जो एक अंतर्निहित संग्रह का है। केवल तब कंपाइल होता है जब SmartPtr_ विशिष्टीकरण प्रकार हो जिसमें [end()](../smartptr/end/) मेथड हो। |
| **bool** [expired](./expired/)() const | जाँचता है कि संदर्भित ऑब्जेक्ट पहले ही हटा दिया गया है या नहीं। |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है। |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | पॉइंटेड ऑब्जेक्ट प्राप्त करता है, लेकिन यह सुनिश्चित करता है कि पॉइंटर shared मोड में है। |
| int [get_shared_count](../smartptr/get_shared_count/)() const | संदर्भित ऑब्जेक्ट के लिए मौजूदा shared पॉइंटर्स की संख्या (वर्तमान सहित) प्राप्त करता है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर shared मोड में है। |
| [Object](../object/) * [get_weak](./get_weak/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर weak मोड में है। |
| int [GetHashCode](../smartptr/gethashcode/)() const | पॉइंटेड ऑब्जेक्ट पर [GetHashCode()](../smartptr/gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि कोई हो) प्राप्त करता है या एक्सेप्शन फेंकता है। |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) या nullptr प्राप्त करता है। यह [get()](../smartptr/get/) के समान है। |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) या nullptr प्राप्त करता है। यह [get()](../smartptr/get/) के समान है। |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | जाँचता है कि पॉइंटेड ऑब्जेक्ट विशिष्ट प्रकार या उसकी चाइल्ड टाइप का है। C# के 'is' सैमैंटिक्स को फॉलो करता है। |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | जाँचता है कि पॉइंटर किसी अन्य ऑब्जेक्ट की ओर इंगित है जो स्वामित्व में नहीं है (aliasing कंस्ट्रक्टर द्वारा निर्मित)। |
| **bool** [IsShared](../smartptr/isshared/)() const | जाँचता है कि पॉइंटर shared मोड में है या नहीं। |
| **bool** [IsWeak](../smartptr/isweak/)() const | जाँचता है कि पॉइंटर weak मोड में है या नहीं। |
| explicit  [operator bool](../smartptr/operator_bool/)() const | जाँचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../smartptr/operator_not/)() const | जाँचता है कि पॉइंटर null है। |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | पॉइंटेड ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्यों तक पहुँचने की अनुमति देता है। |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | [SmartPtr](../smartptr/) क्लास के लिए less-compare सैमैंटिक्स प्रदान करता है। |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | [SmartPtr](../smartptr/) क्लास के लिए less-compare सैमैंटिक्स प्रदान करता है। |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | weak पॉइंटर को वैल्यू असाइन करता है। SmartPtr_ के विशिष्ट असाइनमेंट ऑपरेटर को कॉल करता है। |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | [SmartPtr](../smartptr/) ऑब्जेक्ट को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक टाइप रूपांतरण करता है। |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | raw पॉइंटर को [SmartPtr](../smartptr/) ऑब्जेक्ट में असाइन करता है। |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर वैल्यू को nullptr सेट करता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | जाँचता है कि weak पॉइंटर null है। |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | पॉइंटर से aliasing (aliasing कंस्ट्रक्टर द्वारा निर्मित) हटाता है, यह सुनिश्चित करता है कि वह (यदि shared है तो) प्रबंधित करे या (यदि weak है तो) ट्रैक करे वही ऑब्जेक्ट जिस पर वह इंगित करता है। |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | पॉइंटेड ऑब्जेक्ट सेट करता है। |
| void [reset](../smartptr/reset/)() | पॉइंटर को nullptr की ओर इंगित करता है। |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट की रेफ़रेंस काउंट बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | पॉइंटेड ऑब्जेक्ट (यदि कोई हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | आवश्यक मोड का [SmartPtr](../smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../smartptr/) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर इंगित [SmartPtr](../smartptr/) बनाता है, या raw पॉइंटर को [SmartPtr](../smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इंगित करते हैं। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को कॉपी-कंस्ट्रक्ट करता है। दोनों पॉइंटर्स बाद में एक ही ऑब्जेक्ट की ओर इंगित करते हैं। यदि अनुमति है तो टाइप रूपांतरण करता है। |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](../smartptr/) ऑब्जेक्ट को मूव-कंस्ट्रक्ट करता है। प्रभावी रूप से, यदि दोनों समान मोड के हों तो दो पॉइंटर्स को स्वैप करता है। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | एक अलग प्रकार के नए एरे बनाकर संदर्भित एरे का टाइप बदलता है। यह उपयोगी है अगर C# में ऐसा एरे टाइप कास्ट है जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | खाली एरे को इनिशियलाइज़ करता है। कुछ C# कोड कंस्ट्रक्ट्स को ट्रांसलेट करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | एक [SmartPtr](../smartptr/) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, लेकिन एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | पॉइंटेड ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | किसी भी पॉइंटर टाइप को [Object](../object/) की ओर पॉइंटर में बदलता है। Pointee_ टाइप के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | [System::TypeInfo](../typeinfo/) ऑब्जेक्ट को Pointee_ टाइप के लिए प्राप्त करने का शॉर्टकट। |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | null पॉइंटर बनाता है। |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | दिए गए ऑब्जेक्ट के लिए weak पॉइंटर बनाता है। |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | वेही पॉइंटर जिसे ptr इंगित करता है, को रेफ़रेंस करने वाला weak पॉइंटर बनाता है। |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | वेही पॉइंटर जिसे x इंगित करता है, को रेफ़रेंस करने वाला weak पॉइंटर बनाता है। |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | weak पॉइंटर को कॉपी-कंस्ट्रक्ट करता है। |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | weak पॉइंटर को कॉपी-कंस्ट्रक्ट करता है। |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | weak पॉइंटर को मूव-कंस्ट्रक्ट करता है। |
|  [~SmartPtr](../smartptr/~smartptr/)() | [SmartPtr](../smartptr/) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो पॉइंटेड ऑब्जेक्ट का रेफ़रेंस काउंटर घटाता है और ऑब्जेक्ट को डिलीट करता है। |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | समान [SmartPtr](../smartptr/) क्लास का उपनाम। |
| [WeakPtr_](./weakptr_/) | स्वयं प्रकार का उपनाम। |
| [Pointee_](./pointee_/) | पॉइंटेड टाइप। |

## देखें भी

* क्लास [SmartPtr](../smartptr/)
* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
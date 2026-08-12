---
title: SmartPtr
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "हीप पर आवंटित प्रकारों को लपेटने के लिए पॉइंटर क्लास। इसे उन क्लासों की मेमोरी प्रबंधन के लिए उपयोग करें जो Object को विरासत में लेती हैं। यह पॉइंटर प्रकार इंट्रूज़िव पॉइंटर सिमैंटिक्स का पालन करता है। रेफ़रेंस काउंटर या तो Object स्वयं में या काउंटर स्ट्रक्चर में संग्रहित रहता है जो Object इंस्टेंस से कसकर जुड़ा होता है। किसी भी स्थिति में, सभी SmartPtr इंस्टांस एक ही स्वामित्व समूह बनाते हैं, चाहे वे कैसे भी बनाए गए हों, जो std::shared_ptr क्लास के व्यवहार से अलग है। रॉ पॉइंटर को SmartPtr में बदलना सुरक्षित है बशर्ते अन्य SmartPtr इंस्टांस उसी ऑब्जेक्ट के शेयरड रेफ़रेंसेज़ रख रहे हों। SmartPtr क्लास का इंस्टांस दो स्थितियों में हो सकता है: शेयरड पॉइंटर और वीख पॉइंटर। ऑब्जेक्ट को जीवित रखने के लिए शेयरड रेफ़रेंसेज़ की संख्या सकारात्मक होनी चाहिए। दोनों वीख और शेयरड पॉइंटर का उपयोग संकेतित ऑब्जेक्ट तक पहुँचने के लिए किया जा सकता है (मेथड कॉल करना, फ़ील्ड पढ़ना या लिखना आदि), लेकिन वीख पॉइंटर शेयरड पॉइंटर के रेफ़रेंस काउंटिंग में भाग नहीं लेते। जब अंतिम 'शेयरड' SmartPtr पॉइंटर नष्ट हो जाता है, तो ऑब्जेक्ट डिलीट हो जाता है। इसलिए सुनिश्चित करें कि यह तब न हो जब कोई अन्य शेयरड SmartPtr पॉइंटर ऑब्जेक्ट के लिए मौजूद न हो, जैसे ऑब्जेक्ट निर्माण या विनाश के दौरान। इस समस्या को ठीक करने के लिए System::Object::ThisProtector सेंट्री ऑब्जेक्ट्स (C++ कोड में) या CppCTORSelfReference या CppSelfReference एट्रिब्यूट (C# कोड में) का उपयोग करें। इसी तरह, लूप रेफ़रेंसेज़ को तोड़ने के लिए System::WeakPtr पॉइंटर क्लास या System::SmartPtrMode::Weak पॉइंटर मोड (C++ कोड में) या CppWeakPtr एट्रिब्यूट (C# कोड में) का उपयोग करें। यदि दो या अधिक ऑब्जेक्ट 'शेयरड' पॉइंटर से एक-दूसरे को रेफ़र करते हैं, तो वे कभी डिलीट नहीं होंगे। यदि रनटाइम में पॉइंटर प्रकार (वीख या शेयरड) बदलना हो, तो System::SmartPtr<T>::set_Mode() मेथड या System::DynamicWeakPtr क्लास का उपयोग करें। SmartPtr क्लास में कोई वर्चुअल मेथड नहीं हैं। इसे केवल तभी विरासत में लें जब आप अपनी स्वयं की मेमोरी मैनेजमेंट स्ट्रेटेजी बना रहे हों। यह प्रकार अन्य ऑब्जेक्ट की डिलीशन को मैनेज करने के लिए एक पॉइंटर है। इसे स्टैक पर अलॉकेट करना चाहिए और फ़ंक्शन्स को वैल्यू या const रेफ़रेंस द्वारा पास करना चाहिए."
type: docs
weight: 1236
url: /hi/system/smartptr/
---
## SmartPtr क्लास

Pointer class to wrap types being allocated on heap. Use it to manage memory for classes inheriting [Object](../object/). This pointer type follows intrusive pointer semantics. Reference counter is stored either in [Object](../object/) itself or in counter structure which is tied to [Object](../object/) instance tightly. In any case, all [SmartPtr](./) instances form single ownership group regardless how they were created which is unlike how std::shared_ptr class behaves. Converting raw pointer to [SmartPtr](./) is safe given there are other [SmartPtr](./) instances holding shared references to the same object. [SmartPtr](./) class instance can be in one of two states: shared pointer and weak pointer. To keep object alive, one should have count of shared references to it positive. Both weak and shared pointers can be used to access pointed object (to call methods, read or write fields, etc.), but weak pointers do not participate to shared pointer reference counting. [Object](../object/) is being deleted when the last 'shared' [SmartPtr](./) pointer to it is being destroyed. So, make sure that this doesn't happen when no other shared [SmartPtr](./) pointers to object exist, e. g. during object construction or destruction. Use System::Object::ThisProtector sentry objects (in C++ code) or CppCTORSelfReference or CppSelfReference attribute (in C# code being translated) to fix this issue. Similarily, make sure to break loop references by using [System::WeakPtr](../weakptr/) pointer class or [System::SmartPtrMode::Weak](../smartptrmode/) pointer mode (in C++ code) or CppWeakPtr attribute (in C# code being translated). If two or more objects reference each other using 'shared' pointers, they will never be deleted. If pointer type (weak or shared) should be switched in runtime, use [System::SmartPtr<T>::set_Mode()](./set_mode/) method or [System::DynamicWeakPtr](../dynamicweakptr/) class. [SmartPtr](./) class doesn't contain any virtual methods. You should only inherit it if you're creating a memory management strategy of your own. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
template<class T>class SmartPtr
```


### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | संकेतित ऑब्जेक्ट का प्रकार। यह या तो [System::Object](../object/) होना चाहिए या उसका सबक्लास। |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| auto [begin](./begin/)() | एक अंतर्निहित संग्रह की [begin()](./begin/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [begin()](./begin/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [begin](./begin/)() const | एक अंतर्निहित संग्रह की [begin()](./begin/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [begin()](./begin/) मेथड वाला विशेषीकरण प्रकार हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | पॉइंटर को उसके स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | static_cast का उपयोग करके पॉइंटर को बेस टाइप में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेरिव्ड टाइप में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | dynamic_cast का उपयोग करके पॉइंटर को डेरिव्ड टाइप में कास्ट करता है। |
| auto [cbegin](./cbegin/)() const | एक अंतर्निहित संग्रह की [cbegin()](./cbegin/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [cbegin()](./cbegin/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [cend](./cend/)() const | एक अंतर्निहित संग्रह की [cend()](./cend/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [cend()](./cend/) मेथड वाला विशेषीकरण प्रकार हो। |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | संकेतित ऑब्जेक्ट पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | संकेतित ऑब्जेक्ट पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| auto [end](./end/)() | एक अंतर्निहित संग्रह की [end()](./end/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [end()](./end/) मेथड वाला विशेषीकरण प्रकार हो। |
| auto [end](./end/)() const | एक अंतर्निहित संग्रह की [end()](./end/) मेथड के लिये एक्सेसर। केवल तब कंपाइल होता है जब SmartPtr_ के पास [end()](./end/) मेथड वाला विशेषीकरण प्रकार हो। |
| [Pointee_](./pointee_/) * [get](./get/)() const | संकेतित ऑब्जेक्ट को प्राप्त करता है। |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | पॉइंटर मोड प्राप्त करता है। |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | संकेतित ऑब्जेक्ट प्राप्त करता है, पर यह सुनिश्चित करता है कि पॉइंटर शेयरड मोड में है। |
| int [get_shared_count](./get_shared_count/)() const | संदर्भित ऑब्जेक्ट पर मौजूद शेयरड पॉइंटर्स की संख्या प्राप्त करता है, जिसमें वर्तमान पॉइंटर भी शामिल है। यह सुनिश्चित करता है कि वर्तमान पॉइंटर शेयरड मोड में है। |
| int [GetHashCode](./gethashcode/)() const | संकेतित ऑब्जेक्ट पर [GetHashCode()](./gethashcode/) को कॉल करता है। |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | वर्तमान में संदर्भित ऑब्जेक्ट (यदि मौजूद हो) प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | संकेतित ऑब्जेक्ट (यदि मौजूद हो) या nullptr प्राप्त करता है। [get()](./get/) के समान। |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | संदर्भित ऑब्जेक्ट प्राप्त करता है। |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | संकेतित ऑब्जेक्ट (यदि मौजूद हो) या nullptr प्राप्त करता है। [get()](./get/) के समान। |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | जांचता है कि संकेतित ऑब्जेक्ट निर्दिष्ट प्रकार या उसके चाइल्ड प्रकार का है। C# के 'is' सेमांटिक्स का अनुसरण करता है। |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | जांचता है कि पॉइंटर उस ऑब्जेक्ट को संकेत कर रहा है जो स्वामित्व में नहीं है (एलिएसिंग कन्स्ट्रक्टर द्वारा बनाया गया)। |
| **bool** [IsShared](./isshared/)() const | जांचता है कि पॉइंटर शेयरड मोड में है या नहीं। |
| **bool** [IsWeak](./isweak/)() const | जांचता है कि पॉइंटर वीख मोड में है या नहीं। |
| explicit  [operator bool](./operator_bool/)() const | जांचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](./operator_not/)() const | जांचता है कि पॉइंटर null है। |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | संकेतित ऑब्जेक्ट का रेफ़रेंस प्राप्त करता है। यह सुनिश्चित करता है कि पॉइंटर null न हो। |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | संदर्भित ऑब्जेक्ट के सदस्यों तक पहुँच की अनुमति देता है। |
| **bool** [operator<](./operator_less/)(Y *) const | [SmartPtr](./) क्लास के लिये कम तुलना (less-compare) सेमांटिक्स प्रदान करता है। |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | [SmartPtr](./) क्लास के लिये कम तुलना (less-compare) सेमांटिक्स प्रदान करता है। |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | [SmartPtr](./) ऑब्जेक्ट को मूव-असाइन करता है। x अनुपयोगी हो जाता है। |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | [SmartPtr](./) ऑब्जेक्ट को कॉपी-असाइन करता है। |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | [SmartPtr](./) ऑब्जेक्ट को कॉपी-असाइन करता है। आवश्यक प्रकार परिवर्तन करता है। |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | कच्चे पॉइंटर को [SmartPtr](./) ऑब्जेक्ट को असाइन करता है। |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | पॉइंटर मान को nullptr सेट करता है। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | जांचता है कि पॉइंटर nullptr की ओर इशारा कर रहा है। |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | पॉइंटर से एलिएसिंग (एलिएसिंग कन्स्ट्रक्टर द्वारा बनाया गया) को हटाता है, सुनिश्चित करता है कि यह उसी ऑब्जेक्ट को मैनेज (अगर शेयरड) या ट्रैक (अगर वीख) करता है जिसे यह संकेत करता है। |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | संकेतित ऑब्जेक्ट सेट करता है। |
| void [reset](./reset/)() | पॉइंटर को nullptr की ओर संकेत करने देता है। |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | पॉइंटर मोड सेट करता है। यह संदर्भित ऑब्जेक्ट के रेफ़रेंस काउंट्स को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | संकेतित ऑब्जेक्ट (यदि मौजूद हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | आवश्यक मोड का [SmartPtr](./) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](./) ऑब्जेक्ट बनाता है। |
|  [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | निर्दिष्ट ऑब्जेक्ट की ओर संकेत करने वाला [SmartPtr](./) बनाता है, या कच्चे पॉइंटर को [SmartPtr](./) में बदलता है। |
|  [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) ऑब्जेक्ट की कॉपी निर्माण करता है। दोनों पॉइंटर बाद में उसी ऑब्जेक्ट को संकेत करेंगे। |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) ऑब्जेक्ट की कॉपी निर्माण करता है। दोनों पॉइंटर बाद में उसी ऑब्जेक्ट को संकेत करेंगे। यदि अनुमति हो तो प्रकार परिवर्तन करता है। |
|  [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | [SmartPtr](./) ऑब्जेक्ट की मूव निर्माण करता है। प्रभावी रूप से दो पॉइंटर को स्वैप करता है, यदि दोनों का मोड समान हो। कॉल के बाद x अनुपयोगी हो सकता है। |
| explicit  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | संदर्भित ऐरे के प्रकार को बदलता है, एक नया विभिन्न प्रकार का ऐरे बनाकर। यह उपयोगी है जब C# में ऐसा ऐरे टाइप कास्ट हो जिसे C++ में समर्थन नहीं है। |
| explicit  [SmartPtr](./smartptr/)(const Y\&) | खाली ऐरे को इनिशियलाइज़ करता है। कुछ C# कोड संरचनाओं के अनुवाद में उपयोग होता है। |
|  [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | एक [SmartPtr](./) बनाता है जो ptr के प्रारंभिक मान के साथ स्वामित्व जानकारी साझा करता है, परंतु एक असंबंधित और अनमैनेज्ड पॉइंटर p रखता है। |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | संकेतित ऑब्जेक्ट पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../object/) की ओर पॉइंटर में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Pointee_ प्रकार के लिये [System::TypeInfo](../typeinfo/) ऑब्जेक्ट प्राप्त करने का शॉर्टकट। |
|  [~SmartPtr](./~smartptr/)() | [SmartPtr](./) ऑब्जेक्ट को नष्ट करता है। यदि आवश्यक हो, तो संकेतित ऑब्जेक्ट के रेफ़रेंस काउंटर को घटाता है और ऑब्जेक्ट को डिलीट करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Pointee_](./pointee_/) | संकेतित प्रकार। |
| [SmartPtr_](./smartptr_/) | विशेषीकृत स्मार्ट पॉइंटर प्रकार। |
| [ArrayType](./arraytype/) | यदि यह [System::Array](../array/) का विशेषीकरण है तो Pointee_ के समान, अन्यथा void। |
| [ValueType](./valuetype/) | संकेतित ऐरे का संग्रह प्रकार। केवल तब अर्थपूर्ण जब T [System::Array](../array/) का विशेषीकरण हो। |

## देखें भी

* नेमस्पेस [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
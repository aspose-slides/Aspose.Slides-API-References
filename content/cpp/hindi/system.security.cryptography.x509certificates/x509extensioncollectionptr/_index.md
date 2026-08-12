---
title: X509ExtensionCollectionPtr
second_title: Aspose.Slides for C++ API संदर्भ
description: X509 एक्सटेंशन के संग्रह के लिए पॉइंटर। यह प्रकार अन्य वस्तु की हटाने को प्रबंधित करने के लिए एक पॉइंटर है। इसे स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या const रेफ़रेंस द्वारा पास किया जाना चाहिए।
type: docs
weight: 170
url: /hi/system.security.cryptography.x509certificates/x509extensioncollectionptr/
---
## X509ExtensionCollectionPtr क्लास

Pointer to collection of X509 extensions. This type is a pointer to manage other object's deletion. It should be allocated on stack and passed to functions either by value or by const reference.

```cpp
class X509ExtensionCollectionPtr : public System::SmartPtr<X509ExtensionCollection>
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | एक अंडरलाइन संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| auto [begin](../../system/smartptr/begin/)() const | एक अंडरलाइन संग्रह के [begin()](../../system/smartptr/begin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [begin()](../../system/smartptr/begin/) मेथड हो। |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | पॉइंटर को स्वयं के प्रकार में कास्ट करता है। |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | स्थैटिक-कास्ट का प्रयोग करके पॉइंटर को बेस प्रकार में कास्ट करता है। |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | डायनमिक-कास्ट का प्रयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | डायनमिक-कास्ट का प्रयोग करके पॉइंटर को डेराइव्ड प्रकार में कास्ट करता है। |
| auto [cbegin](../../system/smartptr/cbegin/)() const | एक अंडरलाइन संग्रह के [cbegin()](../../system/smartptr/cbegin/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cbegin()](../../system/smartptr/cbegin/) मेथड हो। |
| auto [cend](../../system/smartptr/cend/)() const | एक अंडरलाइन संग्रह के [cend()](../../system/smartptr/cend/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [cend()](../../system/smartptr/cend/) मेथड हो। |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | संकित वस्तु पर const_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | संकित वस्तु पर dynamic_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| auto [end](../../system/smartptr/end/)() | एक अंडरलाइन संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../../system/smartptr/end/) मेथड हो। |
| auto [end](../../system/smartptr/end/)() const | एक अंडरलाइन संग्रह के [end()](../../system/smartptr/end/) मेथड के लिए अभिगमकर्ता। केवल तभी संकलित होता है जब SmartPtr_ विशेषीकरण प्रकार हो जिसमें [end()](../../system/smartptr/end/) मेथड हो। |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | इशारा किए गए वस्तु को प्राप्त करता है। |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | पॉइंटर मोड को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | इशारा किए गए वस्तु को प्राप्त करता है, लेकिन यह सत्यापित करता है कि पॉइंटर साझा मोड में है। |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | संदर्भित वस्तु के लिए मौजूद साझा पॉइंटर्स की संख्या (वर्तमान सहित) प्राप्त करता है। सत्यापित करता है कि वर्तमान पॉइंटर साझा मोड में है। |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | [GetHashCode()](../../system/smartptr/gethashcode/) को इशारा किए गए वस्तु पर कॉल करता है। |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | वर्तमान में संदर्भित वस्तु (यदि कोई हो) प्राप्त करता है या अपवाद फेंकता है। |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | इशारा किए गए वस्तु (यदि कोई हो) या nullptr प्राप्त करता है। समान है [get()](../../system/smartptr/get/)। |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | संदर्भित वस्तु को प्राप्त करता है। |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | इशारा किए गए वस्तु (यदि कोई हो) या nullptr प्राप्त करता है। समान है [get()](../../system/smartptr/get/)। |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि इशारा किया गया वस्तु विशिष्ट प्रकार का है या उसका चाइल्ड प्रकार। C# 'is' सेमान्टिक का पालन करता है। |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | जांचता है कि पॉइंटर किसी अन्य वस्तु की ओर इशारा कर रहा है जो स्वामित्व नहीं रखती (एलियासिंग कंस्ट्रक्टर द्वारा निर्मित)। |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | जांचता है कि पॉइंटर साझा मोड में है। |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | जांचता है कि पॉइंटर कमजोर मोड में है। |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | जांचता है कि पॉइंटर null नहीं है। |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | जांचता है कि पॉइंटर null है। |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | इशारा किए गए वस्तु का संदर्भ प्राप्त करता है। सत्यापित करता है कि पॉइंटर null नहीं है। |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | संदर्भित वस्तु के सदस्य तक पहुँच की अनुमति देता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक प्रदान करता है। |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | [SmartPtr](../../system/smartptr/) क्लास के लिए कम-तुलना सेमांटिक प्रदान करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | [SmartPtr](../../system/smartptr/) वस्तु को मूव-असाइन करता है। x अब उपयोग योग्य नहीं रहता। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी-असाइन करता है। आवश्यक प्रकार रूपांतरण करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | [SmartPtr](../../system/smartptr/) वस्तु को कच्चा पॉइंटर असाइन करता है। |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | पॉइंटर का मान nullptr सेट करता है। |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | जांचता है कि पॉइंटर nullptr की ओर इशारा कर रहा है। |
| [SharedPtr](../../system/sharedptr/)\<[X509Extension](../x509extension/)\>\& [operator[]](./operator[]/)(**int32_t**) const | अभिगमकर्ता। |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | एलियासिंग (एलियासिंग कंस्ट्रक्टर द्वारा निर्मित) को पॉइंटर से हटाता है, सुनिश्चित करता है कि यह (यदि साझा) या (यदि कमजोर) वही वस्तु प्रबंधित/ट्रैक करे जो यह इशारा करता है। |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | इशारा किए गए वस्तु को सेट करता है। |
| void [reset](../../system/smartptr/reset/)() | पॉइंटर को nullptr की ओर इशारा करने के लिए बनाता है। |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | पॉइंटर मोड सेट करता है। संदर्भित वस्तु के रेफ़रेंस काउंट को बदल सकता है। |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | इशारा किए गए वस्तु (यदि कोई हो) पर SetTemplateWeakPtr() मेथड को कॉल करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | आवश्यक मोड का null-pointer [SmartPtr](../../system/smartptr/) वस्तु बनाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | निर्दिष्ट वस्तु की ओर संकेत करने वाला [SmartPtr](../../system/smartptr/) बनाता है, या कच्चे पॉइंटर को [SmartPtr](../../system/smartptr/) में परिवर्तित करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में उसी वस्तु की ओर इशारा करेंगे। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को कॉपी कंस्ट्रक्ट करता है। दोनों पॉइंटर बाद में उसी वस्तु की ओर इशारा करेंगे। यदि अनुमति हो तो प्रकार रूपांतरण करता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) वस्तु को मूव कंस्ट्रक्ट करता है। प्रभावी रूप से दो पॉइंटरों की अदला-बदली करता है, यदि वे दोनों समान मोड के हों। कॉल के बाद x उपयोग योग्य नहीं रह सकता। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | विभिन्न प्रकार का नया एरे बनाकर संदर्भित एरे का प्रकार बदलता है। उपयोगी जब C# में एरे प्रकार कास्ट मौजूद हो जो C++ में समर्थित नहीं है। |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | खाली एरे को प्रारंभ करता है। कुछ C# कोड निर्माणों का अनुवाद करने के लिए उपयोग किया जाता है। |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | [SmartPtr](../../system/smartptr/) बनाता है जो ptr के प्रारम्भिक मान के साथ स्वामित्व जानकारी साझा करता है, पर एक असंबंधित और अनप्रबंधित पॉइंटर p रखता है। |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | इशारा किए गए वस्तु पर static_cast का उपयोग करके पॉइंटर को अलग प्रकार में कास्ट करता है। |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | किसी भी पॉइंटर प्रकार को [Object](../../system/object/) के पॉइंटर में बदलता है। Pointee_ प्रकार के पूर्ण होने की आवश्यकता नहीं है। |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Pointee_ प्रकार के लिए [System::TypeInfo](../../system/typeinfo/) वस्तु प्राप्त करने का शॉर्टकट। |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)() | null पॉइंटर कंस्ट्रक्टर। |
|  [X509ExtensionCollectionPtr](./x509extensioncollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509ExtensionCollection](../x509extensioncollection/)\>\&) | कंस्ट्रक्टर। |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | [SmartPtr](../../system/smartptr/) वस्तु को नष्ट करता है। यदि आवश्यक हो तो इशारा किए गए वस्तु के रेफ़रेंस काउंटर को घटाता है और वस्तु को हटाता है। |

## देखें

* क्लास [SmartPtr](../../system/smartptr/)
* नामस्थान [System::Security::Cryptography::X509Certificates](../)
* लाइब्रेरी [Aspose.Slides](../../)
---
title: PropertyInfo
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: प्रॉपर्टी जानकारी का प्रतिनिधित्व करता है।
type: docs
weight: 144
url: /hi/system.reflection/propertyinfo/
---
## PropertyInfo क्लास

प्रॉपर्टी जानकारी का प्रतिनिधित्व करता है।

```cpp
class PropertyInfo : public System::Reflection::MemberInfo
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | संग्रह में गुण जोड़ता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थवाक्य का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली का फ्लोटिंग पॉइंट तुलना अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, इसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | घोषित प्रकार प्राप्त करता है। |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | सदस्य का पूर्ण नाम प्राप्त करता है। यह मैन्युअली लागू भागों में अलग हो सकता है। |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | एक MemberTypes मान प्राप्त करता है जो दर्शाता है कि यह सदस्य एक प्रॉपर्टी है। |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | सदस्य का नाम प्राप्त करता है। |
| [TypeInfo](../../system/typeinfo/) [get_PropertyType](./get_propertytype/)() | प्रॉपर्टी प्रकार प्राप्त करता है। |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | परावर्तित प्रकार प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा संरचना प्राप्त करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | एक एरे लौटाता है जिसमें वे वस्तुएँ होती हैं जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए टाइप पर लागू सभी कस्टम एट्रीब्यूट्स को दर्शाती हैं। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | एक एरे लौटाता है जिसमें वे वस्तुएँ होती हैं जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए टाइप पर लागू सभी कस्टम एट्रीब्यूट्स को दर्शाती हैं। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) विधि का समानार्थी। कस्टम वस्तुओं के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानार्थी। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | विशिष्ट ऑब्जेक्ट से प्रॉपर्टी मान प्राप्त करता है। |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [GetValue](./getvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | विशिष्ट ऑब्जेक्ट से प्रॉपर्टी मान प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का समानार्थी। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट के लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) विधि का समानार्थी। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को प्रारंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक रूप से कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट प्रारंभ करता है और सबक्लास कॉपी निर्माण को सक्षम करता है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | कन्स्ट्रक्टर। केवल const गेटर वाली प्रॉपर्टी। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | कन्स्ट्रक्टर। केवल non-const गेटर वाली प्रॉपर्टी। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)() const) | कन्स्ट्रक्टर। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)()) | कन्स्ट्रक्टर। [Nullable](../../system/nullable/) प्रॉपर्टी जिसमें सेट्टर और गेटर दोनों हैं। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Nullable](../../system/nullable/)\<NullableType\>), [System::Nullable](../../system/nullable/)\<NullableType\>(ClassType::*)() const) | कन्स्ट्रक्टर। [Nullable](../../system/nullable/) प्रॉपर्टी जिसमें केवल const गेटर है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::SharedPtr](../../system/sharedptr/)\<PropertyType\>), [System::SharedPtr](../../system/sharedptr/)\<PropertyType\>(ClassType::*)()) | कन्स्ट्रक्टर। [Object](../../system/object/) प्रॉपर्टी जिसमें केवल गेटर है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)()) | स्ट्रिंग प्रॉपर्टी जानकारी बनाता है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::String](../../system/string/)), [System::String](../../system/string/)(ClassType::*)() const) | क्लास से स्ट्रिंग प्रॉपर्टी जानकारी बनाता है जिसमें const गेटर है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)()) | [Decimal](../../system/decimal/) प्रॉपर्टी जानकारी बनाता है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)([System::Decimal](../../system/decimal/)), [System::Decimal](../../system/decimal/)(ClassType::*)() const) | क्लास से [Decimal](../../system/decimal/) प्रॉपर्टी जानकारी बनाता है जिसमें const गेटर है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)()) | बूलियन प्रॉपर्टी जानकारी बनाता है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**bool**), **bool**(ClassType::*)() const) | क्लास से बूलियन प्रॉपर्टी जानकारी बनाता है जिसमें const गेटर है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)()) | **int64_t** प्रॉपर्टी जानकारी बनाता है। |
|  [PropertyInfo](./propertyinfo/)([String](../../system/string/), void(ClassType::*)(**int64_t**), **int64_t**(ClassType::*)() const) | क्लास से **int64_t** प्रॉपर्टी जानकारी बनाता है जिसमें const गेटर है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना nullptr के साथ करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकरण स्ट्रिंग और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) की विशेषीकरण स्ट्रिंग्स के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट घटाता है। |
| void [set_PropertyType](./set_propertytype/)(const [TypeInfo](../../system/typeinfo/)\&) | इस प्रॉपर्टी का प्रकार सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | विशिष्ट ऑब्जेक्ट के लिए प्रॉपर्टी मान सेट करता है। |
| void [SetValue](./setvalue/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>) | विशिष्ट ऑब्जेक्ट के लिए प्रॉपर्टी मान सेट करता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) विधि का समानार्थी। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करना-enabled करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट के अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |

## देखें

* क्लास [MemberInfo](../memberinfo/)
* नामस्थान [System::Reflection](../)
* लाइब्रेरी [Aspose.Slides](../../)
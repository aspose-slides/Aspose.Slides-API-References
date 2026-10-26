---
title: TypeInfo
second_title: Aspose.Slides for C++ API संदर्भ
description: किसी विशेष प्रकार का प्रतिनिधित्व करता है और उसके बारे में जानकारी प्रदान करता है।
type: docs
weight: 1379
url: /hi/system/typeinfo/
---
## TypeInfo क्लास

किसी विशिष्ट प्रकार का प्रतिनिधित्व करता है और इसके बारे में जानकारी प्रदान करता है।

```cpp
class TypeInfo
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [AddAttribute](./addattribute/)(const [ObjectPtr](../smartptr/)\&) | निर्दिष्ट विशेषता को प्रकार की विशेषताओं की सूची में जोड़ता है। |
| void [AddDefaultConstructor](./adddefaultconstructor/)() | प्रकार T के लिए डिफ़ॉल्ट कन्स्ट्रक्टर सेट करता है। |
| void [AddDefaultConstructor](./adddefaultconstructor/)([DefaultConstructor](./defaultconstructor/)) | क्लास का इंस्टेंस बनाने वाले फ़ंक्टर द्वारा डिफ़ॉल्ट कन्स्ट्रक्टर सेट करता है। |
| void [AddMember](./addmember/)(const [SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\&) | निर्दिष्ट सदस्य को प्रकार के सदस्यों की सूची में जोड़ता है। |
| static const [TypeInfo](./)\& [BoxedValueType](./boxedvaluetype/)() | एक अद्वितीय [TypeInfo](./) संरचना प्रदान करता है जिसे **BoxedValue** प्रकार के लिए कई Boxed* क्लासों द्वारा साझा किया जा सकता है। |
| **bool** [Equals](./equals/)(const [TypeInfo](./)\&) const |  |
| [System::SharedPtr](../sharedptr/)\<[System::Reflection::Assembly](../../system.reflection/assembly/)\> [get_Assembly](./get_assembly/)() const | नहीं लागू किया गया। वर्तमान ऑब्जेक्ट द्वारा प्रदर्शित प्रकार की घोषणा वाले असेंबली का पॉइंटर लौटाता है। |
| [String](../string/) [get_AssemblyQualifiedName](./get_assemblyqualifiedname/)() const | नहीं लागू किया गया। वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार का पूर्ण रूप से योग्य नाम (परन्तु असेंबली नाम के बिना) लौटाता है। |
| [TypeInfo](./) [get_BaseType](./get_basetype/)() const | बेस प्रकार विवरणकर्ता लौटाता है। |
| **bool** [get_ContainsGenericParameters](./get_containsgenericparameters/)() const | एक मान प्राप्त करता है जो इंगित करता है कि वर्तमान Type ऑब्जेक्ट में ऐसे प्रकार पैरामीटर हैं जो विशिष्ट प्रकारों द्वारा प्रतिस्थापित नहीं हुए हैं। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [get_DeclaredMember](./get_declaredmember/)(const [String](../string/)\&) const | निर्दिष्ट नाम वाले सदस्यों की सूची प्राप्त करता है। |
| [String](../string/) [get_FullName](./get_fullname/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार का पूर्ण रूप से योग्य नाम (परन्तु असेंबली नाम के बिना) लौटाता है। |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [get_GenericTypeArguments](./get_generictypearguments/)() const | इस प्रकार के लिए जनेरिक प्रकार तर्कों की एक एरे प्राप्त करता है। |
| **bool** [get_IsAbstract](./get_isabstract/)() const | एक मान प्राप्त करता है जो इंगित करता है कि Type सारभूत (abstract) है और इसे ओवरराइड किया जाना चाहिए। |
| **bool** [get_IsArray](./get_isarray/)() const | एक मान प्राप्त करता है जो दर्शाता है कि प्रकार एक एरे है। |
| **bool** [get_IsClass](./get_isclass/)() const | एक मान प्राप्त करता है जो इंगित करता है कि Type एक क्लास या डेलिगेट है; अर्थात, मान प्रकार या इंटरफ़ेस नहीं है। |
| **bool** [get_IsEnum](./get_isenum/)() const | एक मान प्राप्त करता है जो इंगित करता है कि वर्तमान Type एक एन्उमेरशन का प्रतिनिधित्व करता है। |
| **bool** [get_IsGenericType](./get_isgenerictype/)() const |  |
| **bool** [get_IsGenericTypeDefinition](./get_isgenerictypedefinition/)() const | एक मान प्राप्त करता है जो इंगित करता है कि वर्तमान Type एक जनेरिक टाइप डिफिनिशन का प्रतिनिधित्व करता है, जिससे अन्य जनेरिक टाइप बनाए जा सकते हैं। |
| **bool** [get_IsInterface](./get_isinterface/)() const | एक मान प्राप्त करता है जो इंगित करता है कि Type एक इंटरफ़ेस है; अर्थात, क्लास या मान प्रकार नहीं। |
| **bool** [get_IsSealed](./get_issealed/)() const | एक मान प्राप्त करता है जो इंगित करता है कि Type को sealed घोषित किया गया है। |
| **bool** [get_IsValueType](./get_isvaluetype/)() const | एक मान प्राप्त करता है जो दर्शाता है कि Type एक मूल्य प्रकार (value type) है। |
| **bool** [get_IsVisible](./get_isvisible/)() const | एक मान प्राप्त करता है जो इंगित करता है कि Type को assembly के बाहर के कोड द्वारा पहुँचा जा सकता है। |
| [String](../string/) [get_Name](./get_name/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार का नाम लौटाता है। |
| [String](../string/) [get_Namespace](./get_namespace/)() const | Type का नेमस्पेस प्राप्त करता है। |
| [SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\> [GetConstructor](./getconstructor/)(const [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\>\&) const | निर्दिष्ट एरे में प्रकारों से मेल खाने वाले पैरामीटर वाले सार्वजनिक इंस्टेंस कन्स्ट्रक्टर को खोजता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | निर्दिष्ट BindingFlags का उपयोग करके वर्तमान Type के लिए परिभाषित कन्स्ट्रक्टर्स को खोजता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::ConstructorInfo](../../system.reflection/constructorinfo/)\>\> [GetConstructors](./getconstructors/)() const | वर्तमान Type के लिए परिभाषित सभी सार्वजनिक कन्स्ट्रक्टर्स को लौटाता है। |
| [ObjectPtr](../smartptr/) [GetCustomAttribute](./getcustomattribute/)(const [TypeInfo](./)\&) const | निर्दिष्ट प्रकार के लागू कस्टम एट्रिब्यूट को खोजता है जो वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार पर लागू हुआ है। |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)() const | एक एरे लौटाता है जिसमें उन सभी कस्टम एट्रिब्यूट्स के ऑब्जेक्ट्स होते हैं जो प्रकार पर लागू किए गए हैं। |
| [ArrayPtr](../arrayptr/)\<[ObjectPtr](../smartptr/)\> [GetCustomAttributes](./getcustomattributes/)(const [TypeInfo](./)\&, **bool**) const | एक एरे लौटाता है जिसमें उन विशिष्ट एट्रिब्यूट्स के ऑब्जेक्ट्स होते हैं जो प्रकार पर लागू किए गए हैं। |
| [TypeInfo](./) [GetElementType](./getelementtype/)() const | नहीं लागू किया गया। |
| [SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\> [GetField](./getfield/)(const [System::String](../string/)\&, [System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | निर्दिष्ट बाइंडिंग सीमाओं का उपयोग करके निर्दिष्ट फ़ील्ड को खोजता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::FieldInfo](../../system.reflection/fieldinfo/)\>\> [GetFields](./getfields/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | निर्दिष्ट बाइंडिंग सीमाओं का उपयोग करके वर्तमान Type के लिए परिभाषित फ़ील्ड्स को खोजता है। |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetGenericArguments](./getgenericarguments/)() const | इस प्रकार के लिए जनेरिक टाइप तर्कों की एरे प्राप्त करता है। |
| int [GetHashCode](./gethashcode/)() const | इस इंस्टेंस से जुड़ा हुआ हैश कोड लौटाता है। |
| [ArrayPtr](../arrayptr/)\<[TypeInfo](./)\> [GetInterfaces](./getinterfaces/)() const | वर्तमान Type द्वारा लागू या विरासत में प्राप्त सभी इंटरफ़ेस प्राप्त करता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::MemberInfo](../../system.reflection/memberinfo/)\>\> [GetMember](./getmember/)(const [String](../string/)\&) const | निर्दिष्ट नाम वाले सदस्यों की सूची प्राप्त करता है। |
| [SharedPtr](../sharedptr/)\<[System::Reflection::MethodInfo](../../system.reflection/methodinfo/)\> [GetMethod](./getmethod/)(const [String](../string/)\&) const | निर्दिष्ट नाम का मेथड प्राप्त करता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)() const | वर्तमान Type की सभी सार्वजनिक प्रॉपर्टीज़ को लौटाता है। |
| [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[System::Reflection::PropertyInfo](../../system.reflection/propertyinfo/)\>\> [GetProperties](./getproperties/)([System::Reflection::BindingFlags](../../system.reflection/bindingflags/)) const | निर्दिष्ट बाइंडिंग सीमाओं का उपयोग करके वर्तमान Type की प्रॉपर्टीज़ को खोजता है। |
| [TypeInfo](./) [GetTemplParamType](./gettemplparamtype/)() const | टेम्पलेट पैरामीटर प्रकार विवरणकर्ता प्राप्त करता है। |
| **uint32_t** [Hash](./hash/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार से जुड़ा हैश वैल्यू लौटाता है। |
| **bool** [IsAssignableFrom](./isassignablefrom/)(const [TypeInfo](./)\&) const | निर्धारित करता है कि क्या निर्दिष्ट प्रकार का एक इंस्टेंस वर्तमान प्रकार के चर को असाइन किया जा सकता है। |
| **bool** [IsDefined](./isdefined/)(const [TypeInfo](./)\&, **bool**) const | नहीं लागू किया गया। इंगित करता है कि निर्दिष्‍ट प्रकार या उसके डेरिव्ड प्रकारों के एक या अधिक एट्रिब्यूट्स इस सदस्य पर लागू हैं। |
| **bool** [IsInstanceOfType](./isinstanceoftype/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | निर्धारित करता है कि क्या निर्दिष्ट ऑब्जेक्ट वर्तमान प्रकार का इंस्टेंस है। |
| **bool** [IsSubclassOf](./issubclassof/)(const [TypeInfo](./)\&) const | निर्धारित करता है कि क्या वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किया गया प्रकार निर्दिष्ट क्लास का उपवर्ग है। |
| **bool** [operator!=](./operator_not_equal/)(const [TypeInfo](./)\&) const | निर्धारित करता है कि क्या वर्तमान और निर्दिष्ट [TypeInfo](./) ऑब्जेक्ट समान नहीं हैं। |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | निर्धारित करता है कि क्या वर्तमान [TypeInfo](./) ऑब्जेक्ट null नहीं है, अर्थात यह किसी प्रकार का प्रतिनिधित्व करता है। |
| **bool** [operator==](./operator_equal_equal/)(const [TypeInfo](./)\&) const | निर्धारित करता है कि क्या वर्तमान और निर्दिष्ट [TypeInfo](./) ऑब्जेक्ट समान हैं। |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | निर्धारित करता है कि क्या वर्तमान [TypeInfo](./) ऑब्जेक्ट null है, अर्थात यह किसी भी प्रकार का प्रतिनिधित्व नहीं करता। |
| void [reset](./reset/)() | [TypeInfo](./) को null सेट करता है। |
| void [set_IsValueType](./set_isvaluetype/)(**bool**) | एक मान सेट करता है जो इंगित करता है कि Type एक वैल्यू टाइप है। |
| void [SetBaseType](./setbasetype/)(GetTypeInfoFunPtr) | बेस टाइप विवरणकर्ता सेट करता है। |
| void [SetTemplParamType](./settemplparamtype/)(const [TypeInfo](./)\&) | टेम्पलेट पैरामीटर टाइप विवरणकर्ता सेट करता है। |
| static **uint32_t** [StringHash](./stringhash/)(const char_t *) | निर्दिष्ट स्ट्रिंग के लिए हैश कैलकुलेट करता है। |
| [String](../string/) [ToString](./tostring/)() const | वर्तमान ऑब्जेक्ट द्वारा प्रतिनिधित्व किए गए प्रकार का नाम युक्त स्ट्रिंग लौटाता है। |
| static const [TypeInfo](./)\& [Type](./type/)() | एक [TypeInfo](./) ऑब्जेक्ट लौटाता है जो [TypeInfo](./) क्लास का प्रतिनिधित्व करता है। |
|  [TypeInfo](./typeinfo/)() | डिफ़ॉल्ट कन्स्ट्रक्टर (कोई प्रकार सेट नहीं)। |
|  [TypeInfo](./typeinfo/)(std::nullptr_t) | नल ऑब्जेक्ट कन्स्ट्रक्टर (कोई प्रकार सेट नहीं)। |
|  [TypeInfo](./typeinfo/)(const char_t *) | कन्स्ट्रक्टर। |
|  [TypeInfo](./typeinfo/)(const char_t *, **uint32_t**) | कन्स्ट्रक्टर। |
|  [TypeInfo](./typeinfo/)(const std::type_info\&) | कन्स्ट्रक्टर। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [EmptyType](./emptytype/) | खाली सूची का प्रतिनिधित्व करने वाला स्थिरांक [TypeInfo](./)। |
| static [EmptyTypes](./emptytypes/) | खाली सूची का प्रतिनिधित्व करने वाला स्थिरांक [TypeInfo](./)। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [DefaultConstructor](./defaultconstructor/) | टाइप को कन्स्ट्रक्ट करने के लिए फ़ंक्शन पॉइंटर। |

## और देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)
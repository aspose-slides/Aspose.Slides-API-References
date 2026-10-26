---
title: XmlSchemaSet
second_title: Aspose.Slides for C++ API संदर्भ
description: XML स्कीमा डिफ़िनिशन लैंग्वेज (XSD) स्कीमा का कैश रखता है।
type: docs
weight: 781
url: /hi/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet क्लास

Contains a cache of XML [Schema](../) definition language (XSD) schemas.

```cpp
class XmlSchemaSet : public System::Object
```

## विधियां

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | निर्दिष्ट URL पर XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को [XmlSchemaSet](./) में जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | [XmlReader](../../system.xml/xmlreader/) में मौजूद XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को [XmlSchemaSet](./) में जोड़ता है। |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | दिए गए [XmlSchemaSet](./) में सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को [XmlSchemaSet](./) में जोड़ता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | दिए गए [XmlSchema](../xmlschema/) को [XmlSchemaSet](./) में जोड़ता है। |
| void [Compile](./compile/)() | XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को, जो [XmlSchemaSet](./) में जोड़े गए हैं, एक तार्किक स्कीमा में संकलित करता है। |
| **bool** [Contains](./contains/)([String](../../system/string/)) | निर्दिष्ट लक्ष्य नेमस्पेस URI वाले XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा [XmlSchemaSet](./) में है या नहीं दर्शाता है। |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | निर्दिष्ट XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) [XmlSchema](../xmlschema/) ऑब्जेक्ट [XmlSchemaSet](./) में है या नहीं दर्शाता है। |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | सभी [XmlSchema](../xmlschema/) ऑब्जेक्ट को [XmlSchemaSet](./) से दिए गए एरे में कॉपी करता है, निर्दिष्ट इंडेक्स से शुरू करके। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-स्टाइल फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | [XmlSchemaSet](./) के लिए [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) वापस करता है। |
| **int32_t** [get_Count](./get_count/)() | [XmlSchemaSet](./) में तार्किक XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा की संख्या लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | [XmlSchemaSet](./) में सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा में सभी ग्लोबल एट्रिब्यूट्स लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | [XmlSchemaSet](./) में सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा में सभी ग्लोबल एलेमेंट्स लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | [XmlSchemaSet](./) में सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा में सभी ग्लोबल सरल और कॉम्प्लेक्स टाइप्स लौटाता है। |
| **bool** [get_IsCompiled](./get_iscompiled/)() | दर्शाता है कि [XmlSchemaSet](./) में XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा संकलित किए गए हैं या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | नया XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा लोड करते समय [XmlSchemaSet](./) द्वारा उपयोग किया जाने वाला डिफ़ॉल्ट [XmlNameTable](../../system.xml/xmlnametable/) लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबंधित रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्यटाइप द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असignment ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | निर्दिष्ट XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को [XmlSchemaSet](./) से हटाता है। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | निर्दिष्ट XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा और वह सभी स्कीमा जिन्हें वह इम्पोर्ट करता है, को [XmlSchemaSet](./) से हटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा को फिर से प्रोसेस करता है जो पहले से [XmlSchemaSet](./) में मौजूद है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | [XmlSchemaSet](./) में सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा का संग्रह लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | दिए गए नेमस्पेस से संबंधित सभी XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा का संग्रह [XmlSchemaSet](./) में लौटाता है। |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | [XmlSchemaSet](./) के लिए [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/) सेट करता है। |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | स्कीमा के include और import तत्वों में संदर्भित नेमस्पेस या लोकेशन्स को रिजॉल्व करने के लिए उपयोग किया जाने वाला [XmlResolver](../../system.xml/xmlresolver/) सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (शेयर किए गए के बजाय) के रूप में सेट करता है। कंटेनर्स में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और वापस करता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा वैलिडेशन त्रुटियों के बारे में जानकारी प्राप्त करने के लिए इवेंट हैंडलर जोड़ता है। |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | XML [Schema](../) डिफ़िनिशन लैंग्वेज (XSD) स्कीमा वैलिडेशन त्रुटियों के बारे में जानकारी प्राप्त करने के लिए इवेंट हैंडलर हटाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं करना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaSet](./xmlschemaset/)() | [XmlSchemaSet](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | निर्दिष्ट [XmlNameTable](../../system.xml/xmlnametable/) के साथ [XmlSchemaSet](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की एक इंस्टेंस के लिए साझा पॉइंटर का उपनाम है। |

## टिप्पणियाँ

Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## संबंधित देखें

* क्लास [Object](../../system/object/)
* नामस्थान [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
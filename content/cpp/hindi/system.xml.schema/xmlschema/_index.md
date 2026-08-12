---
title: XmlSchema
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: XML Schema का इन-मेमारी प्रतिनिधित्व, जैसा कि World Wide Web Consortium (W3C) और . में निर्दिष्ट किया गया है।
type: docs
weight: 79
url: /hi/system.xml.schema/xmlschema/
---
## XmlSchema क्लास

एक इन मेमोरी प्रतिनिधित्व है XML [Schema](../) का, जैसा कि World Wide [Web](../../system.web/) Consortium (W3C) [XML Schema Part 1: Structures](https://www.w3.org/TR/xmlschema-1/) और [XML Schema Part 2: Datatypes](https://www.w3.org/TR/xmlschema-2/) में निर्दिष्ट है।

```cpp
class XmlSchema : public System::Xml::Schema::XmlSchemaObject
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/)) | XML [Schema](../)[Object](../../system/object/) मॉडल (SOM) को स्कीमा सूचना में कम्पाइल करता है मान्यता के लिए। प्रोग्रामेटिक रूप से निर्मित SOM की सिन्टैक्टिक और सेमेंटिक संरचना की जाँच के लिए उपयोग किया जाता है। संसेमिक वैधता जाँच संकलन के दौरान की जाती है। |
| void [Compile](./compile/)([ValidationEventHandler](../validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlResolver](../../system.xml/xmlresolver/)\>\&) | XML [Schema](../)[Object](../../system/object/) मॉडल (SOM) को स्कीमा सूचना में कम्पाइल करता है मान्यता के लिए। प्रोग्रामेटिक रूप से निर्मित SOM की सिन्टैकटिक और सेमेंटिक संरचना की जाँच के लिए उपयोग किया जाता है। संसेमिक वैधता जाँच संकलन के दौरान की जाती है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान, सहित NaN, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [XmlSchemaForm](../xmlschemaform/) [get_AttributeFormDefault](./get_attributeformdefault/)() | स्कीमा के लक्ष्य नेमस्पेस में घोषित एट्रिब्यूट्स के फ़ॉर्म लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | स्कीमा में सभी ग्लोबल एट्रिब्यूट समूहों का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Attributes](./get_attributes/)() | स्कीमा में सभी एट्रिब्यूट्स का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockDefault](./get_blockdefault/)() | स्कीमा के **targetNamespace** में तत्व और जटिल प्रकारों पर **block** एट्रिब्यूट का डिफ़ॉल्ट मान सेट करने वाला **blockDefault** एट्रिब्यूट लौटाता है। |
| [XmlSchemaForm](../xmlschemaform/) [get_ElementFormDefault](./get_elementformdefault/)() | स्कीमा के लक्ष्य नेमस्पेस में घोषित तत्वों के फ़ॉर्म लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Elements](./get_elements/)() | स्कीमा में सभी तत्वों का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalDefault](./get_finaldefault/)() | स्कीमा के लक्ष्य नेमस्पेस में तत्व और जटिल प्रकारों पर **final** एट्रिब्यूट का डिफ़ॉल्ट मान सेट करने वाला **finalDefault** एट्रिब्यूट लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | स्कीमा में सभी समूहों का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [String](../../system/string/) [get_Id](./get_id/)() | स्ट्रिंग ID लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Includes](./get_includes/)() | समाविष्ट और आयातित स्कीमा का संग्रह लौटाता है। |
| **bool** [get_IsCompiled](./get_iscompiled/)() | यह संकेत देता है कि स्कीमा को कम्पाइल किया गया है या नहीं। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | स्कीमा में स्कीमा तत्वों का संग्रह लौटाता है और **schema** तत्व स्तर पर नए तत्व प्रकार जोड़ने के लिए उपयोग किया जाता है। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | फ़ाइल में वह लाइन नंबर लौटाता है जिससे **schema** तत्व संबद्ध है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | फ़ाइल में वह लाइन स्थिति लौटाता है जिससे **schema** तत्व संबद्ध है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Notations](./get_notations/)() | स्कीमा में सभी नोटेशन का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | स्कीमा में सभी स्कीमा प्रकारों का पोस्ट-स्कीमा-कम्पाइलेशन मान लौटाता है। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | स्कीमा को लोड करने वाली फ़ाइल की स्रोत स्थिति लौटाता है। |
| [String](../../system/string/) [get_TargetNamespace](./get_targetnamespace/)() | स्कीमा लक्ष्य नेमस्पेस का यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI) लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](./get_unhandledattributes/)() | स्कीमा लक्ष्य नेमस्पेस से संबंधित न होने वाले योग्य एट्रिब्यूट्स लौटाता है। |
| [String](../../system/string/) [get_Version](./get_version/)() | स्कीमा का संस्करण लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | प्रदान किए गए [IO::TextReader](../../system.io/textreader/) से एक XML [Schema](../) पढ़ता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | प्रदान किए गए स्ट्रीम से एक XML [Schema](../) पढ़ता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchema](./)\> [Read](./read/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, [ValidationEventHandler](../validationeventhandler/)) | प्रदान किए गए [XmlReader](../../system.xml/xmlreader/) से एक XML [Schema](../) पढ़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यु टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_AttributeFormDefault](./set_attributeformdefault/)([XmlSchemaForm](../xmlschemaform/)) | स्कीमा के लक्ष्य नेमस्पेस में घोषित एट्रिब्यूट्स के फ़ॉर्म को सेट करता है। |
| void [set_BlockDefault](./set_blockdefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **targetNamespace** में तत्व और जटिल प्रकारों पर **block** एट्रिब्यूट का डिफ़ॉल्ट मान सेट करने वाला **blockDefault** एट्रिब्यूट सेट करता है। |
| void [set_ElementFormDefault](./set_elementformdefault/)([XmlSchemaForm](../xmlschemaform/)) | स्कीमा के लक्ष्य नेमस्पेस में घोषित तत्वों के फ़ॉर्म को सेट करता है। |
| void [set_FinalDefault](./set_finaldefault/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | लक्ष्य नेमस्पेस में तत्व और जटिल प्रकारों पर **final** एट्रिब्यूट का डिफ़ॉल्ट मान सेट करने वाला **finalDefault** एट्रिब्यूट सेट करता है। |
| void [set_Id](./set_id/)(const [String](../../system/string/)\&) | स्ट्रिंग ID सेट करता है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** तत्व द्वारा संदर्भित फ़ाइल में लाइन नंबर सेट करता है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** तत्व द्वारा संदर्भित फ़ाइल में लाइन पोज़िशन सेट करता है। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | स्कीमा को लोड करने वाली फ़ाइल की स्रोत स्थिति सेट करता है। |
| void [set_TargetNamespace](./set_targetnamespace/)(const [String](../../system/string/)\&) | स्कीमा लक्ष्य नेमस्पेस का यूनिफ़ॉर्म रिसोर्स आइडेंटिफ़ायर (URI) सेट करता है। |
| void [set_UnhandledAttributes](./set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | स्कीमा लक्ष्य नेमस्पेस से संबंधित न होने वाले योग्य एट्रिब्यूट्स सेट करता है। |
| void [set_Version](./set_version/)(const [String](../../system/string/)\&) | स्कीमा का संस्करण सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nवें टेम्प्लेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | प्रदान किए गए डेटा स्ट्रीम में XML [Schema](../) लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | प्रदान किए गए स्ट्रीम में निर्दिष्ट [XmlNamespaceManager](../../system.xml/xmlnamespacemanager/) का उपयोग करके XML [Schema](../) लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | प्रदान किए गए [IO::TextWriter](../../system.io/textwriter/) में XML [Schema](../) लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | प्रदान किए गए TextWriter में XML [Schema](../) लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | प्रदान किए गए [XmlWriter](../../system.xml/xmlwriter/) में XML [Schema](../) लिखता है। |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../../system.xml/xmlnamespacemanager/)\>\&) | प्रदान किए गए [XmlWriter](../../system.xml/xmlwriter/) में XML [Schema](../) लिखता है। |
|  [XmlSchema](./xmlschema/)() | [XmlSchema](./) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [InstanceNamespace](./instancenamespace/) | XML स्कीमा इंस्टेंस नेमस्पेस। यह फ़ील्ड स्थिर है। |
| static [Namespace](./namespace/) | XML स्कीमा नेमस्पेस। यह फ़ील्ड स्थिर है। |

## टाइपडिफ़

| टाइपडिफ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की इंस्टेंस के साझा पॉइंटर के लिए एक उपनाम। |

## टिप्पणी

इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि यह रनटाइम त्रुटियों और/या एसर्शन फ़ॉल्ट्स का कारण बनता है। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन आर्ग्यूमेंट के रूप में पास करें।

## देखें

* क्लास [XmlSchemaObject](../xmlschemaobject/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
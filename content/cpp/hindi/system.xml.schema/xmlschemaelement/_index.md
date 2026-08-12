---
title: XmlSchemaElement
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: World Wide Web Consortium (W3C) द्वारा निर्धारित XML Schema से element तत्व का प्रतिनिधित्व करता है। यह क्लास सभी कण प्रकारों के लिए बेस क्लास है और XML दस्तावेज़ में एक तत्व का वर्णन करने के लिए उपयोग की जाती है।
type: docs
weight: 365
url: /hi/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement क्लास


XML [Schema](../) से **element** तत्व का प्रतिनिधित्व करता है जैसा कि World Wide [Web](../../system.web/) Consortium (W3C) द्वारा निर्दिष्ट किया गया है। यह क्लास सभी कण प्रकारों के लिए बेस क्लास है और XML दस्तावेज़ में एक तत्व का वर्णन करने के लिए उपयोग की जाती है।

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमान्टिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** प्रॉपर्टी को लौटाता है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | एक **Block** डेरिवेशन को लौटाता है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | **Block** मान की पोस्ट-कम्पाइल व्याख्या को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | तत्व पर बाधाओं के संग्रह को लौटाता है। |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | यदि तत्व की सामग्री सरल प्रकार की है या तत्व की सामग्री **textOnly** है तो तत्व का डिफ़ॉल्ट मान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | एक [XmlSchemaType](../xmlschematype/) ऑब्जेक्ट लौटाता है जो तत्व के प्रकार को दर्शाता है, जो तत्व के [XmlSchemaElement::get_SchemaType](./get_schematype/) या [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) मानों पर आधारित है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | एक ऑब्जेक्ट लौटाता है जो तत्व के [XmlSchemaElement](./) या [XmlSchemaElement](./) पर आधारित है, जिसमें **ElementType** मान की पोस्ट-कम्पाइल व्याख्या होती है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | **Final** मान को लौटाता है यह दर्शाने के लिए कि आगे कोई डेरिवेशन अनुमति नहीं है। |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | **Final** मान की पोस्ट-कम्पाइल व्याख्या को लौटाता है। |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | स्थिर मान को लौटाता है। |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | तत्व के रूप (form) को लौटाता है। |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | string id को लौटाता है। |
| **bool** [get_IsAbstract](./get_isabstract/)() | यह दर्शाने के लिए जानकारी लौटाता है कि क्या तत्व को इंस्टेंस दस्तावेज़ में उपयोग किया जा सकता है। |
| **bool** [get_IsNillable](./get_isnillable/)() | यह दर्शाने वाली जानकारी लौटाता है कि क्या **xsi:nil** इंस्टेंस डेटा में हो सकता है। यह भी दर्शाता है कि क्या तत्व को स्पष्ट निल मान असाइन किया जा सकता है। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उसकी पंक्ति संख्या को लौटाता है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उस फ़ाइल में पंक्ति की स्थिति को लौटाता है। |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | कण (particle) के अधिकतम बार होने की संख्या को लौटाता है। |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। कण के अधिकतम बार होने की संख्या। |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | कण के न्यूनतम बार होने की संख्या को लौटाता है। |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। कण के न्यूनतम बार होने की संख्या। |
| [String](../../system/string/) [get_Name](./get_name/)() | तत्व का नाम लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | दिए गए तत्व का वास्तविक योग्य नाम लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | इस स्कीमा में घोषित (या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य स्कीमा में) तत्व के रेफ़रेंस नाम को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | तत्व का प्रकार लौटाता है। यह या तो कॉम्प्लेक्स टाइप या सरल टाइप हो सकता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | इस स्कीमा या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य स्कीमा में परिभाषित बिल्ट-इन डेटा टाइप का नाम लौटाता है। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | स्कीमा को लोड करने वाली फ़ाइल का स्रोत स्थान लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | उस तत्व का नाम लौटाता है जिसे यह तत्व प्रतिस्थापित कर रहा है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | वर्तमान स्कीमा के टार्गेट नेमस्पेस से संबद्ध न रहने वाले योग्य एट्रीब्यूट्स को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफरेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड की समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल की समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का एक इंस्टेंस है या नहीं। C# 'is' ऑपरेटर की समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड की समानांतर। कस्टम प्रकारों की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को आरंभ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफरेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफरेंस द्वारा वैल्यू टाइप ऑब्जेक्ट की nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफरेंस काउंट को घटाता है। |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** प्रॉपर्टी सेट करता है। |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | एक **Block** डेरिवेशन सेट करता है। |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | यदि तत्व की सामग्री सरल प्रकार की है या तत्व की सामग्री **textOnly** है तो तत्व का डिफ़ॉल्ट मान सेट करता है। |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **Final** मान सेट करता है यह दर्शाने के लिए कि आगे कोई डेरिवेशन अनुमति नहीं है। |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | स्थिर मान सेट करता है। |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | तत्व के रूप (form) को सेट करता है। |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | string id सेट करता है। |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | यह दर्शाने के लिए जानकारी सेट करता है कि क्या तत्व को इंस्टेंस दस्तावेज़ में उपयोग किया जा सकता है। |
| void [set_IsNillable](./set_isnillable/)(**bool**) | **xsi:nil** इंस्टेंस डेटा में हो सकता है या नहीं, यह दर्शाने वाली जानकारी सेट करता है। यह भी दर्शाता है कि क्या तत्व को स्पष्ट निल मान असाइन किया जा सकता है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** तत्व जो फ़ाइल को संदर्भित करता है, उसकी पंक्ति संख्या सेट करता है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** तत्व जो फ़ाइल को संदर्भित करता है, उसकी पंक्ति स्थिति सेट करता है। |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | कण के अधिकतम बार होने की संख्या सेट करता है। |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। कण के अधिकतम बार होने की संख्या। |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | कण के न्यूनतम बार होने की संख्या सेट करता है। |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। कण के न्यूनतम बार होने की संख्या। |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | तत्व का नाम सेट करता है। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | इस स्कीमा में घोषित (या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य स्कीमा में) तत्व के रेफ़रेंस नाम को सेट करता है। |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | तत्व का प्रकार सेट करता है। यह या तो कॉम्प्लेक्स टाइप या सरल टाइप हो सकता है। |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | इस स्कीमा या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य स्कीमा में परिभाषित बिल्ट-इन डेटा टाइप का नाम सेट करता है। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | स्कीमा को लोड करने वाली फ़ाइल का स्रोत स्थान सेट करता है। |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | उस तत्व का नाम सेट करता है जिसे यह तत्व प्रतिस्थापित कर रहा है। |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | वर्तमान स्कीमा के टार्गेट नेमस्पेस से संबद्ध न रहने वाले योग्य एट्रीब्यूट्स को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर सेट करता है (शेर्ड के बजाय)। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफरेंस काउंट को घटाता है और वापस करता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड की समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीरी ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफरेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफरेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaElement](./xmlschemaelement/)() | [XmlSchemaElement](./) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | [XmlSchemaParticle](../xmlschemaparticle/) क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की इंस्टेंस के लिए साझा पॉइंटर का उपनाम है। |

## टिप्पणी



इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही अलोकेट किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम एरर और/या एसेर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग करके फ़ंक्शन्स को आर्ग्यूमेंट के रूप में पास करें। 

## देखें

* क्लास [XmlSchemaParticle](../xmlschemaparticle/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
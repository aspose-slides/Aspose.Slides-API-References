---
title: XmlSchemaGroupRef
second_title: Aspose.Slides for C++ API संदर्भ
description: XML Schema से ref एट्रिब्यूट के साथ group एलिमेंट का प्रतिनिधित्व करता है जैसा कि World Wide Web Consortium (W3C) द्वारा निर्दिष्ट किया गया है। यह क्लास जटिल प्रकारों के भीतर उपयोग की जाती है जो schema स्तर पर परिभाषित एक समूह का संदर्भ देती हैं।
type: docs
weight: 456
url: /hi/system.xml.schema/xmlschemagroupref/
---
## XmlSchemaGroupRef क्लास


Represents the **group** element with **ref** attribute from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). यह क्लास जटिल प्रकारों के भीतर उपयोग की जाती है जो **schema** स्तर पर परिभाषित **group** का संदर्भ देती हैं।

```cpp
class XmlSchemaGroupRef : public System::Xml::Schema::XmlSchemaParticle
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमैंटिक्स का उपयोग करके करती है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करती है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करती है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करती है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिये। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** प्रॉपर्टी लौटाता है। |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | स्ट्रिंग आईडी लौटाता है। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उसमें लाइन नंबर लौटाता है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उसमें लाइन स्थिति लौटाता है। |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | पार्टिकल के अधिकतम बार घटित होने की संख्या लौटाता है। |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। पार्टिकल के अधिकतम बार घटित होने की संख्या। |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | पार्टिकल के न्यूनतम बार घटित होने की संख्या लौटाता है। |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। पार्टिकल के न्यूनतम बार घटित होने की संख्या। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस schema ऑब्जेक्ट के साथ उपयोग करने के लिये XmlSerializerNamespaces लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaGroupBase](../xmlschemagroupbase/)\> [get_Particle](./get_particle/)() | [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) या [XmlSchemaSequence](../xmlschemasequence/) वर्गों में से एक लौटाता है, जो **Particle** मान की पोस्ट-कंपिलेशन व्याख्या रखता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | इस schema में परिभाषित समूह का नाम लौटाता है (या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य schema में)। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | schema को लोड करने वाली फ़ाइल का स्रोत स्थान लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | वर्तमान schema के टार्गेट नेमस्पेस से संबंधित नहीं होने वाले क्वालिफ़ाइड एट्रिब्यूट्स लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का उदाहरण है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाईज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाईज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, बस नया ऑब्जेक्ट इनिशियलाईज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करती है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | रेफ़रेंस द्वारा वैल्यू टाइप ऑब्जेक्ट को nullptr से तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | string और nullptr के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | strings के केस के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा शेयर्ड रेफ़रेंस काउंट घटाता है। |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** प्रॉपर्टी सेट करता है। |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | स्ट्रिंग आईडी सेट करता है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उसमें लाइन नंबर सेट करता है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** तत्व जिस फ़ाइल को संदर्भित करता है, उसमें लाइन स्थिति सेट करता है। |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | पार्टिकल के अधिकतम बार घटित होने की संख्या सेट करता है। |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। पार्टिकल के अधिकतम बार घटित होने की संख्या। |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | पार्टिकल के न्यूनतम बार घटित होने की संख्या सेट करता है। |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। पार्टिकल के न्यूनतम बार घटित होने की संख्या। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस schema ऑब्जेक्ट के साथ उपयोग करने के लिये XmlSerializerNamespaces सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | इस schema में परिभाषित समूह का नाम सेट करता है (या निर्दिष्ट नेमस्पेस द्वारा संकेतित अन्य schema में)। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | schema को लोड करने वाली फ़ाइल के स्रोत स्थान को सेट करता है। |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | वर्तमान schema के टार्गेट नेमस्पेस से संबंधित नहीं होने वाले क्वालिफ़ाइड एट्रिब्यूट्स को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयर्ड नहीं) सेट करता है। कंटेनर्स में पॉइंटरों को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं करना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaGroupRef](./xmlschemagroupref/)() | [XmlSchemaGroupRef](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | [XmlSchemaParticle](../xmlschemaparticle/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के लिये शेयर्ड पॉइंटर का उपनाम। |
## टिप्पणी



इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही एलोकेट किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन्स में आर्ग्यूमेंट के रूप में पास करने के लिये करें। 

## देखें

* क्लास [XmlSchemaParticle](../xmlschemaparticle/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
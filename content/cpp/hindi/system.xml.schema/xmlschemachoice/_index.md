---
title: XmlSchemaChoice
second_title: Aspose.Slides for C++ API संदर्भ
description: XML Schema से कॉम्पोजिटर (choice) तत्व को World Wide Web Consortium (W3C) द्वारा निर्दिष्ट अनुसार प्रस्तुत करता है। choice केवल अपने एक ही चाइल्ड को एक इंस्टेंस में प्रकट होने की अनुमति देता है।
type: docs
weight: 209
url: /hi/system.xml.schema/xmlschemachoice/
---
## XmlSchemaChoice क्लास


Represents the **choice** element (compositor) from the XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). The **choice** allows only one of its children to appear in an instance.

```cpp
class XmlSchemaChoice : public System::Xml::Schema::XmlSchemaGroupBase
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | ऑब्जेक्ट्स की तुलना C# [Object.Equals](../../system/object/equals/) सेमांटिक्स का उपयोग करके करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | रेफरेंस टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | वैल्यू टाइप ऑब्जेक्ट्स की तुलना C# शैली में करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | यह C#-स्टाइल फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | यह C#-स्टाइल फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** प्रॉपर्टी को लौटाता है। |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | स्ट्रिंग आईडी को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() override | कम्पोजिटर (**choice**) के साथ सम्मिलित तत्वों का संग्रह लौटाता है: [XmlSchemaElement](../xmlschemaelement/), [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](./), [XmlSchemaSequence](../xmlschemasequence/) या [XmlSchemaAny](../xmlschemaany/)। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | फ़ाइल में उस लाइन नंबर को लौटाता है जिसे **schema** तत्व संदर्भित करता है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | फ़ाइल में उस लाइन पोजीशन को लौटाता है जिसे **schema** तत्व संदर्भित करता है। |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | कण (particle) के अधिकतम प्रकट होने की संख्या लौटाता है। |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। कण के अधिकतम प्रकट होने की संख्या। |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | कण के न्यूनतम प्रकट होने की संख्या लौटाता है। |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | संख्या को स्ट्रिंग मान के रूप में लौटाता है। कण के न्यूनतम प्रकट होने की संख्या। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस schema ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट लौटाता है। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | schema लोड करने वाली फ़ाइल की स्रोत स्थान को लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | वर्तमान schema के लक्ष्य नेमस्पेस से संबंधित नहीं होने वाले योग्य (qualified) एट्रिब्यूट्स को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफरेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का एक इंस्टेंस दर्शाता है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट को लॉक करने के लिए कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्टिंग को सक्षम बनाता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ के कॉपी कंस्ट्रक्टिंग को सक्षम बनाता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस की तुलना nullptr से करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिए स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिए स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** प्रॉपर्टी सेट करता है। |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | स्ट्रिंग आईडी सेट करता है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | फ़ाइल में उस लाइन नंबर को सेट करता है जिसे **schema** तत्व संदर्भित करता है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | फ़ाइल में उस लाइन पोजीशन को सेट करता है जिसे **schema** तत्व संदर्भित करता है। |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | कण के अधिकतम प्रकट होने की संख्या सेट करता है। |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। कण के अधिकतम प्रकट होने की संख्या। |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | कण के न्यूनतम प्रकट होने की संख्या सेट करता है। |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | संख्या को स्ट्रिंग मान के रूप में सेट करता है। कण के न्यूनतम प्रकट होने की संख्या। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस schema ऑब्जेक्ट के साथ उपयोग करने के लिए XmlSerializerNamespaces सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | schema लोड करने वाली फ़ाइल की स्रोत स्थान सेट करता है। |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | वर्तमान schema के लक्ष्य नेमस्पेस से संबंधित नहीं होने वाले योग्य एट्रिब्यूट्स सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्युमेंट को एक वीक पॉइंटर (शेयर्ड के बजाय) सेट करता है। कंटेनरों में पॉइंटर को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलना सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को कार्यान्वित करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने के लिए कार्यान्वित करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वी्क रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वी्क रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaChoice](./xmlschemachoice/)() | [XmlSchemaChoice](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | [XmlSchemaParticle](../xmlschemaparticle/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडिफ़्स

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के इंस्टेंस के लिए शेयर्ड पॉइंटर का एक एलियास। |
## टिप्पणियाँ



इस क्लास के ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके न बनाएं, क्योंकि इससे रनटाइम एरर और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को तर्क के रूप में फ़ंक्शन्स को पास करने के लिए उपयोग करें। 

## संबंधित देखें

* क्लास [XmlSchemaGroupBase](../xmlschemagroupbase/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
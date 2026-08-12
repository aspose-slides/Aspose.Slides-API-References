---
title: XmlSchemaMaxExclusiveFacet
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: XML Schema से maxExclusive एलिमेंट को दर्शाता है जैसा कि World Wide Web Consortium (W3C) द्वारा निर्दिष्ट किया गया है। इस क्लास का उपयोग simpleType एलिमेंट के अधिकतम मान पर प्रतिबंध निर्दिष्ट करने के लिए किया जा सकता है। एलिमेंट का मान maxExclusive एलिमेंट के मान से कम होना चाहिए।
type: docs
weight: 573
url: /hi/system.xml.schema/xmlschemamaxexclusivefacet/
---
## XmlSchemaMaxExclusiveFacet वर्ग


XML [Schema](../) से **maxExclusive** एलिमेंट को दर्शाता है जैसा कि विश्वव्यापी [Web](../../system.web/) कंसोर्टियम (W3C) द्वारा निर्दिष्ट किया गया है। इस वर्ग का उपयोग **simpleType** एलिमेंट के अधिकतम मान पर प्रतिबंध निर्दिष्ट करने के लिए किया जा सकता है। एलिमेंट का मान **maxExclusive** एलिमेंट के मान से कम होना चाहिए।

```cpp
class XmlSchemaMaxExclusiveFacet : public System::Xml::Schema::XmlSchemaFacet
```

## विधियाँ

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-style फ्लोटिंग पॉइंट तुलना जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के लिए भी। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-style फ्लोटिंग पॉइंट तुलना जहाँ दो NaN को बराबर माना जाता है जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के लिए भी। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक उपयोग के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** गुण को लौटाता है। |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | string id को लौटाता है। |
| virtual **bool** [get_IsFixed](../xmlschemafacet/get_isfixed/)() | इस फैसेट के फ़िक्स्ड होने का संकेत देने वाली जानकारी लौटाता है। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** एलिमेंट के संदर्भित फ़ाइल में पंक्ति संख्या लौटाता है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** एलिमेंट के संदर्भित फ़ाइल में पंक्ति स्थिति लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस schema ऑब्जेक्ट के साथ उपयोग हेतु XmlSerializerNamespaces लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट लौटाता है। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | स्कीमा को लोड करने वाली फ़ाइल का स्रोत स्थान लौटाता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | वर्तमान schema के टार्गेट नेमस्पेस से संबंधित न रहने वाले क्वालिफाइड एट्रिब्यूट्स लौटाता है। |
| [String](../../system/string/) [get_Value](../xmlschemafacet/get_value/)() | **value** एट्रिब्यूट को लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से संबद्ध रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स का हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट की लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का प्रयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स को क्लोन करने में सक्षम बनाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | रेफ़रेंस द्वारा ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | value टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, string और nullptr के केस के लिए। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण, strings के केस के लिए। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को कम करता है। |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** गुण को सेट करता है। |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | string id को सेट करता है। |
| virtual void [set_IsFixed](../xmlschemafacet/set_isfixed/)(**bool**) | इस फैसेट के फ़िक्स्ड होने का संकेत देने वाली जानकारी सेट करता है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** एलिमेंट के संदर्भित फ़ाइल में पंक्ति संख्या सेट करता है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** एलिमेंट के संदर्भित फ़ाइल में पंक्ति स्थिति सेट करता है। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस schema ऑब्जेक्ट के साथ उपयोग हेतु XmlSerializerNamespaces सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | स्कीमा को लोड करने वाली फ़ाइल का स्रोत स्थान सेट करता है। |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | वर्तमान schema के टार्गेट नेमस्पेस से संबंधित न रहने वाले क्वालिफाइड एट्रिब्यूट्स सेट करता है। |
| void [set_Value](../xmlschemafacet/set_value/)(const [String](../../system/string/)\&) | **value** एट्रिब्यूट सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को weak pointer (shared के बजाय) सेट करता है। कंटेनर्स में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) निर्माण को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वैक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वैक रेफ़रेंस काउंट को घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlSchemaFacet](../xmlschemafacet/xmlschemafacet/)() | [XmlSchemaFacet](../xmlschemafacet/) वर्ग की नई इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaMaxExclusiveFacet](./xmlschemamaxexclusivefacet/)() | [XmlSchemaMaxExclusiveFacet](./) वर्ग की नई इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) वर्ग की नई इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़्स

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | इस वर्ग के इंस्टेंस के लिए साझा पॉइंटर का एक उपनाम। |

## टिप्पणियां

इस वर्ग की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके आवंटित किया जाना चाहिए। इस प्रकार की इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन फॉल्ट्स उत्पन्न हो सकते हैं। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्यूमेंट के रूप में पास करने के लिए करें। 

## संबंधित देखें

* वर्ग [XmlSchemaFacet](../xmlschemafacet/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
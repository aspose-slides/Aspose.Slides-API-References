---
title: XmlSchemaMaxLengthFacet
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: World Wide Web Consortium (W3C) द्वारा निर्दिष्ट XML Schema से maxLength तत्व का प्रतिनिधित्व करता है। इस क्लास का उपयोग simpleType तत्व के डेटा मान की अधिकतम लंबाई पर प्रतिबंध निर्धारित करने के लिए किया जा सकता है। लंबाई को maxLength तत्व के मान से कम होना चाहिए।
type: docs
weight: 599
url: /hi/system.xml.schema/xmlschemamaxlengthfacet/
---
## XmlSchemaMaxLengthFacet क्लास


Represents the **maxLength** element from XML [Schema](../) as specified by the World Wide [Web](../../system.web/) Consortium (W3C). This क्लास can be used to specify a restriction on the maximum length of the data value of a **simpleType** element. The length must be less than the value of the **maxLength** element.

```cpp
class XmlSchemaMaxLengthFacet : public System::Xml::Schema::XmlSchemaNumericFacet
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अभिप्रायों का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में संदर्भ प्रकार की वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में मान प्रकार की वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN को समान माना जाता है हालांकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, जिसमें NaN भी शामिल है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** प्रॉपर्टी को वापस करता है। |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | स्ट्रिंग आईडी को वापस करता है। |
| virtual **bool** [get_IsFixed](../xmlschemafacet/get_isfixed/)() | वह जानकारी वापस करता है जो दर्शाती है कि यह फ़ेसेट फिक्स्ड है। |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | वह लाइन नंबर वापस करता है जिसमें **schema** एलिमेंट संदर्भित है। |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | वह लाइन पोजिशन वापस करता है जिसमें **schema** एलिमेंट संदर्भित है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिये XmlSerializerNamespaces को वापस करता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट वापस करता है। |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | स्कीमा को लोड करने वाली फ़ाइल के स्रोत स्थान को वापस करता है। |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | वर्तमान स्कीमा के टार्गेट नेमस्पेस से न जुड़े योग्य एट्रिब्यूट्स को वापस करता है। |
| [String](../../system/string/) [get_Value](../xmlschemafacet/get_value/)() | फ़ेसेट का **value** एट्रिब्यूट वापस करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफ़रेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट के वास्तविक प्रकार को प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समकक्ष। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट लक्ष्य प्रकार द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समकक्ष। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समकक्ष। कस्टम प्रकारों के क्लोनिंग को सक्षम करता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। कुछ नहीं कॉपी करता, बल्कि नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी निर्माण को सक्षम करता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के मामले के लिये [Object::ReferenceEquals](../../system/object/referenceequals/) का विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** प्रॉपर्टी को सेट करता है। |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | स्ट्रिंग आईडी को सेट करता है। |
| virtual void [set_IsFixed](../xmlschemafacet/set_isfixed/)(**bool**) | वह जानकारी सेट करता है जो दर्शाती है कि यह फ़ेसेट फिक्स्ड है। |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | फ़ाइल में वह लाइन नंबर सेट करता है जिसमें **schema** एलिमेंट संदर्भित है। |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | फ़ाइल में वह लाइन पोजिशन सेट करता है जिसमें **schema** एलिमेंट संदर्भित है। |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | इस स्कीमा ऑब्जेक्ट के साथ उपयोग करने के लिये XmlSerializerNamespaces को सेट करता है। |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | इस [XmlSchemaObject](../xmlschemaobject/) का पैरेंट सेट करता है। |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | स्कीमा को लोड करने वाली फ़ाइल के स्रोत स्थान को सेट करता है। |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | वर्तमान स्कीमा के टार्गेट नेमस्पेस से न जुड़े योग्य एट्रिब्यूट्स को सेट करता है। |
| void [set_Value](../xmlschemafacet/set_value/)(const [String](../../system/string/)\&) | फ़ेसेट का **value** एट्रिब्यूट सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n-वें टेम्पलेट आर्ग्यूमेंट को वीक पॉइंटर (शेयरड नहीं) के रूप में सेट करता है। कंटेनर में पॉइंटर को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | वर्तमान साझा रेफ़रेंस काउंटर मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट को घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समकक्ष। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने को सक्षम करता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [XmlSchemaFacet](../xmlschemafacet/xmlschemafacet/)() | [XmlSchemaFacet](../xmlschemafacet/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaMaxLengthFacet](./xmlschemamaxlengthfacet/)() | [XmlSchemaMaxLengthFacet](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडेफ़्स

| टाइपडेफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |
## टिप्पणियाँ



इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का इस्तेमाल करके ही अलोकेट किया जाना चाहिए। इस प्रकार के इंस्टेंस को स्टैक पर या operator new का उपयोग करके कभी न बनाएँ, क्योंकि इससे रन-टाइम एरर और/या असर्शन फ़ॉल्ट्स हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में रैप करें और इस पॉइंटर को फ़ंक्शन्स में तर्क के रूप में पास करें। 

## देखें

* क्लास [XmlSchemaNumericFacet](../xmlschemanumericfacet/)
* नेमस्पेस [System::Xml::Schema](../)
* लाइब्रेरी [Aspose.Slides](../../)
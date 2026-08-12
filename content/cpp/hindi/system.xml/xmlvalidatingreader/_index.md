---
title: XmlValidatingReader
second_title: Aspose.Slides for C++ API संदर्भ
description: एक रीडर को दर्शाता है जो दस्तावेज़ प्रकार परिभाषा (DTD), XML-Data Reduced (XDR) स्कीमा, तथा XML Schema परिभाषा भाषा (XSD) सत्यापन प्रदान करता है।
type: docs
weight: 547
url: /hi/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader क्लास

एक रीडर का प्रतिनिधित्व करता है जो दस्तावेज़ प्रकार परिभाषा (DTD), XML-डेटा रिड्यूस्ड (XDR) स्कीमा, और XML [Schema](../../system.xml.schema/) परिभाषा भाषा (XSD) वैधता प्रदान करता है।

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## विधियाँ
| मेथड | विवरण |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/) को Closed में बदलता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | निर्दिष्ट URI के साथ [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट URI और सेटिंग्स का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट URI, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम को डिफ़ॉल्ट सेटिंग्स के साथ उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रीम, बेस URI और सेटिंग्स का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट स्ट्रीम, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | निर्दिष्ट टेक्स्ट रीडर का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट टेक्स्ट रीडर और सेटिंग्स का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और बेस URI का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | निर्दिष्ट XML रीडर और सेटिंग्स का उपयोग करके [XmlReader](../xmlreader/) का नया इंस्टेंस बनाता है। |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) क्लास के वर्तमान इंस्टेंस द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमैटिक्स का उपयोग करके वस्तुओं की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस टाइप वस्तुओं की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप वस्तुओं की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग पॉइंट तुलना की नकल करता है जहाँ दो NaN को समान माना जाता है, जबकि IEC 60559:1989 के अनुसार NaN किसी भी मान के बराबर नहीं होता, यहाँ तक कि NaN के भी नहीं। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | वर्तमान नोड पर एट्रिब्यूट्स की संख्या लौटाता है। |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | वर्तमान नोड का बेस URI लौटाता है। |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlValidatingReader](./) बाइनरी कंटेंट रीड मेथड्स को लागू करता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/) [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) मेथड को लागू करता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | यह रीडर एंटिटीज़ को पार्स और रिजॉल्व कर सकता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **int32_t** [get_Depth](./get_depth/)() override | XML दस्तावेज़ में वर्तमान नोड की गहराई लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | दस्तावेज़ के लिए एन्कोडिंग एट्रिब्यूट लौटाता है। |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | एक मान लौटाता है जो यह निर्दिष्ट करता है कि रीडर एंटिटीज़ को कैसे संभालता है। |
| **bool** [get_EOF](./get_eof/)() override | रीडर स्ट्रीम के अंत पर स्थित है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | वर्तमान नोड के पास कोई एट्रिब्यूट हैं या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_HasValue](./get_hasvalue/)() override | वर्तमान नोड के पास [String::Empty](../../system/string/empty/) के अलावा [XmlValidatingReader::get_Value](./get_value/) हो सकता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_IsDefault](./get_isdefault/)() override | वर्तमान नोड वह एट्रिब्यूट है जो दस्तावेज़ प्रकार परिभाषा (DTD) या स्कीमा में परिभाषित डिफ़ॉल्ट वैल्यू से उत्पन्न हुआ है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | वर्तमान नोड एक खाली एलिमेंट है (उदाहरण के लिए, **<MyElement/>**) या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | वर्तमान लाइन नंबर लौटाता है। |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | वर्तमान लाइन पोजीशन लौटाता है। |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | वर्तमान नोड का स्थानीय नाम लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | वर्तमान नोड का योग्य (qualified) नाम लौटाता है। |
| **bool** [get_Namespaces](./get_namespaces/)() | नेमस्पेस सपोर्ट करने के बारे में दर्शाने वाला मान लौटाता है। |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | रीडर जिस नोड पर स्थित है, उसका नेमस्पेस यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) (World Wide [Web](../../system.web/) Consortium (W3C) नेमस्पेस स्पेसिफिकेशन के अनुसार) लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | इस इम्प्लीमेंटेशन से जुड़ा [XmlNameTable](../xmlnametable/) लौटाता है। |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | वर्तमान नोड का प्रकार लौटाता है। |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | वर्तमान नोड से जुड़ा नेमस्पेस प्रीफ़िक्स लौटाता है। |
| char16_t [get_QuoteChar](./get_quotechar/)() override | एट्रिब्यूट नोड के मान को घेरने के लिए उपयोग किए जाने वाले उद्धरण चिह्न (quotation mark) को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | इस [XmlValidatingReader](./) को बनाने में उपयोग किए गए [XmlReader](../xmlreader/) को लौटाता है। |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | रीडर की स्थिति लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | स्कीमा वैधता के परिणामस्वरूप वर्तमान नोड को असाइन की गई स्कीमा जानकारी लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | वैलिडेशन के लिए उपयोग करने हेतु एक XmlSchemaCollection लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | एक स्कीमा टाइप ऑब्जेक्ट लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | इस [XmlReader](../xmlreader/) इंस्टेंस को बनाने में उपयोग किए गए [XmlReaderSettings](../xmlreadersettings/) ऑब्जेक्ट को लौटाता है। |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | किए जाने वाले वैलिडेशन के प्रकार को दर्शाने वाला मान लौटाता है। |
| [String](../../system/string/) [get_Value](./get_value/)() override | वर्तमान नोड का टेक्स्ट मान लौटाता है। |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | वर्तमान नोड का प्रकार लौटाता है। |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | वर्तमान **xml:lang** स्कोप लौटाता है। |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | वर्तमान **xml:space** स्कोप लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट स्थानीय नाम और नेमस्पेस यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुक्रम (एनालॉग)। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुक्रम। |
| **bool** [HasLineInfo](./haslineinfo/)() override | क्लास लाइन जानकारी लौटा सकता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | डेराइव्ड क्लास में ओवरराइड करने पर, निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | डेराइव्ड क्लास में ओवरराइड करने पर, निर्दिष्ट [XmlReader::get_Name](../xmlreader/get_name/) मान वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | डेराइव्ड क्लास में ओवरराइड करने पर, निर्दिष्ट [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मानों वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनुक्रम। |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | स्ट्रिंग आर्ग्युमेंट एक वैध XML नाम है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | स्ट्रिंग आर्ग्युमेंट एक वैध XML नाम टोकन है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है या नहीं। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है या नहीं और क्या पाए गए एलिमेंट का [XmlReader::get_Name](../xmlreader/get_name/) मान दिया गया आर्ग्युमेंट के साथ मेल खाता है। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है या नहीं और क्या पाए गए एलिमेंट के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गए स्ट्रिंग्स के साथ मेल खाते हैं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | वर्तमान एलिमेंट की स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुक्रम। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट स्थानीय नाम और नेमस्पेस यूनिफॉर्म रिसोर्स आइडेंटिफायर (URI) वाले एट्रिब्यूट पर जाता है। |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट पर जाता है। |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | जाँचता है कि वर्तमान नोड कंटेंट नोड है (non-white space text, **CDATA**, **Element**, **EndElement**, **EntityReference**, या **EndEntity**)। यदि नोड कंटेंट नोड नहीं है, तो रीडर अगले कंटेंट नोड या फ़ाइल के अंत तक स्किप कर देता है। यह निम्न प्रकार के नोड्स को स्किप करता है: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, या **SignificantWhitespace**। |
| **bool** [MoveToElement](./movetoelement/)() override | वर्तमान एट्रिब्यूट नोड को सम्मिलित करने वाले एलिमेंट पर जाता है। |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | पहले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | अगले एट्रिब्यूट पर जाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कॉन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक

 में कुछ नहीं कॉपी करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेस की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| **bool** [Read](./read/)() override | स्ट्रीम से अगला नोड पढ़ता है। |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | एट्रिब्यूट वैल्यू को एक या अधिक **[Text](../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | निर्दिष्ट टाइप के ऑब्जेक्ट के रूप में कंटेंट पढ़ता है। |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | कंटेंट पढ़ता है और Base64 डिकोडेड बाइनरी बाइट्स लौटाता है। |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | कंटेंट पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है। |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | वर्तमान स्थिति पर पाठ सामग्री को [Boolean](../../system/boolean/) के रूप में पढ़ता है। |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | वर्तमान स्थिति पर पाठ सामग्री को [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | वर्तमान स्थिति पर पाठ सामग्री को [DateTimeOffset](../../system/datetimeoffset/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | वर्तमान स्थिति पर पाठ सामग्री को [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | वर्तमान स्थिति पर पाठ सामग्री को दोहरी-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | वर्तमान स्थिति पर पाठ सामग्री को एकल-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | वर्तमान स्थिति पर पाठ सामग्री को 32-बिट साइन्ड इंटिजर के रूप में पढ़ता है। |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | वर्तमान स्थिति पर पाठ सामग्री को 64-बिट साइन्ड इंटिजर के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | वर्तमान स्थिति पर पाठ सामग्री को [Object](../../system/object/) के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | वर्तमान स्थिति पर पाठ सामग्री को [String](../../system/string/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और Base64 सामग्री को डिकोड करता है। |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और BinHex सामग्री को डिकोड करता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Boolean](../../system/boolean/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Boolean](../../system/boolean/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | वर्तमान तत्व को पढ़ता है और सामग्री को दोहरी-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को दोहरी-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एकल-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एकल-परिशुद्धता वाले फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइन्ड इंटिजर के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइन्ड इंटिजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइन्ड इंटिजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम एवं नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइन्ड इंटिजर के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [String](../../system/string/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, यह जाँचता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [String](../../system/string/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | केवल-पाठ तत्व को पढ़ता है। हालांकि, इसे संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | केवल-पाठ तत्व को पढ़ने से पहले जांचता है कि पाए गए तत्व का [XmlReader::get_Name](../xmlreader/get_name/) मान दिया गया स्ट्रिंग से मेल खाता है। हालांकि, इसे संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | केवल-पाठ तत्व को पढ़ने से पहले जांचता है कि पाए गए तत्व के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं। हालांकि, इसे संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | वर्तमान कंटेंट नोड के एंड टैग होने की जाँच करता है और रीडर को अगले नोड पर ले जाता है। |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | एक व्युत्पन्न वर्ग में ओवरराइड किए जाने पर, सभी कंटेंट, मार्कअप सहित, को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | एक व्युत्पन्न वर्ग में ओवरराइड किए जाने पर, इस नोड और सभी उसके बच्चों का प्रतिनिधित्व करने वाला कंटेंट, मार्कअप सहित, पढ़ता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | वर्तमान नोड के तत्व होने की जाँच करता है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | वर्तमान कंटेंट नोड के दिए गए [XmlReader::get_Name](../xmlreader/get_name/) मान वाले तत्व होने की जाँच करता है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | वर्तमान कंटेंट नोड के दिए गए [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान वाले तत्व होने की जाँच करता है और रीडर को अगले नोड पर ले जाता है। |
| [String](../../system/string/) [ReadString](./readstring/)() override | एक तत्व या पाठ नोड की सामग्री को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | एक नया [XmlReader](../xmlreader/) उदाहरण लौटाता है जिसे वर्तमान नोड और उसके सभी वंशज को पढ़ने के लिए उपयोग किया जा सकता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) को निर्दिष्ट योग्य नाम वाले अगले वंशज तत्व तक ले जाता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले वंशज तत्व तक ले जाता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | जब तक निर्दिष्ट योग्य नाम वाला तत्व न मिल जाए, पढ़ता रहता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | जब तक निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाला तत्व न मिल जाए, पढ़ता रहता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) को निर्दिष्ट योग्य नाम वाले अगले सहोदर तत्व तक ले जाता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) को निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सहोदर तत्व तक ले जाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | निर्दिष्ट XML [Schema](../../system.xml.schema/) डिफ़िनिशन भाषा (XSD) प्रकार के लिए रन-टाइम प्रकार लौटाता है। |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML दस्तावेज़ में एम्बेडेड बड़े टेक्स्ट स्ट्रीम्स को पढ़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना संदर्भ द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना संदर्भ द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | नलपॉइंटर (nullptr) के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस-तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr के केस के लिये विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के केस के लिये विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** नोड्स के लिए एंटीटी रेफ़रेंस को हल करता है। |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | एक मान सेट करता है जो यह निर्दिष्ट करता है कि रीडर एंटीटीज़ को कैसे संभालता है। |
| void [set_Namespaces](./set_namespaces/)(**bool**) | एक मान सेट करता है जो यह दर्शाता है कि नेमस्पेस समर्थन करना है या नहीं। |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | एक मान सेट करता है जो यह दर्शाता है कि कौन सा वैलिडेशन टाइप किया जाना है। |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/) को सेट करता है जिसका उपयोग बाहरी दस्तावेज़ प्रकार परिभाषा (DTD) और स्कीमा लोकेशन रेफ़रेंसेज़ को हल करने के लिये किया जाता है। [XmlResolver](../xmlresolver/) का भी उपयोग XML [Schema](../../system.xml.schema/) डिफ़िनिशन भाषा (XSD) स्कीमा में पाए गए किसी भी इम्पोर्ट या इंक्लूड तत्वों को संभालने के लिये किया जाता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्यूमेंट को एक weak पॉइंटर (साझा के बजाय) सेट करता है। कंटेनर में पॉइंटर को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| virtual void [Skip](../xmlreader/skip/)() | वर्तमान नोड के बच्चों को छोड़ देता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का analogue। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में परिवर्तित करने की सुविधा देता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) संरचना को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | डॉक्युमेंट टाइप डिफिनिशन (DTD), XML-Data Reduced (XDR) स्कीमा, और XML [Schema](../../system.xml.schema/) डिफिनिशन भाषा (XSD) स्कीमा वैलिडेशन त्रुटियों की जानकारी प्राप्त करने के लिए एक इवेंट हैंडलर जोड़ता है। |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | डॉक्युमेंट टाइप डिफिनिशन (DTD), XML-Data Reduced (XDR) स्कीमा, और XML [Schema](../../system.xml.schema/) डिफिनिशन भाषा (XSD) स्कीमा वैलिडेशन त्रुटियों की जानकारी प्राप्त करने के लिए इवेंट हैंडलर हटाता है। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | weak रेफ़रेंस काउंट बढ़ाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | weak रेफ़रेंस काउंट घटाता है। सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर या ThisProtector का उपयोग करें। |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | [XmlReader](../xmlreader/) से प्राप्त कंटेंट को वैलिडेट करने वाले [XmlValidatingReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट मानों के साथ [XmlValidatingReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट मानों के साथ [XmlValidatingReader](./) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के साझा पॉइंटर के लिए एक उपनाम है। |

## टिप्पणियाँ

अप्रचलित
:   यह वर्ग अब अप्रचलित है। वैध XML रीडर बनाने के लिए [XmlReaderSettings](../xmlreadersettings/) वर्ग और [XmlReader::Create](../xmlreader/create/) विधि का उपयोग करने की सलाह दी जाती है।
इस वर्ग की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरणों को स्टैक पर या operator new का उपयोग करके कभी न बनाएं, क्योंकि यह रनटाइम त्रुटियों और/या अभिकथन दोषों का कारण बन सकता है। हमेशा इस वर्ग को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शनों में तर्क के रूप में पास करने के लिए करें। 

## संबंधित देखें

* क्लास [XmlReader](../xmlreader/)
* क्लास [IXmlLineInfo](../ixmllineinfo/)
* क्लास [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)
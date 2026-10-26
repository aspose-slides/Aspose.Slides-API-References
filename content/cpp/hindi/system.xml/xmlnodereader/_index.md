---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API संदर्भ
description: एक रीडर का प्रतिनिधित्व करता है जो XML डेटा को एक XmlNode में तेज़, गैर-कैश्ड, केवल-फ़ॉरवर्ड एक्सेस प्रदान करता है।
type: docs
weight: 365
url: /hi/system.xml/xmlnodereader/
---
## XmlNodeReader क्लास

एक रीडर का प्रतिनिधित्व करता है जो तेज़, गैर-कैश्ड, केवल-आगे की एक्सेस प्रदान करता है XML डेटा तक एक [XmlNode](../xmlnode/) में।

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## विधियाँ

| मेथड | विवरण |
| --- | --- |
| void [Close](./close/)() override | [XmlNodeReader::get_ReadState](./get_readstate/) को [ReadState::Closed](../readstate/) में बदलता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | निर्दिष्ट URI के साथ नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट URI और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट URI, सेटिंग्स, और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम के साथ डिफ़ॉल्ट सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रीम, बेस URI और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट स्ट्रीम, सेटिंग्स, और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | निर्दिष्ट टेक्स्ट रीडर का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट टेक्स्ट रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स, और बेस URI का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स, और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | निर्दिष्ट XML रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) क्लास की वर्तमान इंस्टेंस द्वारा उपयोग किए गए सभी संसाधनों को रिलीज़ करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सेमेंटिक्स का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफ़रेंस प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू प्रकार के ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ़्लोटिंग पॉइंट तुलना का अनुकरण करता है जहाँ दो NaN बराबर माने जाते हैं, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, यहाँ तक कि NaN, के बराबर नहीं है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | वर्तमान नोड पर एट्रिब्यूट्स की संख्या लौटाता है। |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | वर्तमान नोड का बेस URI लौटाता है। |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlNodeReader](./) बाइनरी कंटेंट रीड मेथड्स को लागू करता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/) [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) मेथड को लागू करता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | यह रीडर एंटिटीज़ को पार्स और रेज़ॉल्व कर सकता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **int32_t** [get_Depth](./get_depth/)() override | XML दस्तावेज़ में वर्तमान नोड की गहराई लौटाता है। |
| **bool** [get_EOF](./get_eof/)() override | रीडर स्ट्रीम के अंत में स्थित है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | वर्तमान नोड के पास कोई एट्रिब्यूट है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_HasValue](./get_hasvalue/)() override | वर्तमान नोड के पास [XmlNodeReader::get_Value](./get_value/) मान हो सकता है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_IsDefault](./get_isdefault/)() override | वर्तमान नोड वह एट्रिब्यूट है जो दस्तावेज़ प्रकार परिभाषा (DTD) या स्कीमा में परिभाषित डिफ़ॉल्ट मान से उत्पन्न हुआ है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | वर्तमान नोड एक खाली एलिमेंट है (उदाहरण के लिए, **<MyElement/>**) या नहीं, यह दर्शाने वाला मान लौटाता है। |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | वर्तमान नोड का स्थानीय नाम लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | वर्तमान नोड का योग्य नाम (qualified name) लौटाता है। |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | रीडर जिस नोड पर स्थित है, उसके नेमस्पेस URI (W3C नेमस्पेस विनिर्देशन में परिभाषित) को लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | इस इम्प्लीमेंटेशन से जुड़ा [XmlNameTable](../xmlnametable/) लौटाता है। |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | वर्तमान नोड का प्रकार लौटाता है। |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | वर्तमान नोड से जुड़ा नेमस्पेस प्रीफ़िक्स लौटाता है। |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | डेराइव्ड क्लास में ओवरराइड किए जाने पर, एट्रिब्यूट नोड के मान को घेरने वाले कोटेशन मार्क वर्ण को प्राप्त करता है। |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | रीडर की स्थिति लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | वर्तमान नोड को सौंपा गया स्कीमा जानकारी लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | इस [XmlReader](../xmlreader/) इंस्टेंस को बनाने के लिए उपयोग किए गए [XmlReaderSettings](../xmlreadersettings/) ऑब्जेक्ट को लौटाता है। |
| [String](../../system/string/) [get_Value](./get_value/)() override | वर्तमान नोड का टेक्स्ट मान लौटाता है। |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | वर्तमान नोड का प्रकार लौटाता है। |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | वर्तमान **xml:lang** स्कोप लौटाता है। |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | वर्तमान **xml:space** स्कोप लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स के हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट [XmlReader::get_Name](../xmlreader/get_name/) मान वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | डेराइव्ड क्लास में ओवरराइड किए जाने पर, निर्दिष्ट [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचता है कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | स्ट्रिंग तर्क एक वैध XML नाम है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | स्ट्रिंग तर्क एक वैध XML नाम टोकन है या नहीं, यह दर्शाने वाला मान लौटाता है। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है या नहीं। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है और पाया गया एलिमेंट का [XmlReader::get_Name](../xmlreader/get_name/) मान दिए गए तर्क से मेल खाता है या नहीं। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है और पाया गया एलिमेंट के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गये स्ट्रिंग्स से मेल खाते हैं या नहीं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | वर्तमान एलिमेंट के स्कोप में नेमस्पेस प्रीफ़िक्स को हल करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम प्रकारों की क्लोनिंग को सक्षम करता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एट्रिब्यूट पर जाता है। |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट पर जाता है। |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | जाँचता है कि वर्तमान नोड कंटेंट (गैर-व्हाइटस्पेस टेक्स्ट, **CDATA**, **Element**, **EndElement**, **EntityReference**, या **EndEntity**) नोड है या नहीं। यदि नोड कंटेंट नोड नहीं है, तो रीडर अगले कंटेंट नोड या फ़ाइल के अंत तक आगे बढ़ जाता है। यह निम्न प्रकार के नोड्स को स्किप करता है: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, या **SignificantWhitespace**। |
| **bool** [MoveToElement](./movetoelement/)() override | वर्तमान एट्रिब्यूट नोड को शामिल करने वाले एलिमेंट पर जाता है। |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | पहले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | अगले एट्रिब्यूट पर जाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा संरचनाओं को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ भी कॉपी नहीं करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| **bool** [Read](./read/)() override | स्ट्रीम से अगला नोड पढ़ता है। |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | एट्रिब्यूट मान को एक या अधिक **[Text](../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | निर्दिष्ट प्रकार के ऑब्जेक्ट के रूप में कंटेंट पढ़ता है। |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | कंटेंट पढ़ता है और Base64 डिकोडेड बाइनरी बाइट्स लौटाता है। |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | कंटेंट पढ़ता है और BinHex डिकोडेड बाइनरी बाइट्स लौटाता है। |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को [Boolean](../../system/boolean/) के रूप में पढ़ता है। |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को [DateTimeOffset](../../system/datetimeoffset/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को डबल-प्रिसीजन फ़्लोटिंग-पॉइंट नंबर के रूप में पढ़ता है। |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को सिंगल-प्रिसीजन फ़्लोटिंग पॉइंट नंबर के रूप में पढ़ता है। |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को 32-बिट साइनड इंटेजर के रूप में पढ़ता है। |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को 64-बिट साइनड इंटेजर के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को [Object](../../system/object/) के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [String](../../system/string/) वस्तु के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और Base64 सामग्री को डिकोड करता है। |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और BinHex सामग्री को डिकोड करता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Boolean](../../system/boolean/) वस्तु के रूप में लौटाता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Boolean](../../system/boolean/) वस्तु के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [DateTime](../../system/datetime/) वस्तु के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [DateTime](../../system/datetime/) वस्तु के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Decimal](../../system/decimal/) वस्तु के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Decimal](../../system/decimal/) वस्तु के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | वर्तमान तत्व को पढ़ता है और सामग्री को डबल-प्रिसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को डबल-प्रिसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | वर्तमान तत्व को पढ़ता है और सामग्री को सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को सिंगल-प्रिसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइन्ड इंटेजर के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइन्ड इंटेजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइन्ड इंटेजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइन्ड इंटेजर के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [String](../../system/string/) वस्तु के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व के समान है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [String](../../system/string/) वस्तु के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | केवल पाठ वाला तत्व पढ़ता है। हालांकि, [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करता है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | जाँचता है कि पाए गए तत्व का [XmlReader::get_Name](../xmlreader/get_name/) मान दिए गए स्ट्रिंग से मेल खाता है, फिर केवल पाठ वाला तत्व पढ़ता है। हालांकि, [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करता है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि पाए गए तत्व के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं, फिर केवल पाठ वाला तत्व पढ़ता है। हालांकि, [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करता है। |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | जाँचता है कि वर्तमान कंटेंट नोड एक एंड टैग है और रीडर को अगले नोड पर ले जाता है। |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | एक व्युत्पन्न क्लास में ओवरराइड किए जाने पर, मार्कअप सहित सभी सामग्री को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | एक व्युत्पन्न क्लास में ओवरराइड किए जाने पर, इस नोड और उसके सभी चाइल्ड को दर्शाने वाले मार्कअप सहित सामग्री को पढ़ता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | जाँचता है कि वर्तमान नोड एक एलिमेंट है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_Name](../xmlreader/get_name/) मान वाला एलिमेंट है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान वाला एलिमेंट है और रीडर को अगले नोड पर ले जाता है। |
| [String](../../system/string/) [ReadString](./readstring/)() override | एक एलिमेंट या टेक्स्ट नोड की सामग्री को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | एक नया [XmlReader](../xmlreader/) इंस्टेंस लौटाता है जिसका उपयोग वर्तमान नोड और उसके सभी वंशजों को पढ़ने के लिए किया जा सकता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | निर्दिष्ट क्वालिफाइड नाम वाले अगले वंशज एलिमेंट पर [XmlReader](../xmlreader/) को अग्रसर करता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले वंशज एलिमेंट पर [XmlReader](../xmlreader/) को अग्रसर करता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | जब तक निर्दिष्ट क्वालिफाइड नाम वाला एलिमेंट न मिल जाए, पढ़ता रहता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | जब तक निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाला एलिमेंट न मिल जाए, पढ़ता रहता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | निर्दिष्ट क्वालिफाइड नाम वाले अगले सिब्लिंग एलिमेंट पर [XmlReader](../xmlreader/) को अग्रसर करता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सिब्लिंग एलिमेंट पर [XmlReader](../xmlreader/) को अग्रसर करता है। |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML दस्तावेज़ में एम्बेडेड बड़े टेक्स्ट स्ट्रीम को पढ़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफ़रेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | स्ट्रिंग और nullptr केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | स्ट्रिंग्स के केस के लिए [Object::ReferenceEquals](../../system/object/referenceequals/) का स्पेशलाइज़ेशन। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान से साझा रेफ़रेंस काउंट घटाता है। |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** नोड्स के लिए एंटिटी रेफ़रेंस को हल करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्प्लेट आर्ग्युमेंट को वीक पॉइंटर (शेयर किए हुए के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को वीक मोड में बदलने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | साझा रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | साझा रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | साझा रेफ़रेंस काउंट घटाता है और लौटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Skip](./skip/)() override | वर्तमान नोड के चाइल्ड को स्किप करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समान। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने की अनुमति देता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्सट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट को अनलॉक करने को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट बढ़ाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट घटाता है। इसे सीधे कॉल नहीं किया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | [XmlNodeReader](./) क्लास का एक इंस्टेंस बनाता है निर्दिष्ट [XmlNode](../xmlnode/) का उपयोग करके। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास की एक इंस्टेंस के लिए शेयर किए हुए पॉइंटर का उपनाम। |
## टिप्पणियाँ

इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही अल्लोकट किया जाना चाहिए। इस प्रकार की इंस्टेंसेस को स्टैक पर या ऑपरेटर new का उपयोग करके कभी न बनाएं, क्योंकि इससे रनटाइम त्रुटियाँ और/या असर्शन फॉल्ट हो सकते हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन को आर्ग्युमेंट के रूप में पास करने के लिए करें। 

## संबंधित देखें

* क्लास [XmlReader](../xmlreader/)
* क्लास [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* नेमस्पेस [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)
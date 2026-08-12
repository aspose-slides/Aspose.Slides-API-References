---
title: XmlReader
second_title: Aspose.Slides for C++ API संदर्भ
description: एक रीडर का प्रतिनिधित्व करता है जो तेज़, गैर-कैश्ड, केवल-फ़ॉरवर्ड एक्सेस XML डेटा प्रदान करता है।
type: docs
weight: 430
url: /hi/system.xml/xmlreader/
---
## XmlReader क्लास

XML डेटा तक तेज़, गैर-कैश्ड, केवल-आगे की पहुँच प्रदान करने वाला रीडर दर्शाता है।

```cpp
class XmlReader : public System::IDisposable
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| virtual void [Close](./close/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो [XmlReader::get_ReadState](./get_readstate/) को [ReadState::Closed](../readstate/) में बदल देता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | निर्दिष्ट URI के साथ नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट URI और सेटिंग्स का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट URI, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम को डिफ़ॉल्ट सेटिंग्स के साथ उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रीम, बेस URI और सेटिंग्स का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट स्ट्रीम, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | निर्दिष्ट टेक्स्ट रीडर का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट टेक्स्ट रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और बेस URI का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | निर्दिष्ट XML रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](./) इंस्टेंस बनाता है। |
| void [Dispose](./dispose/)() override | वर्तमान [XmlReader](./) क्लास की इंस्टेंस द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) अर्थविधियों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 के अनुसार NaN किसी मान से समान नहीं होता, यहाँ तक कि NaN से भी नहीं, लेकिन C#-शैली के फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 के अनुसार NaN किसी मान से समान नहीं होता, यहाँ तक कि NaN से भी नहीं, लेकिन C#-शैली के डबल फ्लोटिंग पॉइंट तुलना को अनुकरण करता है जहाँ दो NaN को समान माना जाता है। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजन के लिए। |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड पर एट्रिब्यूट्स की संख्या प्राप्त करता है। |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड का बेस URI प्राप्त करता है। |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | एक मान लौटाता है जो दर्शाता है कि [XmlReader](./) बाइनरी कंटेंट पढ़ने की विधियों को लागू करता है या नहीं। |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | एक मान लौटाता है जो दर्शाता है कि [XmlReader](./) [XmlReader::ReadValueChunk](./readvaluechunk/) विधि को लागू करता है या नहीं। |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | एक मान लौटाता है जो दर्शाता है कि यह रीडर एंटिटी को पार्स और रिजॉल्व कर सकता है या नहीं। |
| virtual **int32_t** [get_Depth](./get_depth/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो XML दस्तावेज़ में वर्तमान नोड की गहराई प्राप्त करता है। |
| virtual **bool** [get_EOF](./get_eof/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो रीडर स्ट्रीम के अंत में स्थित है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड के पास कोई एट्रिब्यूट हैं या नहीं। |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड के पास [XmlReader::get_Value](./get_value/) मान हो सकता है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड DTD या स्कीमा में परिभाषित डिफ़ॉल्ट मान से उत्पन्न एट्रिब्यूट है या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड एक खाली एलिमेंट है (उदाहरण के लिए, **<MyElement/>**) या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड का लोकल नेम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड का क्वालिफाइड नेम प्राप्त करता है। |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो रीडर जिस नोड पर स्थित है, उसका नेमस्पेस URI (W3C नेमस्पेस स्पेसिफिकेशन के अनुसार) प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो इस इम्प्लीमेंटेशन से जुड़ा [XmlNameTable](../xmlnametable/) प्राप्त करता है। |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड का टाइप प्राप्त करता है। |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड से जुड़ा नेमस्पेस प्रीफ़िक्स प्राप्त करता है। |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो एट्रिब्यूट नोड के मान को बंद करने के लिए उपयोग किया जाने वाला कोटेशन मार्क कैरेक्टर प्राप्त करता है। |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो रीडर की स्टेट प्राप्त करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | स्कीमा वैलिडेशन के परिणामस्वरूप वर्तमान नोड को असाइन किया गया स्कीमा सूचना लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | इस [XmlReader](./) इंस्टेंस को बनाने के लिए उपयोग किया गया [XmlReaderSettings](../xmlreadersettings/) ऑब्जेक्ट लौटाता है। |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान नोड का टेक्स्ट वैल्यू प्राप्त करता है। |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | वर्तमान नोड का टाइप लौटाता है। |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान **xml:lang** स्कोप प्राप्त करता है। |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान **xml:space** स्कोप प्राप्त करता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](./get_name/) मान वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मानों वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़े रेफरेंस काउंटर डेटा स्ट्रक्चर को प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का अनुरूप। कस्टम ऑब्जेक्ट्स की हैशिंग को सक्षम करता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक टाइप प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का अनुरूप। |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](./get_name/) मान वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मानों वाले एट्रिब्यूट का वैल्यू प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जाँचता है कि ऑब्जेक्ट targetType द्वारा वर्णित टाइप का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का अनुरूप। |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | एक मान लौटाता है जो दर्शाता है कि स्ट्रिंग आर्ग्यूमेंट एक वैध XML नाम है या नहीं। |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | एक मान लौटाता है जो दर्शाता है कि स्ट्रिंग आर्ग्यूमेंट एक वैध XML नाम टोकन है या नहीं। |
| virtual **bool** [IsStartElement](./isstartelement/)() | [XmlReader::MoveToContent](./movetocontent/) को कॉल करता है और जाँचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है या नहीं। |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/) को कॉल करता है और जाँचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है और क्या पाए गए एलिमेंट का [XmlReader::get_Name](./get_name/) मान दिए गए आर्ग्यूमेंट से मेल खाता है। |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/) को कॉल करता है और जाँचता है कि वर्तमान कंटेंट नोड स्टार्ट टैग या खाली एलिमेंट टैग है और क्या पाए गए एलिमेंट के [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंटीर ऑब्जेक्ट का उपयोग करें। |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान एलिमेंट की स्कोप में नेमस्पेस प्रीफ़िक्स को रिजॉल्व करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का अनुरूप। कस्टम टाइप्स की क्लोनिंग को सक्षम करता है। |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_Name](./get_name/) मान वाले एट्रिब्यूट पर जाता है। |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मानों वाले एट्रिब्यूट पर जाता है। |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो निर्दिष्ट इंडेक्स वाले एट्रिब्यूट पर चलता है। |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | जाँचता है कि वर्तमान नोड कंटेंट नोड है (नॉन-व्हाइटस्पेस टेक्स्ट, **CDATA**, **Element**, **EndElement**, **EntityReference**, या **EndEntity**). यदि नोड कंटेंट नोड नहीं है, तो रीडर अगले कंटेंट नोड या फ़ाइल के अंत तक स्किप करता है। यह निम्न टाइप के नोड्स को स्किप करता है: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, या **SignificantWhitespace**। |
| virtual **bool** [MoveToElement](./movetoelement/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो वर्तमान एट्रिब्यूट नोड को सम्मिलित करने वाले एलिमेंट पर जाता है। |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो पहले एट्रिब्यूट पर जाता है। |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो अगले एट्रिब्यूट पर जाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी इंटरनल डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कंस्ट्रक्टर। वास्तविक में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तविक में कुछ भी कॉपी नहीं करता, सिर्फ नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लासेज़ की कॉपी कंस्ट्रक्शन को सक्षम करता है। |
| virtual **bool** [Read](./read/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो स्ट्रीम से अगला नोड पढ़ता है। |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | जब किसी व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो एट्रिब्यूट वैल्यू को एक या अधिक **[Text](../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | निर्दिष्ट टाइप के ऑब्जेक्ट के रूप में कंटेंट को पढ़ता है। |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | कंटेंट को पढ़ता है और Base64 डिकोडेड बाइनरी बाइट्स लौटाता है। |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | कंटेंट को पढ़ता है और **BinHex** डिकोडेड बाइनरी बाइट्स लौटाता है। |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | वर्तमान स्थिति पर टेक्स्ट कंटेंट को एक [Boolean](../../system/boolean/) के रूप में पढ़ता है। |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [DateTimeOffset](../../system/datetimeoffset/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | वर्तमान स्थिति पर पाठ सामग्री को एक डबल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | वर्तमान स्थिति पर पाठ सामग्री को एक सिंगल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | वर्तमान स्थिति पर पाठ सामग्री को एक 32-बिट साइन्ड इंटीजर के रूप में पढ़ता है। |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | वर्तमान स्थिति पर पाठ सामग्री को एक 64-बिट साइन्ड इंटीजर के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [Object](../../system/object/) के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | वर्तमान स्थिति पर पाठ सामग्री को एक [String](../../system/string/) ऑब्जेक्ट के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | तत्व को पढ़ता है और **Base64** सामग्री को डिकोड करता है। |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | तत्व को पढ़ता है और **BinHex** सामग्री को डिकोड करता है। |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Boolean](../../system/boolean/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Boolean](../../system/boolean/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [DateTime](../../system/datetime/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Decimal](../../system/decimal/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक डबल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक डबल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक सिंगल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक सिंगल-प्रेसिशन फ़्लोटिंग-पॉइंट संख्या के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक 32-बिट साइन्ड इंटीजर के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक 32-बिट साइन्ड इंटीजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक 64-बिट साइन्ड इंटीजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक 64-बिट साइन्ड इंटीजर के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | वर्तमान तत्व को पढ़ता है और सामग्री को एक [String](../../system/string/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को एक [String](../../system/string/) ऑब्जेक्ट के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | केवल-पाठ तत्व को पढ़ता है। हालांकि, इस ऑपरेशन को संभालने के लिए [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह अधिक सीधा तरीका प्रदान करता है। |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | जाँचता है कि найденный элемент की [XmlReader::get_Name](./get_name/) मान दिए गए स्ट्रिंग से मेल खाती है, फिर केवल-पाठ तत्व को पढ़ता है। हालांकि, इस ऑपरेशन को संभालने के लिए [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह अधिक सीधा तरीका प्रदान करता है। |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि найденный элемент की [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मान दिए गए स्ट्रिंग से मेल खाते हैं, फिर केवल-पाठ तत्व को पढ़ता है। हालांकि, इस ऑपरेशन को संभालने के लिए [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह अधिक सीधा तरीका प्रदान करता है। |
| virtual void [ReadEndElement](./readendelement/)() | जाँचता है कि वर्तमान कंटेंट नोड एक एंड टैग है और रीडर को अगले नोड तक ले जाता है। |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो सभी सामग्री, जिसमें मार्कअप शामिल है, को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो इस नोड और इसकी सभी चाइल्ड को दर्शाते हुए सामग्री, जिसमें मार्कअप शामिल है, को पढ़ता है। |
| virtual void [ReadStartElement](./readstartelement/)() | जाँचता है कि वर्तमान नोड एक तत्व है और रीडर को अगले नोड तक ले जाता है। |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_Name](./get_name/) मान वाला तत्व है और रीडर को अगले नोड तक ले जाता है। |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_LocalName](./get_localname/) और [XmlReader::get_NamespaceURI](./get_namespaceuri/) मान वाला तत्व है और रीडर को अगले नोड तक ले जाता है। |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो तत्व या टेक्स्ट नोड की सामग्री को स्ट्रिंग के रूप में पढ़ता है। हालांकि, इस ऑपरेशन को संभालने के लिए [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) मेथड का उपयोग करने की सलाह दी जाती है, क्योंकि यह अधिक सीधा तरीका प्रदान करता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | एक नया [XmlReader](./) इंस्टेंस लौटाता है जिसे वर्तमान नोड और उसके सभी उतरावों को पढ़ने के लिए उपयोग किया जा सकता है। |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | निर्दिष्ट योग्य नाम वाले अगले उतराव तत्व तक [XmlReader](./) को ले जाता है। |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले उतराव तत्व तक [XmlReader](./) को ले जाता है। |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | निर्दिष्ट योग्य नाम वाले तत्व को मिलने तक पढ़ता है। |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले तत्व को मिलने तक पढ़ता है। |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | निर्दिष्ट योग्य नाम वाले अगले सिब्लिंग तत्व तक [XmlReader](./) को ले जाता है। |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सिब्लिंग तत्व तक [XmlReader](./) को ले जाता है। |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | एक XML दस्तावेज़ में एम्बेडेड बड़े टेक्स्ट स्ट्रीम को पढ़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की तुलना रेफरेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की तुलना रेफरेंस द्वारा करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | निलपॉइंट के साथ वैल्यू टाइप ऑब्जेक्ट की रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और निलपॉइंट केस के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स केस के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्धारित मान द्वारा शेयरड रेफरेंस काउंट को घटाता है। |
| virtual void [ResolveEntity](./resolveentity/)() | जब व्युत्पन्न क्लास में ओवरराइड किया जाता है, तो **EntityReference** नोड्स के लिए एंटिटी रेफ़रेंस को हल करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th टेम्पलेट आर्ग्यूमेंट को एक weak पॉइंटर (शेयरड के बजाय) सेट करता है। कंटेनर में पॉइंटर्स को वीक मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयरड रेफरेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयरड रेफरेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयरड रेफरेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual void [Skip](./skip/)() | वर्तमान नोड के चाइल्ड्स को स्किप करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कॉन्स्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट का अनलॉक लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफरेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफरेंस काउंट को घटाता है। इसे सीधे नहीं बुलाया जाना चाहिए; इसके बजाय स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा स्ट्रक्चर को मुक्त करता है। |

## टाइपडिफ़

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के इंस्टेंस के लिए शेयरड पॉइंटर का एक एलियास। |

## देखें

* क्लास [IDisposable](../../system/idisposable/)
* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)
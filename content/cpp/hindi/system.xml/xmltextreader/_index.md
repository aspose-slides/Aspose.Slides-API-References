---
title: XmlTextReader
second_title: Aspose.Slides for C++ API संदर्भ
description: एक रीडर को दर्शाता है जो XML डेटा तक तेज़, गैर-कैश्ड, केवल-फ़ॉरवर्ड एक्सेस प्रदान करता है।
type: docs
weight: 508
url: /hi/system.xml/xmltextreader/
---
## XmlTextReader क्लास

Represents a reader that provides fast, non-cached, forward-only access to XML data.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## मेथड्स

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/) को **Closed** में बदलता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | निर्दिष्ट URI के साथ नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट URI और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट URI, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | निर्दिष्ट स्ट्रीम को डिफॉल्ट सेटिंग्स के साथ उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट स्ट्रीम और सेटिंग्स के साथ नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट स्ट्रीम, बेस URI और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट स्ट्रीम, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | निर्दिष्ट टेक्स्ट रीडर का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | निर्दिष्ट टेक्स्ट रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और बेस URI का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | निर्दिष्ट टेक्स्ट रीडर, सेटिंग्स और पार्सिंग के लिए संदर्भ जानकारी का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | निर्दिष्ट XML रीडर और सेटिंग्स का उपयोग करके नया [XmlReader](../xmlreader/) इंस्टेंस बनाता है। |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) क्लास के वर्तमान इंस्टेंस द्वारा उपयोग किए गए सभी संसाधनों को मुक्त करता है। |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) सिद्धांतों का उपयोग करके ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में रेफरेंस टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# शैली में वैल्यू टाइप ऑब्जेक्ट्स की तुलना करता है। |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C#-शैली के फ्लोटिंग प्वाइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C#-शैली के फ्लोटिंग प्वाइंट तुलना का अनुकरण करता है जहाँ दो NaN को बराबर माना जाता है, भले ही IEC 60559:1989 के अनुसार NaN किसी भी मान, जिसमें NaN भी शामिल है, के बराबर नहीं होता। |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | केवल आंतरिक प्रयोजनों के लिए। |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | वर्तमान नोड पर गुणों की संख्या लौटाता है। |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | वर्तमान नोड का बेस URI लौटाता है। |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | एक मान लौटाता है जो दर्शाता है कि [XmlTextReader](./) बाइनरी कंटेंट रीड मेथड्स को लागू करता है या नहीं। |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | एक मान लौटाता है जो दर्शाता है कि [XmlTextReader](./) [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) मेथड को लागू करता है या नहीं। |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | एक मान लौटाता है जो दर्शाता है कि यह रीडर एंटिटीज़ को पार्स और रिज़ॉल्व कर सकता है या नहीं। |
| **int32_t** [get_Depth](./get_depth/)() override | XML दस्तावेज़ में वर्तमान नोड की गहराई लौटाता है। |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | DtdProcessing एन्यूमेरेशन लौटाता है। |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | दस्तावेज़ की एन्कोडिंग लौटाता है। |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | एक मान लौटाता है जो निर्दिष्ट करता है कि रीडर एंटिटीज़ को कैसे संभालता है। |
| **bool** [get_EOF](./get_eof/)() override | एक मान लौटाता है जो दर्शाता है कि रीडर स्ट्रीम के अंत में स्थित है या नहीं। |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड में कोई गुण हैं या नहीं। |
| **bool** [get_HasValue](./get_hasvalue/)() override | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड के पास [XmlTextReader::get_Value](./get_value/) हो सकता है, जो [String::Empty](../../system/string/empty/) नहीं है। |
| **bool** [get_IsDefault](./get_isdefault/)() override | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड वह एट्रिब्यूट है जो DTD या स्कीमा में परिभाषित डिफॉल्ट मान से उत्पन्न हुआ है। |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | एक मान लौटाता है जो दर्शाता है कि वर्तमान नोड एक खाली एलिमेंट है (उदाहरण के लिए, **<MyElement/>**)। |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | वर्तमान पंक्ति संख्या लौटाता है। |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | वर्तमान पंक्ति स्थिति लौटाता है। |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | वर्तमान नोड का लोकल नाम लौटाता है। |
| [String](../../system/string/) [get_Name](./get_name/)() override | वर्तमान नोड का क्वालीफाइड नाम लौटाता है। |
| **bool** [get_Namespaces](./get_namespaces/)() | एक मान लौटाता है जो नामस्थान समर्थन करने के बारे में दर्शाने वाला मान लौटाता है। |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | जेपीएससी नामस्थान विनिर्देशन में परिभाषित अनुसार, उस नोड का नामस्थान URI लौटाता है जिस पर रीडर स्थित है। |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | इस इम्प्लीमेंटेशन से जुड़ा हुआ [XmlNameTable](../xmlnametable/) लौटाता है। |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | वर्तमान नोड का प्रकार लौटाता है। |
| **bool** [get_Normalization](./get_normalization/)() | एक मान लौटाता है जो दर्शाता है कि व्हाइट स्पेस और एट्रिब्यूट मानों को सामान्यीकृत किया जाना चाहिए या नहीं। |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | वर्तमान नोड से जुड़ा नामस्थान प्रीफ़िक्स लौटाता है। |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | एक मान लौटाता है जो दर्शाता है कि DTD प्रोसेसिंग की अनुमति है या नहीं। |
| char16_t [get_QuoteChar](./get_quotechar/)() override | एट्रिब्यूट नोड के मान को घेरने के लिए उपयोग किए जाने वाले उद्धरण चिह्न अक्षर को लौटाता है। |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | रीडर की स्थिति लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | स्कीमा वैलीडेशन के परिणामस्वरूप वर्तमान नोड को असाइन किए गए स्कीमा जानकारी को लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | इस [XmlReader](../xmlreader/) इंस्टेंस को बनाने के लिए उपयोग किया गया [XmlReaderSettings](../xmlreadersettings/) ऑब्जेक्ट लौटाता है। |
| [String](../../system/string/) [get_Value](./get_value/)() override | वर्तमान नोड का टेक्स्ट मान लौटाता है। |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | वर्तमान नोड के लिए प्रकार लौटाता है। |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | एक मान लौटाता है जो निर्दिष्ट करता है कि व्हाइट स्पेस कैसे संभाला जाता है। |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | वर्तमान **xml:lang** स्कोप लौटाता है। |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | वर्तमान **xml:space** स्कोप लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट लोकल नाम और नामस्थान URI वाले एट्रिब्यूट का मान लौटाता है। |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान लौटाता है। |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ऑब्जेक्ट से जुड़ी रेफ़रेंस काउंटर डेटा स्ट्रक्चर प्राप्त करता है। |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स की हैशिंग सक्षम करता है। |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | एक संग्रह लौटाता है जिसमें वर्तमान में इन-स्कोप सभी नामस्थानों को शामिल किया गया है। |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | बफ़र किए गए XML का शेष भाग लौटाता है। |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ऑब्जेक्ट का वास्तविक प्रकार प्राप्त करता है। C# [System.Object.GetType()](../../system/object/gettype/) कॉल का समानांतर। |
| **bool** [HasLineInfo](./haslineinfo/)() override | एक मान लौटाता है जो दर्शाता है कि क्लास लाइन जानकारी लौटाने में सक्षम है या नहीं। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | एक व्युत्पन्न क्लास में ओवरराइड होने पर, निर्दिष्ट इंडेक्स वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | एक व्युत्पन्न क्लास में ओवरराइड होने पर, निर्दिष्ट [XmlReader::get_Name](../xmlreader/get_name/) मान वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | एक व्युत्पन्न क्लास में ओवरराइड होने पर, निर्दिष्ट [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मानों वाले एट्रिब्यूट का मान प्राप्त करता है। |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | जांचें कि ऑब्जेक्ट targetType द्वारा वर्णित प्रकार का इंस्टेंस है या नहीं। C# 'is' ऑपरेटर का समानांतर। |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | एक मान लौटाता है जो दर्शाता है कि स्ट्रिंग तर्क एक वैध XML नाम है या नहीं। |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | एक मान लौटाता है जो दर्शाता है कि स्ट्रिंग तर्क एक वैध XML नाम टोकन है या नहीं। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड एक स्टार्ट टैग है या खाली एलिमेंट टैग। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड एक स्टार्ट टैग है या खाली एलिमेंट टैग और क्या पाए गए एलिमेंट का [XmlReader::get_Name](../xmlreader/get_name/) मान दिए गए तर्क से मेल खाता है। |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/) को कॉल करता है और जांचता है कि वर्तमान कंटेंट नोड एक स्टार्ट टैग है या खाली एलिमेंट टैग और क्या पाए गए एलिमेंट के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं। |
| void [Lock](../../system/object/lock/)() | C# lock() स्टेटमेंट लॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | वर्तमान एलिमेंट के स्कोप में नामस्थान प्रीफ़िक्स को हल करता है। |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) मेथड का समानांतर। कस्टम टाइप्स की क्लोनिंग सक्षम करता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | निर्दिष्ट नाम वाले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | निर्दिष्ट लोकल नाम और नामस्थान URI वाले एट्रिब्यूट पर जाता है। |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | निर्दिष्ट इंडेक्स वाले एट्रिब्यूट पर जाता है। |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | जांचता है कि वर्तमान नोड एक कंटेंट (नॉन-व्हाइटस्पेस टेक्स्ट, **CDATA**, **Element**, **EndElement**, **EntityReference**, या **EndEntity**) नोड है या नहीं। यदि नोड कंटेंट नोड नहीं है, तो रीडर अगले कंटेंट नोड या फाइल के अंत तक स्किप करता है। यह निम्नलिखित प्रकार के नोड्स को स्किप करता है: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, या **SignificantWhitespace**। |
| **bool** [MoveToElement](./movetoelement/)() override | वर्तमान एट्रिब्यूट नोड को समेटे हुए एलिमेंट पर जाता है। |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | पहले एट्रिब्यूट पर जाता है। |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | अगले एट्रिब्यूट पर जाता है। |
|  [Object](../../system/object/object/)() | ऑब्जेक्ट बनाता है। सभी आंतरिक डेटा स्ट्रक्चर को इनिशियलाइज़ करता है। |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | कॉपी कन्स्ट्रक्टर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | असाइनमेंट ऑपरेटर। वास्तव में कुछ नहीं कॉपी करता, केवल नया ऑब्जेक्ट इनिशियलाइज़ करता है और सबक्लास की कॉपी कन्स्ट्रक्शन को सक्षम करता है। |
| **bool** [Read](./read/)() override | स्ट्रीम से अगला नोड पढ़ता है। |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | एट्रिब्यूट मान को एक या अधिक **[Text](../../system.text/)**, **EntityReference**, या **EndEntity** नोड्स में पार्स करता है। |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Base64 डिकोड करता है और डिकोड किए गए बाइनरी बाइट्स लौटाता है। |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | **BinHex** डिकोड करता है और डिकोड किए गए बाइनरी बाइट्स लौटाता है। |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | एक तत्व की पाठ सामग्री को एक वर्ण बफ़र में पढ़ता है। यह विधि क्रमवार कॉल करके एम्बेडेड पाठ के बड़े प्रवाह को पढ़ने के लिए डिज़ाइन की गई है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | सामग्री को निर्दिष्ट प्रकार की वस्तु के रूप में पढ़ता है। |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | सामग्री को पढ़ता है और **Base64** डीकोड किए गए बाइनरी बाइट्स लौटाता है। |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | सामग्री को पढ़ता है और **BinHex** डीकोड किए गए बाइनरी बाइट्स लौटाता है। |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | वर्तमान स्थिति पर पाठ सामग्री को [Boolean](../../system/boolean/) के रूप में पढ़ता है। |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | वर्तमान स्थिति पर पाठ सामग्री को [DateTime](../../system/datetime/) वस्तु के रूप में पढ़ता है। |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | वर्तमान स्थिति पर पाठ सामग्री को [DateTimeOffset](../../system/datetimeoffset/) वस्तु के रूप में पढ़ता है। |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | वर्तमान स्थिति पर पाठ सामग्री को [Decimal](../../system/decimal/) वस्तु के रूप में पढ़ता है। |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | वर्तमान स्थिति पर पाठ सामग्री को डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | वर्तमान स्थिति पर पाठ सामग्री को सिंगल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में पढ़ता है। |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | वर्तमान स्थिति पर पाठ सामग्री को 32-बिट साइनड इंटीजर के रूप में पढ़ता है। |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | वर्तमान स्थिति पर पाठ सामग्री को 64-बिट साइनड इंटीजर के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | वर्तमान स्थिति पर पाठ सामग्री को [Object](../../system/object/) के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | वर्तमान स्थिति पर पाठ सामग्री को [String](../../system/string/) वस्तु के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर तत्व सामग्री को अनुरोधित प्रकार के रूप में पढ़ता है। |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और Base64 सामग्री को डीकोड करता है। |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | तत्व को पढ़ता है और **BinHex** सामग्री को डीकोड करता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Boolean](../../system/boolean/) वस्तु के रूप में लौटाता है। |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Boolean](../../system/boolean/) वस्तु के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [DateTime](../../system/datetime/) वस्तु के रूप में लौटाता है। |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [DateTime](../../system/datetime/) वस्तु के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Decimal](../../system/decimal/) वस्तु के रूप में लौटाता है। |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Decimal](../../system/decimal/) वस्तु के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | वर्तमान तत्व को पढ़ता है और सामग्री को डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को डबल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | वर्तमान तत्व को पढ़ता है और सामग्री को सिंगल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को सिंगल-प्रेसिशन फ्लोटिंग पॉइंट संख्या के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइनड इंटीजर के रूप में लौटाता है। |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 32-बिट साइनड इंटीजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइनड इंटीजर के रूप में लौटाता है। |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को 64-बिट साइनड इंटीजर के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [Object](../../system/object/) के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | वर्तमान तत्व को पढ़ता है और सामग्री को [String](../../system/string/) वस्तु के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वर्तमान तत्व से मेल खाता है, फिर वर्तमान तत्व को पढ़ता है और सामग्री को [String](../../system/string/) वस्तु के रूप में लौटाता है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | केवल-पाठ तत्व को पढ़ता है। हालांकि, इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | केवल-पाठ तत्व को पढ़ने से पहले जाँचता है कि पाए गए तत्व का [XmlReader::get_Name](../xmlreader/get_name/) मान दिए गए स्ट्रिंग से मेल खाता है। हालांकि, इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | केवल-पाठ तत्व को पढ़ने से पहले जाँचता है कि पाए गए तत्व के [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान दिए गए स्ट्रिंग्स से मेल खाते हैं। हालांकि, इस ऑपरेशन को संभालने का अधिक सरल तरीका प्रदान करने के कारण [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) विधि का उपयोग करने की सलाह दी जाती है। |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | जाँचता है कि वर्तमान कंटेंट नोड एक एंड टैग है और रीडर को अगले नोड पर ले जाता है। |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | डेराइव्ड क्लास में ओवरराइड करने पर, सभी कंटेंट, मार्कअप सहित, को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | डेराइव्ड क्लास में ओवरराइड करने पर, इस नोड और इसके सभी चाइल्ड को दर्शाते हुए कंटेंट, मार्कअप सहित, को पढ़ता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | जाँचता है कि वर्तमान नोड एक एलेमेंट है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_Name](../xmlreader/get_name/) मान वाला एलेमेंट है और रीडर को अगले नोड पर ले जाता है। |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | जाँचता है कि वर्तमान कंटेंट नोड दिया गया [XmlReader::get_LocalName](../xmlreader/get_localname/) और [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) मान वाला एलेमेंट है और रीडर को अगले नोड पर ले जाता है। |
| [String](../../system/string/) [ReadString](./readstring/)() override | एक एलेमेंट या टेक्स्ट नोड की सामग्री को स्ट्रिंग के रूप में पढ़ता है। |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | एक नया [XmlReader](../xmlreader/) इंस्टेंस लौटाता है जिसका उपयोग वर्तमान नोड और उसकी सभी डीसेंडेंट को पढ़ने के लिए किया जा सकता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | निर्दिष्ट क्वालिफाइड नाम वाले अगले डीसेंडेंट एलेमेंट पर [XmlReader](../xmlreader/) को आगे बढ़ाता है। |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले डीसेंडेंट एलेमेंट पर [XmlReader](../xmlreader/) को आगे बढ़ाता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | निर्दिष्ट क्वालिफाइड नाम वाले एलेमेंट मिलने तक पढ़ता रहता है। |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले एलेमेंट मिलने तक पढ़ता रहता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | निर्दिष्ट क्वालिफाइड नाम वाले अगले सिब्लिंग एलेमेंट पर [XmlReader](../xmlreader/) को आगे बढ़ाता है। |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | निर्दिष्ट स्थानीय नाम और नेमस्पेस URI वाले अगले सिब्लिंग एलेमेंट पर [XmlReader](../xmlreader/) को आगे बढ़ाता है। |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | एक XML दस्तावेज़ में एम्बेडेड बड़े पाठ प्रवाह को पढ़ता है। |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | ऑब्जेक्ट्स की रेफ़रेंस द्वारा तुलना करता है। |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | वैल्यू टाइप ऑब्जेक्ट की nullptr के साथ रेफ़रेंस तुलना करता है। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग और nullptr मामलों के लिए विशेषीकरण। |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) का स्ट्रिंग्स के मामलों के लिए विशेषीकरण। |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | निर्दिष्ट मान द्वारा साझा रेफ़रेंस काउंट को घटाता है। |
| void [ResetState](./resetstate/)() | रीडर की स्थिति को [ReadState::Initial](../readstate/) पर रीसेट करता है। |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** नोड्स के लिए एंटिटी रेफ़रेंस को हल करता है। |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | DtdProcessing एन्यूमरेशन को सेट करता है। |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | एक मान सेट करता है जो दर्शाता है कि रीडर एंटिटीज़ को कैसे संभालता है। |
| void [set_Namespaces](./set_namespaces/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि नेमस्पेस समर्थन किया जाए या नहीं। |
| void [set_Normalization](./set_normalization/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि व्हाइट स्पेस और एट्रिब्यूट वैल्यू को नॉर्मलाइज़ किया जाए या नहीं। |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | एक मान सेट करता है जो दर्शाता है कि DTD प्रोसेसिंग की अनुमति दी जाए या नहीं। |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | एक मान सेट करता है जो दर्शाता है कि व्हाइट स्पेस को कैसे हैंडल किया जाए। |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | DTD रेफ़रेंस को हल करने के लिए उपयोग किए जाने वाले [XmlResolver](../xmlresolver/) को सेट करता है। |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | nth टेम्प्लेट आर्ग्युमेंट को weak पॉइंटर (shared के बजाय) सेट करता है। कंटेनरों में पॉइंटर्स को weak मोड में स्विच करने की अनुमति देता है। |
| int [SharedCount](../../system/object/sharedcount/)() const | शेयर्ड रेफ़रेंस काउंटर का वर्तमान मान प्राप्त करता है। |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | शेयर्ड रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | शेयर्ड रेफ़रेंस काउंट को घटाता है और लौटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [Skip](./skip/)() override | वर्तमान नोड के चाइल्ड को स्किप करता है। |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) मेथड का समानांतर। कस्टम ऑब्जेक्ट्स को स्ट्रिंग में बदलने में सक्षम बनाता है। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) कंस्ट्रक्ट को लागू करता है। |
| void [Unlock](../../system/object/unlock/)() | C# lock() स्टेटमेंट की अनलॉकिंग को लागू करता है। सीधे कॉल करें या [LockContext](../../system/lockcontext/) सेंट्री ऑब्जेक्ट का उपयोग करें। |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | वीक रेफ़रेंस काउंट को बढ़ाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | वीक रेफ़रेंस काउंट को घटाता है। इसे सीधे नहीं बुलाना चाहिए; इसके बजाय, स्मार्ट पॉइंटर्स या ThisProtector का उपयोग करें। |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | [XmlTextReader](./) क्लास का नया इंस्टेंस निर्दिष्ट स्ट्रीम के साथ इनिशियलाइज़ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | [XmlTextReader](./) क्लास का नया इंस्टेंस निर्दिष्ट URL और स्ट्रीम के साथ इनिशियलाइज़ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlTextReader](./) क्लास का नया इंस्टेंस निर्दिष्ट स्ट्रीम और [XmlNameTable](../xmlnametable/) के साथ इनिशियलाइज़ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlTextReader](./) क्लास का नया इंस्टेंस निर्दिष्ट URL, स्ट्रीम और [XmlNameTable](../xmlnametable/) के साथ इनिशियलाइज़ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट TextReader के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट URL और TextReader के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट TextReader और [XmlNameTable](../xmlnametable/) के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट URL, TextReader और [XmlNameTable](../xmlnametable/) के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट stream, XmlNodeType और [XmlParserContext](../xmlparsercontext/) के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट string, XmlNodeType और [XmlParserContext](../xmlparsercontext/) के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट फ़ाइल के साथ आरंभ करता है। |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | [XmlTextReader](./) क्लास का नया उदाहरण निर्दिष्ट फ़ाइल और [XmlNameTable](../xmlnametable/) के साथ आरंभ करता है। |
| virtual  [~Object](../../system/object/~object/)() | ऑब्जेक्ट को नष्ट करता है। सभी आंतरिक डेटा संरचनाओं को मुक्त करता है। |
## टाइपडिफ़

| टाइपडिफ़ | विवरण |
| --- | --- |
| [Ptr](./ptr/) | इस क्लास के एक इंस्टेंस के लिए साझा पॉइंटर का उपनाम। |
## टिप्पणियाँ



यह अनुशंसा की जाती है कि इसके बजाय [XmlReader](../xmlreader/) क्लास का उपयोग करें। 

इस क्लास की वस्तुओं को केवल [System::MakeObject()](../../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। इस प्रकार के उदाहरणों को स्टैक पर या operator new का उपयोग करके कभी न बनायें, क्योंकि इससे रनटाइम त्रुटियाँ और/या एसेर्शन त्रुटियाँ हो सकती हैं। हमेशा इस क्लास को [System::SmartPtr](../../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग फ़ंक्शन में आर्गुमेंट के रूप में पास करने के लिये करें। 

## संबंधित देखें

* क्लास [XmlReader](../xmlreader/)
* क्लास [IXmlLineInfo](../ixmllineinfo/)
* क्लास [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* नामस्थान [System::Xml](../)
* लाइब्रेरी [Aspose.Slides](../../)
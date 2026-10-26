---
title: XmlValidatingReader
second_title: Aspose.Slides için C++ API Referansı
description: Belge tipi tanımı (DTD), XML-Data Reduced (XDR) şeması ve XML Şema tanım dili (XSD) doğrulaması sağlayan bir okuyucuyu temsil eder.
type: docs
weight: 547
url: /tr/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader sınıf

Belirli bir belge türü tanımı (DTD), XML-Data Reduced (XDR) şeması ve XML [Schema](../../system.xml.schema/) tanım dili (XSD) doğrulaması sağlayan bir okuyucuyu temsil eder.

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/) öğesini Kapalı'ya değiştirir. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Belirtilen URI ile yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen URI, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akışı varsayılan ayarlarla kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen akış ve ayarlarla yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen akış, temel URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen akış, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen metin okuyucusunu kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen metin okuyucusu ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen metin okuyucusu, ayarlar ve temel URI'yi kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen metin okuyucusu, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Belirtilen XML okuyucusu ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) sınıfının mevcut örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Geçerli düğümdeki öznitelik sayısını döndürür. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Geçerli düğümün temel URI'sini döndürür. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlValidatingReader](./)'ın ikili içerik okuma yöntemlerini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/)'in [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) yöntemini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Bu okuyucunun varlıkları ayrıştırıp çözümleyip çözemeyeceğini gösteren bir değer döndürür. |
| **int32_t** [get_Depth](./get_depth/)() override | XML belgesindeki geçerli düğümün derinliğini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Belge için kodlama özniteliğini döndürür. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Okuyucunun varlıkları nasıl işleyeceğini belirten bir değer döndürür. |
| **bool** [get_EOF](./get_eof/)() override | Okuyucunun akışın sonuna konumlandırılıp konumlandırılmadığını gösteren bir değer döndürür. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Geçerli düğümün herhangi bir özniteliği olup olmadığını gösteren bir değer döndürür. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Geçerli düğümün [String::Empty](../../system/string/empty/) dışındaki bir [XmlValidatingReader::get_Value](./get_value/) sahip olup olamayacağını gösteren bir değer döndürür. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Geçerli düğümün belge türü tanımında (DTD) veya şemada tanımlı varsayılan değerden oluşturulan bir öznitelik olup olmadığını gösteren bir değer döndürür. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Geçerli düğümün boş bir öğe olup olmadığını (örneğin **<MyElement/>**) gösteren bir değer döndürür. |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Geçerli satır numarasını döndürür. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Geçerli satır konumunu döndürür. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Geçerli düğümün yerel adını döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Geçerli düğümün nitelikli adını döndürür. |
| **bool** [get_Namespaces](./get_namespaces/)() | Ad alanı desteği yapılması gerektiğini gösteren bir değer döndürür. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Okuyucunun konumlandığı düğümün ad alanı Birleşik Kaynak Tanımlayıcısını (URI) (Dünya Çapında [Web](../../system.web/) Konsorsiyumu (W3C) Ad Alanı spesifikasyonunda tanımlandığı gibi) döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Bu uygulama ile ilişkili [XmlNameTable](../xmlnametable/) döndürür. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Geçerli düğümün tipini döndürür. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Geçerli düğümle ilişkili ad alanı ön ekini döndürür. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Bir öznitelik düğümünün değerini kapsayan tırnak işareti karakterini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | Bu [XmlValidatingReader](./) oluşturulurken kullanılan [XmlReader](../xmlreader/) döndürür. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Okuyucunun durumunu döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Şema doğrulaması sonucunda geçerli düğüme atanmış şema bilgilerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | Doğrulama için kullanılacak bir XmlSchemaCollection döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | Şema tipi nesnesi döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Bu [XmlReader](../xmlreader/) örneğini oluşturmak için kullanılan [XmlReaderSettings](../xmlreadersettings/) nesnesini döndürür. |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Gerçekleştirilecek doğrulama türünü gösteren bir değer döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Geçerli düğümün metin değerini döndürür. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Geçerli düğümün tipini döndürür. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Geçerli **xml:lang** kapsamını döndürür. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Geçerli **xml:space** kapsamını döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Belirtilen ada sahip özniteliğin değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ad ve ad alanı Birleşik Kaynak Tanımlayıcısına (URI) sahip özniteliğin değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Belirtilen indeksdeki özniteliğin değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeridir. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeridir. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Sınıfın satır bilgisi döndürüp döndüremeyeceğini gösteren bir değer döndürür. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen indeksdeki özniteliğin değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../xmlreader/get_name/) değerine sahip özniteliğin değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerine sahip özniteliğin değerini alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün benzeridir. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML adı olup olmadığını gösteren bir değer döndürür. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML ad belirteci olup olmadığını gösteren bir değer döndürür. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'i çağırır ve geçerli içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu sınar. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'i çağırır ve geçerli içerik düğümünün başlangıç etiketi mi boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_Name](../xmlreader/get_name/) değerinin verilen argümanla eşleşip eşleşmediğini sınar. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'i çağırır ve geçerli içerik düğümünün başlangıç etiketi mi boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleşip eşleşmediğini sınar. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemeyi uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Geçerli öğenin kapsamındaki bir ad alanı ön ekini çözer. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeridir. Özel tiplerin klonlanmasını sağlar. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Belirtilen ada sahip özniteliğe hareket eder. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ada ve ad alanı Birleşik Kaynak Tanımlayıcısına (URI) sahip özniteliğe hareket eder. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Belirtilen indeksdeki özniteliğe hareket eder. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Geçerli düğümün içerik (boşluk olmayan metin, **CDATA**, **Element**, **EndElement**, **EntityReference**, veya **EndEntity**) düğümü olup olmadığını denetler. Düğüm içerik düğümü değilse, okuyucu bir sonraki içerik düğümüne ya da dosyanın sonuna atlar. Aşağıdaki türdeki düğümleri atlar: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, veya **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Geçerli öznitelik düğümünü içeren öğeye hareket eder. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | İlk özniteliğe hareket eder. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Sonraki özniteliğe hareket eder. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarının ilklendirilmesini yapar. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, yalnızca yeni nesneyi ilklendirir ve alt sınıfların kopya yapımını mümkün kılar. |
| **bool** [Read](./read/)() override | Akıştan bir sonraki düğümü okur. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Öznitelik değerini bir veya daha fazla **[Text](../../system.text/)**, **EntityReference**, veya **EndEntity** düğümüne ayrıştırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | İçeriği belirtilen tipte bir nesne olarak okur. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve Base64 kodu çözülmüş ikili baytları döndürür. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve BinHex kodu çözülmüş ikili baytları döndürür. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Geçerli konumdaki metin içeriğini bir [Boolean](../../system/boolean/) olarak okur. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Geçerli konumdaki metin içeriğini bir [DateTime](../../system/datetime/) nesnesi olarak okur. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Geçerli konumdaki metin içeriğini bir [DateTimeOffset](../../system/datetimeoffset/) nesnesi olarak okur. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Geçerli konumdaki metin içeriğini bir [Decimal](../../system/decimal/) nesnesi olarak okur. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Geçerli konumdaki metin içeriğini çift hassasiyetli kayan nokta sayı olarak okur. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Geçerli konumdaki metin içeriğini tek hassasiyetli kayan nokta sayı olarak okur. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Geçerli konumdaki metin içeriğini 32-bit işaretli tamsayı olarak okur. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Geçerli konumdaki metin içeriğini 64-bit işaretli tamsayı olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Geçerli konumdaki metin içeriğini bir [Object](../../system/object/) olarak okur. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Geçerli konumdaki metin içeriğini bir [String](../../system/string/) nesnesi olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Eleman içeriğini istenen tipte okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından eleman içeriğini istenen tipte okur. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Elemanı okur ve Base64 içeriğini çözer. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Elemanı okur ve BinHex içeriğini çözer. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Geçerli elemanı okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Geçerli elemanı okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Geçerli elemanı okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Geçerli elemanı okur ve içeriği çift hassasiyetli kayan nokta sayı olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği çift hassasiyetli kayan nokta sayı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Geçerli elemanı okur ve içeriği tek hassasiyetli kayan nokta sayı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği tek hassasiyetli kayan nokta sayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Geçerli elemanı okur ve içeriği 32-bit işaretli tamsayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği 32-bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Geçerli elemanı okur ve içeriği 64-bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği 64-bit işaretli tamsayı olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Geçerli elemanı okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Geçerli elemanı okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli elemanla eşleştiğini kontrol eder, ardından geçerli elemanı okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Yalnızca metin içeren bir elemanı okur. Ancak, bu işlemi daha basit bir şekilde gerçekleştirmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Bulunan elemanın [XmlReader::get_Name](../xmlreader/get_name/) değeri verilen dizeyle eşleştiğini kontrol ettikten sonra yalnızca metin içeren bir eleman okur. Ancak, bu işlemi daha basit bir şekilde gerçekleştirmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Bulunan elemanın [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini kontrol ettikten sonra yalnızca metin içeren bir eleman okur. Ancak, bu işlemi daha basit bir şekilde gerçekleştirmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Geçerli içerik düğümünün bir bitiş etiketi olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, tüm içeriği, işaretlemeler dahil, bir dize olarak okur. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu düğüm ve tüm çocuklarını temsil eden içeriği, işaretleme dahil, bir dize olarak okur. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Geçerli düğümün bir eleman olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_Name](../xmlreader/get_name/) değerine sahip bir eleman olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerine sahip bir eleman olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Bir eleman ya da metin düğümünün içeriğini bir dize olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Geçerli düğümü ve tüm alt düğümlerini okumak için kullanılabilecek yeni bir [XmlReader](../xmlreader/) örneği döndürür. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir sonraki alt elemana [XmlReader](../xmlreader/)'yi ilerletir. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir sonraki alt elemana [XmlReader](../xmlreader/)'yi ilerletir. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir eleman bulunana kadar okur. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir eleman bulunana kadar okur. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir sonraki kardeş elemana [XmlReader](../xmlreader/)'yi ilerletir. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir sonraki kardeş elemana [XmlReader](../xmlreader/)'yi ilerletir. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | Belirtilen XML [Schema](../../system.xml.schema/) tanım dili (XSD) türü için çalışma zamanı tipini döndürür. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Bir XML belgesine gömülü büyük metin akışlarını okur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string ve nullptr durumları için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** düğümleri için varlık referansını çözer. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Okuyucunun varlıkları nasıl ele alacağını belirten bir değer ayarlar. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ad alanı desteğinin yapılacağını gösteren bir değer ayarlar. |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Yapılacak doğrulama türünü gösteren bir değer ayarlar. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | [XmlResolver](../xmlresolver/)'i harici belge tipi tanımı (DTD) ve şema konumu referanslarını çözmek için ayarlar. [XmlResolver](../xmlresolver/) ayrıca XML [Schema](../../system.xml.schema/) tanım dili (XSD) şemalarında bulunan tüm import veya include öğelerini işlemek için de kullanılır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon bağımsız değişkeni zayıf bir gösterici olarak ayarlar (paylaşılan yerine). Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual void [Skip](../xmlreader/skip/)() | Geçerli düğümün alt öğelerini atlar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özelleştirilmiş nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Belge tipi tanımı (DTD), XML-Data Reduced (XDR) şeması ve XML [Schema](../../system.xml.schema/) tanım dili (XSD) şema doğrulama hataları hakkında bilgi almak için bir olay işleyicisi ekler. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Belge tipi tanımı (DTD), XML-Data Reduced (XDR) şeması ve XML [Schema](../../system.xml.schema/) tanım dili (XSD) şema doğrulama hataları hakkında bilgi almak için bir olay işleyicisini kaldırır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | [XmlValidatingReader](./) sınıfının, verilen [XmlReader](../xmlreader/)'den dönen içeriği doğrulayan yeni bir örneğini başlatır. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlValidatingReader](./) sınıfının belirtilen değerlerle yeni bir örneğini başlatır. |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | [XmlValidatingReader](./) sınıfının belirtilen değerlerle yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak işaretçi takma adıdır. |

## Açıklamalar


Kullanımdan Kaldırıldı
:   Bu sınıf artık kullanılmıyor. Doğrulamalı bir XML okuyucu oluşturmak için [XmlReaderSettings](../xmlreadersettings/) sınıfı ve [XmlReader::Create](../xmlreader/create/) metodu kullanılmalıdır.
Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini yığıt üzerinde veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçmek için kullanın.

## Diğer Bağlantılar

* Sınıf [XmlReader](../xmlreader/)
* Sınıf [IXmlLineInfo](../ixmllineinfo/)
* Sınıf [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
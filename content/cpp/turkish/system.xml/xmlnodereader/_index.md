---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API Referansı
description: XmlNode içindeki XML verilerine hızlı, önbelleğe alınmamış yalnızca ileri erişim sağlayan bir okuyucuyu temsil eder.
type: docs
weight: 365
url: /tr/system.xml/xmlnodereader/
---
## XmlNodeReader sınıfı

XML verilerine hızlı, önbelleğe alınmamış, yalnızca ileri okuma erişimi sağlayan bir okuyucuyu temsil eder [XmlNode](../xmlnode/) içinde.

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| void [Close](./close/)() override | [XmlNodeReader::get_ReadState](./get_readstate/)'yi [ReadState::Closed](../readstate/)'ye değiştirir. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Belirtilen URI ile yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen URI, ayarlar ve ayrıştırma için bağlam bilgileri kullanılarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Varsayılan ayarlarla belirtilen akışı kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen akış ve ayarlarla yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen akış, temel URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen akış, ayarlar ve ayrıştırma bağlamı kullanılarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen metin okuyucuyu kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen metin okuyucu ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen metin okuyucu, ayarlar ve temel URI kullanılarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen metin okuyucu, ayarlar ve ayrıştırma bağlamı kullanılarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Belirtilen XML okuyucu ve ayarlar kullanılarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| void [Dispose](../xmlreader/dispose/)() override | Mevcut [XmlReader](../xmlreader/) sınıfı örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# benzeri kayan nokta karşılaştırması sağlar. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# benzeri kayan nokta karşılaştırması sağlar. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Mevcut düğümdeki öznitelik sayısını döndürür. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Mevcut düğümün temel URI'sını döndürür. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlNodeReader](./)'nin ikili içerik okuma yöntemlerini uygulayıp uygulamadığını belirten bir değer döndürür. |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | [XmlReader](../xmlreader/)'nin [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) metodunu uygulayıp uygulamadığını belirten bir değer döndürür. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Bu okuyucunun varlıkları ayrıştırıp çözümleyip çözemeyeceğini belirten bir değer döndürür. |
| **int32_t** [get_Depth](./get_depth/)() override | XML belgesindeki mevcut düğümün derinliğini döndürür. |
| **bool** [get_EOF](./get_eof/)() override | Okuyucunun akışın sonuna konumlandırılıp konumlandırılmadığını belirten bir değer döndürür. |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | Mevcut düğümün herhangi bir özniteliği olup olmadığını belirten bir değer döndürür. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Mevcut düğümün bir [XmlNodeReader::get_Value](./get_value/) değerine sahip olup olamayacağını belirten bir değer döndürür. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Mevcut düğümün, belge türü tanımı (DTD) veya şema içinde tanımlanan varsayılan değerden üretilen bir öznitelik olup olmadığını belirten bir değer döndürür. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Mevcut düğümün boş bir öğe olup olmadığını (ör. **<MyElement/>**) belirten bir değer döndürür. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Mevcut düğümün yerel adını döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Mevcut düğümün nitelikli adını döndürür. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Okuyucunun konumlandığı düğümün W3C Namespace spesifikasyonunda tanımlandığı gibi ad alanı URI'sını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Bu uygulama ile ilişkili [XmlNameTable](../xmlnametable/)'yi döndürür. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Mevcut düğümün tipini döndürür. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Mevcut düğümle ilişkili ad alanı önekini döndürür. |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bir öznitelik düğümünün değerini çevreleyen tırnak işareti karakterini döndürür. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Okuyucunun durumunu döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | Mevcut düğüme atanmış şema bilgilerini döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Bu [XmlReader](../xmlreader/) örneğini oluşturmak için kullanılan [XmlReaderSettings](../xmlreadersettings/) nesnesini döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Mevcut düğümün metin değerini döndürür. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Mevcut düğümün tipini döndürür. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Mevcut **xml:lang** kapsamını döndürür. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Mevcut **xml:space** kapsamını döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Belirtilen adla öznitelik değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ad ve ad alanı URI'sı ile öznitelik değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Belirtilen indeksle öznitelik değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğudur. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen indeksle öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../xmlreader/get_name/) değeriyle öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Türetilmiş bir sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerleriyle öznitelik değerini alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin hedefTür tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğudur. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML adı olup olmadığını belirten bir değer döndürür. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML ad belirteci olup olmadığını belirten bir değer döndürür. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'yi çağırır ve mevcut içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu test eder. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'yi çağırır ve mevcut içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_Name](../xmlreader/get_name/) değerinin verilen argümanla eşleşip eşleşmediğini test eder. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'yi çağırır ve mevcut içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleşip eşleşmediğini test eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Mevcut öğenin kapsamında bir ad alanı önekini çözer. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğudur. Özel tiplerin klonlanmasını sağlar. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Belirtilen adla özniteliğe geçer. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ad ve ad alanı URI'sı ile öznelliğe geçer. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Belirtilen indeksle öznelliğe geçer. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Mevcut düğümün içerik (boşluk olmayan metin, **CDATA**, **Element**, **EndElement**, **EntityReference** veya **EndEntity**) düğümü olup olmadığını denetler. Düğüm içerik değilse okuyucu bir sonraki içerik düğümüne veya dosya sonuna atlar. Aşağıdaki türdeki düğümleri atlar: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, veya **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Mevcut öznitelik düğümünü içeren öğeye geçer. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | İlk özniteliğe geçer. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Sonraki özniteliğe geçer. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| **bool** [Read](./read/)() override | Akıştan bir sonraki düğümü okur. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Öznitelik değerini bir veya daha fazla **[Text](../../system.text/)**, **EntityReference** veya **EndEntity** düğümüne ayrıştırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Belirtilen tipe sahip bir nesne olarak içeriği okur. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve Base64 çözülen ikili baytları döndürür. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve BinHex çözülen ikili baytları döndürür. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Mevcut konumdaki metin içeriğini bir [Boolean](../../system/boolean/) olarak okur. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Mevcut konumdaki metin içeriğini bir [DateTime](../../system/datetime/) nesnesi olarak okur. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Mevcut konumdaki metin içeriğini bir [DateTimeOffset](../../system/datetimeoffset/) nesnesi olarak okur. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Mevcut konumdaki metin içeriğini bir [Decimal](../../system/decimal/) nesnesi olarak okur. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Mevcut konumdaki metin içeriğini çift duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Mevcut konumdaki metin içeriğini tek duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Mevcut konumdaki metin içeriğini 32-bit işaretli tam sayı olarak okur. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Mevcut konumdaki metin içeriğini 64-bit işaretli tam sayı olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Mevcut konumdaki metin içeriğini bir [Object](../../system/object/) olarak okur. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Geçerli konumdaki metin içeriğini bir [String](../../system/string/) nesnesi olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | İstenen türde öğe içeriğini okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından öğe içeriğini istenen türde okur. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Öğeyi okur ve Base64 içeriğini çözer. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Öğeyi okur ve BinHex içeriğini çözer. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel adın ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Sadece metin içeren bir öğeyi okur. Ancak, bu işlemi daha doğrudan bir şekilde ele alması nedeniyle [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Bulunan öğenin [XmlReader::get_Name](../xmlreader/get_name/) değerinin verilen dizeyle eşleştiğini kontrol eder, ardından sadece metin içeren bir öğeyi okur. Ancak, bu işlemi daha doğrudan bir şekilde ele alması nedeniyle [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Bulunan öğenin [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini kontrol eder, ardından sadece metin içeren bir öğeyi okur. Ancak, bu işlemi daha doğrudan bir şekilde ele alması nedeniyle [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) metodunun kullanılması önerilir. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Geçerli içerik düğümünün bir bitiş etiketi olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, tüm içeriği (işaretlemeler dahil) bir dize olarak okur. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu düğümün ve tüm alt düğümlerinin içeriğini (işaretlemeler dahil) okur. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Geçerli düğümün bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_Name](../xmlreader/get_name/) değerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Bir öğenin veya metin düğümünün içeriğini bir dize olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Geçerli düğümü ve tüm alt düğümlerini okumak için kullanılabilecek yeni bir [XmlReader](../xmlreader/) örneği döndürür. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Belirtilen nitelikli adı taşıyan bir sonraki alt öğeye [XmlReader](../xmlreader/) ilerletir. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir sonraki alt öğeye [XmlReader](../xmlreader/) ilerletir. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Belirtilen nitelikli adı taşıyan bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Belirtilen nitelikli adı taşıyan bir sonraki kardeş öğeye [XmlReader](../xmlreader/) ilerletir. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sine sahip bir sonraki kardeş öğeye [XmlReader](../xmlreader/) ilerletir. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Bir XML belgesine gömülü büyük metin akışlarını okur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/)'nin özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** düğümleri için varlık referansını çözer. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını bir zayıf gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişine olanak tanır. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [Skip](./skip/)() override | Geçerli düğümün çocuklarını atlar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | [XmlNodeReader](./) sınıfının bir örneğini belirtilen [XmlNode](../xmlnode/) kullanarak oluşturur. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Tip Tanımları

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine paylaşılan gösterici için bir takma addır. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini yığıt üzerinde ya da operator new ile oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı bir [System::SmartPtr](../../system/smartptr/) gösterici içinde tutun ve bu göstericiyi işlevlere argüman olarak geçirin. 

## Bakınız

* Sınıf [XmlReader](../xmlreader/)
* Sınıf [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
---
title: XmlTextReader
second_title: Aspose.Slides for C++ API Referansı
description: XML verilerine hızlı, önbelleğe alınmamış, yalnızca ileri yönde erişim sağlayan bir okuyucuyu temsil eder.
type: docs
weight: 508
url: /tr/system.xml/xmltextreader/
---
## XmlTextReader sınıf

XML verilerine hızlı, önbelleğe alınmamış, yalnızca ileri yönde erişim sağlayan bir okuyucuyu temsil eder.

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## Metotlar

| Metod | Açıklama |
| --- | --- |
| void [Close](./close/)() override | [XmlReader::get_ReadState](../xmlreader/get_readstate/)'yi **Closed**'a değiştirir. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | Belirtilen URI ile yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen URI, ayarlar ve ayrıştırma için bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akışı varsayılan ayarlarla kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen akış ve ayarlarla yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen akış, temel URI ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen akış, ayarlar ve ayrıştırma bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen metin okuyucusunu kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen metin okuyucusu ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen metin okuyucusu, ayarlar ve temel URI'yi kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen metin okuyucusu, ayarlar ve ayrıştırma bağlam bilgilerini kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Belirtilen XML okuyucu ve ayarları kullanarak yeni bir [XmlReader](../xmlreader/) örneği oluşturur. |
| void [Dispose](../xmlreader/dispose/)() override | [XmlReader](../xmlreader/) sınıfının geçerli örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiğiyle karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipindeki nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipindeki nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere (NaN dahil) eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere (NaN dahil) eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | Geçerli düğümdeki öznitelik sayısını döndürür. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | Geçerli düğümün temel URI'sini döndürür. |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | [XmlTextReader](./)'nin ikili içerik okuma yöntemlerini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | [XmlTextReader](./)'nin [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) yöntemini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | Bu okuyucunun varlıkları (entity) ayrıştırıp çözüp çözemeyeceğini gösteren bir değer döndürür. |
| **int32_t** [get_Depth](./get_depth/)() override | XML belgesindeki geçerli düğümün derinliğini döndürür. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | DtdProcessing enum değerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Belgenin kodlamasını döndürür. |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | Okuyucunun varlıkları nasıl işlediğini belirten bir değer döndürür. |
| **bool** [get_EOF](./get_eof/)() override | Okuyucunun akışın sonuna konumlandırılıp konumlandırılmadığını gösteren bir değer döndürür. |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | Geçerli düğümün herhangi bir özniteliği olup olmadığını gösteren bir değer döndürür. |
| **bool** [get_HasValue](./get_hasvalue/)() override | Geçerli düğümün [XmlTextReader::get_Value](./get_value/)'nin [String::Empty](../../system/string/empty/) dışında bir değere sahip olup olamayacağını gösteren bir değer döndürür. |
| **bool** [get_IsDefault](./get_isdefault/)() override | Geçerli düğümün DTD ya da şemada tanımlı varsayılan değerden üretilen bir öznitelik olup olmadığını gösteren bir değer döndürür. |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | Geçerli düğümün boş bir öğe olup olmadığını gösterir (örnek: **<MyElement/>**). |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | Geçerli satır numarasını döndürür. |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | Geçerli satır konumunu döndürür. |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | Geçerli düğümün yerel adını döndürür. |
| [String](../../system/string/) [get_Name](./get_name/)() override | Geçerli düğümün nitelikli adını döndürür. |
| **bool** [get_Namespaces](./get_namespaces/)() | Ad alanı desteği uygulanıp uygulanmayacağını gösteren bir değer döndürür. |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | Okuyucunun konumlandığı düğümün ad alanı URI'sini (W3C Namespace spesifikasyonunda tanımlandığı gibi) döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | Bu uygulamayla ilişkilendirilen [XmlNameTable](../xmlnametable/)'yi döndürür. |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | Geçerli düğümün tipini döndürür. |
| **bool** [get_Normalization](./get_normalization/)() | Boşlukları ve öznitelik değerlerini normalleştirip normalleştirilmeyeceğini gösteren bir değer döndürür. |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | Geçerli düğümle ilişkilendirilen ad alanı önekini döndürür. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | DTD işlenmesine izin verilip verilmeyeceğini gösteren bir değer döndürür. |
| char16_t [get_QuoteChar](./get_quotechar/)() override | Bir öznitelik düğümünün değerini çevrelemek için kullanılan tırnak karakterini döndürür. |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | Okuyucunun durumunu döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | Şema doğrulaması sonucunda geçerli düğüme atanmış şema bilgisini döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | Bu [XmlReader](../xmlreader/) örneğini oluşturmak için kullanılan [XmlReaderSettings](../xmlreadersettings/) nesnesini döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() override | Geçerli düğümün metin değerini döndürür. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | Geçerli düğüm için tip döndürür. |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | Boşlukların nasıl işlendiğini belirten bir değer döndürür. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | Geçerli **xml:lang** kapsamını döndürür. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | Geçerli **xml:space** kapsamını döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | Belirtilen isimdeki özniteliğin değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ad ve ad alanı URI'sine sahip özniteliğin değerini döndürür. |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | Belirtilen indeksli özniteliğin değerini döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkilendirilen referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | Şu anda kapsam içinde olan tüm ad alanlarını içeren bir koleksiyon döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | Tamponlanmış XML'in kalan kısmını döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| **bool** [HasLineInfo](./haslineinfo/)() override | Sınıfın satır bilgisi döndürebilirliğini gösteren bir değer döndürür. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen indeksli öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](../xmlreader/get_name/) değerine sahip öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | Türetilmiş sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerine sahip öznitelik değerini alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML adı olup olmadığını gösteren bir değer döndürür. |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML adı belirteci olup olmadığını gösteren bir değer döndürür. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'i çağırır ve geçerli içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu test eder. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'yi çağırır ve geçerli içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_Name](../xmlreader/get_name/) değerinin verilen argümanla eşleşip eşleşmediğini test eder. |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](../xmlreader/movetocontent/)'yi çağırır ve geçerli içerik düğümünün başlangıç etiketi mi yoksa boş öğe etiketi mi olduğunu ve bulunan öğenin [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleşip eşleşmediğini test eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Geçerli öğenin kapsamındaki bir ad alanı önekini çözer. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | Belirtilen isimdeki özniteliğe geçer. |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | Belirtilen yerel ad ve ad alanı URI'sine sahip özniteliğe geçer. |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | Belirtilen indeksli özniteliğe geçer. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | Geçerli düğümün içerik (boşluk dışı metin, **CDATA**, **Element**, **EndElement**, **EntityReference** veya **EndEntity**) düğümü olup olmadığını kontrol eder. Düğüm içerik düğümü değilse, okuyucu bir sonraki içerik düğümüne ya da dosyanın sonuna atlar. Aşağıdaki tipteki düğümleri atlar: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace** veya **SignificantWhitespace**. |
| **bool** [MoveToElement](./movetoelement/)() override | Geçerli öznitelik düğümünü içeren öğeye geçer. |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | İlk özniteliğe geçer. |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | Sonraki özniteliğe geçer. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| **bool** [Read](./read/)() override | Akıştan bir sonraki düğümü okur. |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | Öznitelik değerini bir veya daha fazla **[Text](../../system.text/)**, **EntityReference** veya **EndEntity** düğümüne ayrıştırır. |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | Base64'i çözer ve çözülen ikili baytları döndürür. |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | **BinHex**'i çözer ve çözülen ikili baytları döndürür. |
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Bir öğenin metin içeriğini bir karakter tamponuna okur. Bu yöntem, gömülü metnin büyük akışlarını ardışık olarak çağırarak okumak için tasarlanmıştır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | İçeriği belirtilen tipte bir nesne olarak okur. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve Base64 ile çözülen ikili baytları döndürür. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | İçeriği okur ve BinHex ile çözülen ikili baytları döndürür. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Geçerli konumdaki metin içeriğini bir [Boolean](../../system/boolean/) olarak okur. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Geçerli konumdaki metin içeriğini bir [DateTime](../../system/datetime/) nesnesi olarak okur. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Geçerli konumdaki metin içeriğini bir [DateTimeOffset](../../system/datetimeoffset/) nesnesi olarak okur. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Geçerli konumdaki metin içeriğini bir [Decimal](../../system/decimal/) nesnesi olarak okur. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Geçerli konumdaki metin içeriğini çift duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Geçerli konumdaki metin içeriğini tek duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Geçerli konumdaki metin içeriğini 32 bit işaretli tamsayı olarak okur. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Geçerli konumdaki metin içeriğini 64 bit işaretli tamsayı olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Geçerli konumdaki metin içeriğini bir [Object](../../system/object/) olarak okur. |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Geçerli konumdaki metin içeriğini bir [String](../../system/string/) nesnesi olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Öğenin içeriğini istenen tipte okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından öğenin içeriğini istenen tipte okur. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Öğeyi okur ve Base64 içeriğini çözer. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Öğeyi okur ve BinHex içeriğini çözer. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayı olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) yönteminin kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Bulunan öğenin [XmlReader::get_Name](../xmlreader/get_name/) değerinin verilen dizeyle eşleştiğini kontrol eder, ardından yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) yönteminin kullanılması önerilir. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini kontrol eder, ardından yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) yönteminin kullanılması önerilir. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Geçerli içerik düğümünün bir son etiket olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | Türetilmiş bir sınıfta ezildiğinde, işaretleme dahil tüm içeriği bir dize olarak okur. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | Türetilmiş bir sınıfta ezildiğinde, bu düğümü ve tüm alt düğümlerini temsil eden işaretleme dahil içeriği okur. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Geçerli düğümün bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_Name](../xmlreader/get_name/) değerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_LocalName](../xmlreader/get_localname/) ve [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) değerlerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Bir öğenin veya metin düğümünün içeriğini bir dize olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Geçerli düğümü ve tüm alt düğümlerini okumak için kullanılabilecek yeni bir [XmlReader](../xmlreader/) örneği döndürür. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | [XmlReader](../xmlreader/) öğesini belirtilen nitelikli ada sahip bir sonraki alt öğeye ilerletir. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) öğesini belirtilen yerel ada ve ad alanı URI'sine sahip bir sonraki alt öğeye ilerletir. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ada ve ad alanı URI'sine sahip bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | [XmlReader](../xmlreader/) öğesini belirtilen nitelikli ada sahip bir sonraki kardeş öğeye ilerletir. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader](../xmlreader/) öğesini belirtilen yerel ada ve ad alanı URI'sine sahip bir sonraki kardeş öğeye ilerletir. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Bir XML belgesine gömülü büyük metin akışlarını okur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [ResetState](./resetstate/)() | Okuyucunun durumunu [ReadState::Initial](../readstate/)'ye sıfırlar. |
| void [ResolveEntity](./resolveentity/)() override | **EntityReference** düğümleri için varlık referansını çözer. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | DtdProcessing ayrık tipini ayarlar. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Okuyucunun varlıkları nasıl işleyeceğini belirten bir değeri ayarlar. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Ad alanı desteği yapılacak mı diye gösteren bir değeri ayarlar. |
| void [set_Normalization](./set_normalization/)(**bool**) | Boşluk ve öznitelik değerlerini normalleştirip normalleştirilmeyeceğini belirten bir değeri ayarlar. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | DTD işlemesine izin verilip verilmeyeceğini belirten bir değeri ayarlar. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Boşlukların nasıl ele alınacağını belirten bir değeri ayarlar. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | DTD referanslarını çözmek için kullanılan [XmlResolver](../xmlresolver/)'yi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeyi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının geçerli değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Skip](./skip/)() override | Geçerli düğümün alt öğelerini atlar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açmayı uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akış ile yeni bir [XmlTextReader](./) sınıfı örneği başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen URL ve akış ile yeni bir [XmlTextReader](./) sınıfı örneği başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Belirtilen akış ve [XmlNameTable](../xmlnametable/) ile yeni bir [XmlTextReader](./) sınıfı örneği başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Belirtilen URL, akış ve [XmlNameTable](../xmlnametable/) ile yeni bir [XmlTextReader](./) sınıfı örneği başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen TextReader ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen URL ve TextReader ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Belirtilen TextReader ve [XmlNameTable](../xmlnametable/) ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Belirtilen URL, TextReader ve [XmlNameTable](../xmlnametable/) ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen akış, XmlNodeType ve [XmlParserContext](../xmlparsercontext/) ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen dize, XmlNodeType ve [XmlParserContext](../xmlparsercontext/) ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | Belirtilen dosya ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Belirtilen dosya ve [XmlNameTable](../xmlnametable/) ile [XmlTextReader](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |
## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı işaretçi için bir takma ad. |
## Açıklamalar

Bunun yerine [XmlReader](../xmlreader/) sınıfını kullanmanız önerilir. 

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak ayrılmalıdır. Bu tipin örneklerini yığıt üzerinde veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. 

## Diğer

* Sınıf [XmlReader](../xmlreader/)
* Sınıf [IXmlLineInfo](../ixmllineinfo/)
* Sınıf [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
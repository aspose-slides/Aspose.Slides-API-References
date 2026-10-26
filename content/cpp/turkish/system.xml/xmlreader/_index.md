---
title: XmlReader
second_title: Aspose.Slides for C++ API Referansı
description: XML verilerine hızlı, önbelleğe alınmamış, yalnızca ileri okuma erişimi sağlayan bir okuyucuyu temsil eder.
type: docs
weight: 430
url: /tr/system.xml/xmlreader/
---
## XmlReader sınıfı

XML verilerine hızlı, önbelleğe alınmamış, yalnızca ileri yönde erişim sağlayan bir okuyucuyu temsil eder.

```cpp
class XmlReader : public System::IDisposable
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Türev sınıfta geçersiz kılındığında, [XmlReader::get_ReadState](./get_readstate/) değerini [ReadState::Closed](../readstate/) olarak değiştirir. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | Belirtilen URI ile yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen URI ve ayarları kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen URI, ayarlar ve ayrıştırma için bağlam bilgisini kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Belirtilen akışı varsayılan ayarlarla kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen akış ve ayarlarla yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen akış, temel URI ve ayarları kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen akış, ayarlar ve ayrıştırma bağlam bilgisini kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | Belirtilen metin okuyucuyu kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | Belirtilen metin okuyucu ve ayarları kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | Belirtilen metin okuyucu, ayarlar ve temel URI'yi kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | Belirtilen metin okuyucu, ayarlar ve ayrıştırma bağlam bilgisiyle yeni bir [XmlReader](./) örneği oluşturur. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | Belirtilen XML okuyucu ve ayarları kullanarak yeni bir [XmlReader](./) örneği oluşturur. |
| void [Dispose](./dispose/)() override | [XmlReader](./) sınıfının mevcut örneği tarafından kullanılan tüm kaynakları serbest bırakır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümdeki öznitelik sayısını alır. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün temel URI'sini alır. |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | [XmlReader](./)'ın ikili içerik okuma yöntemlerini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | [XmlReader](./)'ın [XmlReader::ReadValueChunk](./readvaluechunk/) yöntemini uygulayıp uygulamadığını gösteren bir değer döndürür. |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | Bu okuyucunun varlıkları ayrıştırıp çözümleyip çözümleyemediğini gösteren bir değer döndürür. |
| virtual **int32_t** [get_Depth](./get_depth/)() | Türev sınıfta geçersiz kılındığında, XML belgesindeki geçerli düğümün derinliğini alır. |
| virtual **bool** [get_EOF](./get_eof/)() | Türev sınıfta geçersiz kılındığında, okuyucunun akışın sonunda konumlanıp konumlanmadığını gösteren bir değeri alır. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Geçerli düğümün herhangi bir özniteliği olup olmadığını gösteren bir değer döndürür. |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün [XmlReader::get_Value](./get_value/) değerine sahip olup olamayacağını gösteren bir değeri alır. |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün DTD veya şemada tanımlı varsayılan değerden üretilen bir öznitelik olup olmadığını gösteren bir değeri alır. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün boş bir öğe olup olmadığını (örneğin **<MyElement/>**) gösteren bir değeri alır. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün yerel adını alır. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün nitelikli adını alır. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | Türev sınıfta geçersiz kılındığında, okuyucunun konumlandığı düğümün (W3C Namespace specine göre) namespace URI'sini alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Türev sınıfta geçersiz kılındığında, bu uygulamaya bağlı [XmlNameTable](../xmlnametable/)'yi alır. |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün türünü alır. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümle ilişkili namespace önekini alır. |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | Türev sınıfta geçersiz kılındığında, bir öznitelik düğümünün değerini çevreleyen tırnak karakterini alır. |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | Türev sınıfta geçersiz kılındığında, okuyucunun durumunu alır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Şema doğrulaması sonucu geçerli düğüme atanan şema bilgisini döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | Bu [XmlReader](./) örneğini oluşturmak için kullanılan [XmlReaderSettings](../xmlreadersettings/) nesnesini döndürür. |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | Türev sınıfta geçersiz kılındığında, geçerli düğümün metin değerini alır. |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | Geçerli düğümün türünü döndürür. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Türev sınıfta geçersiz kılındığında, geçerli **xml:lang** kapsamını alır. |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Türev sınıfta geçersiz kılındığında, geçerli **xml:space** kapsamını alır. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](./get_name/) değerine sahip öznitelik değerini alır. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerine sahip öznitelik değerini alır. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | Türev sınıfta geçersiz kılındığında, belirtilen indeksle öznitelik değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | Türev sınıfta geçersiz kılındığında, belirtilen indeksle öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](./get_name/) değerine sahip öznitelik değerini alır. |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerine sahip öznitelik değerini alır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türe ait bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML adı olup olmadığını gösteren bir değer döndürür. |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | Dize argümanının geçerli bir XML ad token'ı olup olmadığını gösteren bir değer döndürür. |
| virtual **bool** [IsStartElement](./isstartelement/)() | [XmlReader::MoveToContent](./movetocontent/)'i çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş öğe etiketi olup olmadığını test eder. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/)'i çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş öğe etiketi olup olmadığını ve bulunan öğenin [XmlReader::get_Name](./get_name/) değerinin verilen argümanla eşleşip eşleşmediğini test eder. |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | [XmlReader::MoveToContent](./movetocontent/)'i çağırır ve geçerli içerik düğümünün bir başlangıç etiketi veya boş öğe etiketi olup olmadığını ve bulunan öğenin [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerinin verilen dizelerle eşleşip eşleşmediğini test eder. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Direkt olarak çağırın veya [LockContext](../../system/lockcontext/) gözcüsü nesnesini kullanın. |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | Türev sınıfta geçersiz kılındığında, geçerli öğenin kapsamındaki bir namespace önekini çözümler. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_Name](./get_name/) değerine sahip özniteliğe gider. |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Türev sınıfta geçersiz kılındığında, belirtilen [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerine sahip özniteliğe gider. |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | Türev sınıfta geçersiz kılındığında, belirtilen indeksle özniteliğe gider. |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | Geçerli düğümün bir içerik (boşluk olmayan metin, **CDATA**, **Element**, **EndElement**, **EntityReference** veya **EndEntity**) düğümü olup olmadığını kontrol eder. Düğüm içerik düğümü değilse, okuyucu bir sonraki içerik düğümüne ya da dosya sonuna atlar. Aşağıdaki türdeki düğümleri atlar: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, **SignificantWhitespace**. |
| virtual **bool** [MoveToElement](./movetoelement/)() | Türev sınıfta geçersiz kılındığında, geçerli öznitelik düğümünü içeren öğeye gider. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | Türev sınıfta geçersiz kılındığında, ilk özniteliğe gider. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | Türev sınıfta geçersiz kılındığında, bir sonraki özniteliğe gider. |
|   [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya üretimini sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya üretimini sağlar. |
| virtual **bool** [Read](./read/)() | Türev sınıfta geçersiz kılındığında, akıştan bir sonraki düğümü okur. |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | Türev sınıfta geçersiz kılındığında, öznitelik değerini bir veya daha fazla **[Text](../../system.text/)**, **EntityReference** veya **EndEntity** düğümüne ayrıştırır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | İçeriği belirtilen tipte bir nesne olarak okur. |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | İçeriği okuyup Base64 ile kod çözülmüş ikili baytları döndürür. |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | İçeriği okuyup **BinHex** ile kod çözülmüş ikili baytları döndürür. |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | Geçerli konumdaki metin içeriğini bir [Boolean](../../system/boolean/) olarak okur. |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | Geçerli konumdaki metin içeriğini bir [DateTime](../../system/datetime/) nesnesi olarak okur. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | Geçerli konumdaki metin içeriğini bir [DateTimeOffset](../../system/datetimeoffset/) nesnesi olarak okur. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | Geçerli konumdaki metin içeriğini bir [Decimal](../../system/decimal/) nesnesi olarak okur. |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | Geçerli konumdaki metin içeriğini çift duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | Geçerli konumdaki metin içeriğini tek duyarlıklı kayan nokta sayısı olarak okur. |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | Geçerli konumdaki metin içeriğini 32 bit işaretli tamsayı olarak okur. |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | Geçerli konumdaki metin içeriğini 64 bit işaretli tamsayı olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | Geçerli konumdaki metin içeriğini bir [Object](../../system/object/) olarak okur. |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | Geçerli konumdaki metin içeriğini bir [String](../../system/string/) nesnesi olarak okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Öğenin içeriğini istenen türde okur. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından öğe içeriğini istenen türde okur. |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Öğeyi okur ve **Base64** içeriğini çözer. |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | Öğeyi okur ve **BinHex** içeriğini çözer. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | Geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Boolean](../../system/boolean/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | Geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [DateTime](../../system/datetime/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | Geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Decimal](../../system/decimal/) nesnesi olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | Geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği çift duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | Geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği tek duyarlıklı kayan nokta sayısı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | Geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 32 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | Geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği 64 bit işaretli tamsayı olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | Geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [Object](../../system/object/) olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | Geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ad ve ad alanı URI'sinin geçerli öğeyle eşleştiğini kontrol eder, ardından geçerli öğeyi okur ve içeriği bir [String](../../system/string/) nesnesi olarak döndürür. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | Yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) yöntemi kullanılmalıdır. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | Bulunan öğenin [XmlReader::get_Name](./get_name/) değerinin verilen dizeyle eşleştiğini kontrol eder, ardından yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) yöntemi kullanılmalıdır. |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Bulunan öğenin [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerinin verilen dizelerle eşleştiğini kontrol eder, ardından yalnızca metin içeren bir öğeyi okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) yöntemi kullanılmalıdır. |
| virtual void [ReadEndElement](./readendelement/)() | Geçerli içerik düğümünün bir kapanış etiketi olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, işaretlemeyi de içeren tüm içeriği bir dize olarak okur. |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bu düğümü ve tüm alt düğümlerini temsil eden içeriği, işaretlemeyi de içerecek şekilde okur. |
| virtual void [ReadStartElement](./readstartelement/)() | Geçerli düğümün bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_Name](./get_name/) değerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Geçerli içerik düğümünün verilen [XmlReader::get_LocalName](./get_localname/) ve [XmlReader::get_NamespaceURI](./get_namespaceuri/) değerlerine sahip bir öğe olduğunu kontrol eder ve okuyucuyu bir sonraki düğüme ilerletir. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Türetilmiş bir sınıfta geçersiz kılındığında, bir öğe veya metin düğümünün içeriğini bir dize olarak okur. Ancak, bu işlemi daha basit bir şekilde yönetmek için [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) yöntemi kullanılmalıdır. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | Geçerli düğümü ve tüm alt düğümlerini okumak için kullanılabilecek yeni bir [XmlReader](./) örneği döndürür. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir sonraki alt öğeye [XmlReader](./)'yi ilerletir. |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ada ve ad alanı URI'sine sahip bir sonraki alt öğeye [XmlReader](./)'yi ilerletir. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ada ve ad alanı URI'sine sahip bir öğe bulunana kadar okur. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | Belirtilen nitelikli ada sahip bir sonraki kardeş öğeye [XmlReader](./)'yi ilerletir. |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen yerel ada ve ad alanı URI'sine sahip bir sonraki kardeş öğeye [XmlReader](./)'yi ilerletir. |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | XML belgesine gömülmüş büyük metin akışlarını okur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hâli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [ResolveEntity](./resolveentity/)() | Türetilmiş bir sınıfta geçersiz kılındığında, **EntityReference** düğümleri için varlık referansını çözer. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı değil) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının şu anki değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual void [Skip](./skip/)() | Geçerli düğümün alt öğelerini atlar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapıları serbest bırakılır. |

## Tip Tanımları

| Tip Tanımı | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine shared pointer için bir takma addır. |

## Ayrıca Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
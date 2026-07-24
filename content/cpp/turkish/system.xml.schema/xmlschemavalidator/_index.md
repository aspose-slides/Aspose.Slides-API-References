---
title: XmlSchemaValidator
second_title: C++ için Aspose.Slides API Referansı
description: XML Şema Tanım Dili (XSD) şema doğrulama motorunu temsil eder. XmlSchemaValidator sınıfı miras alınamaz.
type: docs
weight: 937
url: /tr/system.xml.schema/xmlschemavalidator/
---
## XmlSchemaValidator sınıfı


XML [Schema](../) Tanım Dili (XSD) [Schema](../) doğrulama motorunu temsil eder. [XmlSchemaValidator](./) sınıfı miras alınamaz.

```cpp
class XmlSchemaValidator : public System::Object
```

## Yöntemler

| Metot | Açıklama |
| --- | --- |
| void [AddSchema](./addschema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | Doğrulama için kullanılan şema kümesine bir XML [Schema](../) Tanım Dili (XSD) şeması ekler. |
| void [EndValidation](./endvalidation/)() | Doğrulamayı sonlandırır ve tüm XML belgesi için kimlik kısıtlamalarını kontrol eder. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\> [get_LineInfoProvider](./get_lineinfoprovider/)() | Doğrulanan XML düğümünün satır numarası bilgisini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_SourceUri](./get_sourceuri/)() | Doğrulanan XML düğümünün kaynak URI'sını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ValidationEventSender](./get_validationeventsender/)() | Bir doğrulama olayının gönderici nesnesi olarak gönderilen nesneyi döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaAttribute](../xmlschemaattribute/)\>\> [GetExpectedAttributes](./getexpectedattributes/)() | Geçerli öğe bağlamı için beklenen öznitelikleri döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\> [GetExpectedParticles](./getexpectedparticles/)() | Geçerli öğe bağlamındaki beklenen parçacıkları döndürür. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| void [GetUnspecifiedDefaultAttributes](./getunspecifieddefaultattributes/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\>\&) | Varsayılan öznitelikler üzerindeki kimlik kısıtlamalarını doğrular ve öğe bağlamında [XmlSchemaValidator::ValidateAttribute](./validateattribute/) metodu önceden doğrulanmamış varsayılan değere sahip öznitelikler için [XmlSchemaAttribute](../xmlschemaattribute/) nesneleriyle belirtilen Listeyi doldurur. |
| void [Initialize](./initialize/)() | [XmlSchemaValidator](./) nesnesinin durumunu başlatır. |
| void [Initialize](./initialize/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | [XmlSchemaValidator](./) nesnesinin durumunu, kısmi doğrulama için belirtilen [XmlSchemaObject](../xmlschemaobject/) kullanarak başlatır. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_LineInfoProvider](./set_lineinfoprovider/)(const [SharedPtr](../../system/sharedptr/)\<[IXmlLineInfo](../../system.xml/ixmllineinfo/)\>\&) | Doğrulanan XML düğümünün satır numarası bilgisini ayarlar. |
| void [set_SourceUri](./set_sourceuri/)(const [SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>\&) | Doğrulanan XML düğümünün kaynak URI'sını ayarlar. |
| void [set_ValidationEventSender](./set_validationeventsender/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Bir doğrulama olayının gönderici nesnesi olarak gönderilen nesneyi ayarlar. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | [XmlResolver](../../system.xml/xmlresolver/) nesnesini, **xs:import** ve **xs:include** öğelerini ve ayrıca **xsi:schemaLocation** ve **xsi:noNamespaceSchemaLocation** özniteliklerini çözümlemek için ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını paylaşılan yerine zayıf gösterici olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçişini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [SkipToEndElement](./skiptoendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Geçerli öğenin içeriğinin doğrulamasını atlar ve [XmlSchemaValidator](./) nesnesini üst öğe bağlamında içeriği doğrulamak için hazırlar. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidi açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateAttribute](./validateattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [XmlValueGetter](../xmlvaluegetter/), const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Geçerli öğe bağlamında öznitelik adını, ad alanı URI'sını ve değerini doğrular. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Geçerli bağlamda öğeyi doğrular. |
| void [ValidateElement](./validateelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Belirtilen **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** ve **xsi:NoNamespaceSchemaLocation** öznitelik değerleriyle birlikte geçerli bağlamdaki öğeyi doğrular. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Basit içerikli öğeler için öğenin metin içeriğinin veri tipine göre geçerli olup olmadığını ve karmaşık içerikli öğeler için geçerli öğenin içeriğinin tamamlanmış olup olmadığını doğrular. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValidateEndElement](./validateendelement/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Belirtilen öğenin metin içeriğinin veri tipine göre geçerli olup olmadığını doğrular. |
| void [ValidateEndOfAttributes](./validateendofattributes/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaInfo](../xmlschemainfo/)\>\&) | Öğe bağlamındaki tüm zorunlu özniteliklerin mevcut olup olmadığını doğrular ve [XmlSchemaValidator](./) nesnesini öğenin alt içeriğini doğrulamak için hazırlar. |
| void [ValidateText](./validatetext/)(const [String](../../system/string/)\&) | Belirtilen metin **string**'in geçerli öğe bağlamında izin verilip verilmediğini doğrular ve öğe basit içerikli ise doğrulama için metni biriktirir. |
| void [ValidateText](./validatetext/)([XmlValueGetter](../xmlvaluegetter/)) | Belirtilen XmlValueGetter nesnesi tarafından döndürülen metnin geçerli öğe bağlamında izin verilip verilmediğini doğrular ve öğe basit içerikli ise doğrulama için metni biriktirir. |
| void [ValidateWhitespace](./validatewhitespace/)(const [String](../../system/string/)\&) | Belirtilen **string** içindeki boşlukların geçerli öğe bağlamında izin verilip verilmediğini doğrular ve öğe basit içerikli ise doğrulama için boşlukları biriktirir. |
| void [ValidateWhitespace](./validatewhitespace/)([XmlValueGetter](../xmlvaluegetter/)) | Belirtilen XmlValueGetter nesnesi tarafından döndürülen boşlukların geçerli öğe bağlamında izin verilip verilmediğini doğrular ve öğe basit içerikli ise doğrulama için boşlukları biriktirir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [XmlSchemaValidator](./xmlschemavalidator/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](../xmlschemaset/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>\&, [XmlSchemaValidationFlags](../xmlschemavalidationflags/)) | [XmlSchemaValidator](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı gösterici için bir takma isim. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) fonksiyonu kullanılarak allocate edilmelidir. Bu tipin örneklerini yığıt üzerinde veya operator new ile oluşturmayın; aksi takdirde çalışma zamanı hataları ve/veya assert hataları oluşur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin. 

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Xml::Schema](../)
* Kütüphane [Aspose.Slides](../../)
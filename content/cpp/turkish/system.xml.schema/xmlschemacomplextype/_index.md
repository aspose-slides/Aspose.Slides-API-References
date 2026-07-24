---
title: XmlSchemaComplexType
second_title: Aspose.Slides for C++ API Referansı
description: XML Şeması'ndan World Wide Web Consortium (W3C) tarafından belirlenen complexType öğesini temsil eder. Bu sınıf, bir öğenin öznitelik ve içerik kümesini belirleyen bir karmaşık tipi tanımlar.
type: docs
weight: 300
url: /tr/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType sınıfı


XML [Schema](../)'dan **complexType** öğesini, World Wide [Web](../../system.web/) Consortium (W3C) tarafından belirtildiği gibi temsil eder. Bu sınıf, bir öğenin öznitelik ve içerik kümesini belirleyen bir karmaşık tip tanımlar.

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C#-tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | **annotation** özelliğini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşeninin karmaşık tip için değerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | Karmaşık tipin öznitelik koleksiyonunu döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | Bu karmaşık tipin ve temel tiplerinin tüm derlenmiş öznitelik koleksiyonunu döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | **anyAttribute** için bu karmaşık tip ve temel tip(ler) için derleme sonrası değeri döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | Derleme sonrası nesne tipini veya yerleşik XML [Schema](../) Tanım Dili (XSD) veri tipini, simpleType öğesini veya complexType öğesini döndürür. Bu, şema-derleme sonrası bir bilgi kümesi (infoset) değeridir. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | Bu şema tipinin temel tipi için derleme sonrası değeri döndürür. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | **block** özniteliğini döndürür. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | Tip, şema doğrulama sonrası bilgi kümesine (infoset) derlendikten sonra değeri döndürür. Bu değer, örnek belgede **xsi:type** kullanıldığında tipin nasıl zorlandığını gösterir. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | Bu karmaşık tipin derleme sonrası [XmlSchemaContentModel](../xmlschemacontentmodel/) değerini döndürür. |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | Derleme sonrası değeri tutan karmaşık tipin içerik modelini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | [XmlSchemaComplexType::get_ContentType](./get_contenttype/) parçacığının derleme sonrası değerini tutan parçacığı döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | Karmaşık tipin veri tipi için derleme sonrası değeri döndürür. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | Bu öğenin temel tipinden nasıl türetildiğine ilişkin derleme sonrası bilgiyi döndürür. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | Daha fazla türetmeye izin verilip verilmediğini gösteren tip türetmesinin final özniteliğini döndürür. |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | [XmlSchemaType::get_Final](../xmlschematype/get_final/) değerinin derleme sonrası yorumunu döndürür. |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | Dize kimliğini döndürür. |
| **bool** [get_IsAbstract](./get_isabstract/)() | **complexType** öğesinin örnek belgede kullanılıp kullanılamayacağını belirleyen bilgiyi döndürür. |
| **bool** [get_IsMixed](./get_ismixed/)() override | Karmaşık tipin karışık içerik modeline (içerikte işaretleme) sahip olup olmadığını belirleyen bilgiyi döndürür. |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | **schema** öğesinin işaret ettiği dosyadaki satır numarasını döndürür. |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | **schema** öğesinin işaret ettiği dosyadaki satır konumunu döndürür. |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | Tipin adını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | Bu şema nesnesiyle kullanılacak XmlSerializerNamespaces değerini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | Bu [XmlSchemaObject](../xmlschemaobject/)'nin ebeveynini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından biri olarak birleştirici tipini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | Bu tipin **Name** özniteliğinden oluşturulan tipin nitelikli adını döndürür. Bu, şema-derleme sonrası bir değerdir. |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | Şemayı yükleyen dosyanın kaynak konumunu döndürür. |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | Tipin XmlTypeCode değerini döndürür. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | Mevcut şemanın hedef ad alanına ait olmayan nitelikli öznitelikleri döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | Belirtilen karmaşık tipin yerleşik karmaşık tipini temsil eden bir [XmlSchemaComplexType](./) döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Nitelikli ad ile belirtilen karmaşık tipin yerleşik karmaşık tipini temsil eden bir [XmlSchemaComplexType](./) döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | Nitelikli ad ile belirtilen basit tipin yerleşik basit tipini temsil eden bir [XmlSchemaSimpleType](../xmlschemasimpletype/) döndürür. |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | Belirtilen basit tipin yerleşik basit tipini temsil eden bir [XmlSchemaSimpleType](../xmlschemasimpletype/) döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Belirtilen türetilmiş şema tipinin belirtilen temel şema tipinden türetilip türetilmediğini gösteren bir değer döndürür. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesi kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özelleştirilmiş tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcılarını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşımlı referans sayacını azaltır. |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | **annotation** özelliğini ayarlar. |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) bileşeninin karmaşık tip için değerini ayarlar. |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | **block** özniteliğini ayarlar. |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | Bu karmaşık tipin derleme sonrası [XmlSchemaContentModel](../xmlschemacontentmodel/) değerini ayarlar. |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | Daha fazla türetmeye izin verilip verilmediğini gösteren tip türetmesinin final özniteliğini ayarlar. |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | Dize kimliğini ayarlar. |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | **complexType** öğesinin örnek belgede kullanılıp kullanılamayacağını belirleyen bilgiyi ayarlar. |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | Karmaşık tipin karışık içerik modeline (içerikte işaretleme) sahip olup olmadığını belirleyen bilgiyi ayarlar. |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | **schema** öğesinin işaret ettiği dosyadaki satır numarasını ayarlar. |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | **schema** öğesinin işaret ettiği dosyadaki satır konumunu ayarlar. |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | Tipin adını ayarlar. |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | Bu şema nesnesiyle kullanılacak XmlSerializerNamespaces'ı ayarlar. |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | Bu [XmlSchemaObject](../xmlschemaobject/)'nin ebeveynini ayarlar. |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | Birleştirici tipini [XmlSchemaGroupRef](../xmlschemagroupref/), [XmlSchemaChoice](../xmlschemachoice/), [XmlSchemaAll](../xmlschemaall/) veya [XmlSchemaSequence](../xmlschemasequence/) sınıflarından biri olarak ayarlar. |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | Şemayı yükleyen dosyanın kaynak konumunu ayarlar. |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | Mevcut şemanın hedef ad alanına ait olmayan nitelikli öznitelikleri ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kaplarda işaretçileri zayıf moda geçişe izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özelleştirilmiş nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesi kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | [XmlSchemaComplexType](./) sınıfının yeni bir örneğini başlatır. |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | [XmlSchemaObject](../xmlschemaobject/) sınıfının yeni bir örneğini başlatır. |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | [XmlSchemaType](../xmlschematype/) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine yönelik paylaşımlı işaretçi takma adıdır. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini yığında veya operator new ile oluşturmaktan kaçının; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin. 

## Ayrıca Bakınız

* Sınıf [XmlSchemaType](../xmlschematype/)
* Ad Alanı [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)
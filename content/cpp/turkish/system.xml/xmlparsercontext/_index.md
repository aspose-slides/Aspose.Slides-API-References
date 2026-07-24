---
title: XmlParserContext
second_title: Aspose.Slides for C++ API Referansı
description: XmlReader tarafından bir XML parçacığını ayrıştırmak için gereken tüm bağlam bilgilerini sağlar.
type: docs
weight: 391
url: /tr/system.xml/xmlparsercontext/
---
## XmlParserContext sınıfı

Provides all the context information required by the [XmlReader](../xmlreader/) to parse an XML fragment.

```cpp
class XmlParserContext : public System::Object
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca iç amaçlar için. |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | Temel URI'yi döndürür. |
| [String](../../system/string/) [get_DocTypeName](./get_doctypename/)() | Belge türü bildirim adını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Kodlama tipini döndürür. |
| [String](../../system/string/) [get_InternalSubset](./get_internalsubset/)() | Dahili DTD alt kümesini döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\> [get_NamespaceManager](./get_namespacemanager/)() | [XmlNamespaceManager](../xmlnamespacemanager/)'yi döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | [XmlNameTable](../xmlnametable/)'yi döndürür. Atomize edilmiş dizeler hakkında daha fazla bilgi için [XmlNameTable](../xmlnametable/)'e bakın. |
| [String](../../system/string/) [get_PublicId](./get_publicid/)() | Kamu tanımlayıcısını döndürür. |
| [String](../../system/string/) [get_SystemId](./get_systemid/)() | Sistem tanımlayıcısını döndürür. |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Geçerli **xml:lang** kapsamını döndürür. |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | Geçerli **xml:space** kapsamını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumuna özel uyarlaması. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumuna özel uyarlaması. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_BaseURI](./set_baseuri/)(const [String](../../system/string/)\&) | Temel URI'yi ayarlar. |
| void [set_DocTypeName](./set_doctypename/)(const [String](../../system/string/)\&) | Belge türü bildirim adını ayarlar. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Kodlama tipini ayarlar. |
| void [set_InternalSubset](./set_internalsubset/)(const [String](../../system/string/)\&) | Dahili DTD alt kümesini ayarlar. |
| void [set_NamespaceManager](./set_namespacemanager/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | [XmlNamespaceManager](../xmlnamespacemanager/)'yi ayarlar. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Atomize edilmiş dizeleri oluşturmak için kullanılan [XmlNameTable](../xmlnametable/)'yi ayarlar. Atomize edilmiş dizeler hakkında daha fazla bilgi için [XmlNameTable](../xmlnametable/)'a bakın. |
| void [set_PublicId](./set_publicid/)(const [String](../../system/string/)\&) | Kamu tanımlayıcısını ayarlar. |
| void [set_SystemId](./set_systemid/)(const [String](../../system/string/)\&) | Sistem tanımlayıcısını ayarlar. |
| void [set_XmlLang](./set_xmllang/)(const [String](../../system/string/)\&) | Geçerli **xml:lang** kapsamını ayarlar. |
| void [set_XmlSpace](./set_xmlspace/)([System::Xml::XmlSpace](../xmlspace/)) | Geçerli **xml:space** kapsamını ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | [XmlParserContext](./) sınıfının belirtilen [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang** ve **xml:space** değerleriyle yeni bir örneğini başlatır. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | [XmlParserContext](./) sınıfının belirtilen [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), **xml:lang**, **xml:space** ve kodlama ile yeni bir örneğini başlatır. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/)) | [XmlParserContext](./) sınıfının belirtilen [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), temel URI, **xml:lang**, **xml:space** ve belge türü değerleriyle yeni bir örneğini başlatır. |
|  [XmlParserContext](./xmlparsercontext/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, [System::Xml::XmlSpace](../xmlspace/), const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | [XmlParserContext](./) sınıfının belirtilen [XmlNameTable](../xmlnametable/), [XmlNamespaceManager](../xmlnamespacemanager/), temel URI, **xml:lang**, **xml:space**, kodlama ve belge türü değerleriyle yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ait paylaşımlı işaretçi için bir takma addır. |

## Notlar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneklerini yığını üzerinde veya new operatörüyle oluşturmaktan kaçının; aksi takdirde çalışma zamanı hataları ve/veya iddia (assert) hataları meydana gelir. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

## Ayrıca Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
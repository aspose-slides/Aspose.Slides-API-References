---
title: XmlReaderSettings
second_title: Aspose.Slides for C++ API Referansı
description: "XmlReader::Create yöntemiyle oluşturulan XmlReader nesnesi üzerinde desteklenecek bir dizi özelliği belirtir."
type: docs
weight: 443
url: /tr/system.xml/xmlreadersettings/
---
## XmlReaderSettings sınıf


[XmlReader](../xmlreader/) nesnesi üzerinde [XmlReader::Create](../xmlreader/create/) yöntemi tarafından oluşturulan bir dizi özelliği desteklemek için belirtir.

```cpp
class XmlReaderSettings : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | [XmlReaderSettings](./) örneğinin bir kopyasını oluşturur. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre hiçbir değere, NaN dahil, eşit olmamakla birlikte eşit kabul edilir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN, IEC 60559:1989'a göre hiçbir değere, NaN dahil, eşit olmamakla birlikte eşit kabul edilir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Karakter denetimi yapılacak mı gösteren bir değer döndürür. |
| **bool** [get_CloseInput](./get_closeinput/)() | Okuyucu kapandığında temel akışın veya TextReader'ın kapatılıp kapatılmayacağını gösteren bir değer döndürür. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | [XmlReader](../xmlreader/)'nin uyacağı uyumluluk düzeyini döndürür. |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | DTD'lerin işlenmesini belirleyen bir değer döndürür. |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | Yorumların göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | İşlem talimatlarının göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | Önemsiz boşlukların göz ardı edilip edilmeyeceğini gösteren bir değer döndürür. |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | [XmlReader](../xmlreader/) nesnesinin satır numarası ofsetini döndürür. |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | [XmlReader](../xmlreader/) nesnesinin satır konumu ofsetini döndürür. |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | Varlıkları genişletmekten kaynaklanan bir belgede izin verilen maksimum karakter sayısını gösteren bir değer döndürür. |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | Bir XML belgesinde izin verilen maksimum karakter sayısını gösteren bir değer döndürür. Sıfır (0) değeri, XML belgesinin boyutu için limit olmadığını gösterir. Sıfır olmayan bir değer, maksimum boyutu karakter olarak belirtir. |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | Atomik string karşılaştırmaları için kullanılan [XmlNameTable](../xmlnametable/)'i döndürür. |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | Belge türü tanımı (DTD) işlenmesini yasaklayıp yasaklamayacağını gösteren bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | Şema doğrulaması yapılırken kullanılacak XmlSchemaSet'i döndürür. |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | Şema doğrulama ayarlarını gösteren bir değer döndürür. Bu ayar, şemaları doğrulayan [XmlReader](../xmlreader/) nesnelerine uygulanır ([XmlReaderSettings::get_ValidationType](./get_validationtype/) değeri [ValidationType::Schema](../validationtype/)'dur). |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | Okuma sırasında [XmlReader](../xmlreader/)'nin doğrulama veya tip ataması yapıp yapmayacağını gösteren bir değer döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağl ar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Referansla değer tipi nesnesini nullptr ile karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nın string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [Reset](./reset/)() | Ayar sınıfının üyelerini varsayılan değerlerine sıfırlar. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Karakter denetimi yapılacak mı gösteren bir değer ayarlar. |
| void [set_CloseInput](./set_closeinput/)(**bool**) | Okuyucu kapandığında temel akışın veya TextReader'ın kapatılıp kapatılmayacağını gösteren bir değer ayarlar. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | [XmlReader](../xmlreader/)'nin uyacağı uyumluluk düzeyini ayarlar. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | DTD'lerin işlenmesini belirleyen bir değer ayarlar. |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | Yorumların göz ardı edilip edilmeyeceğini gösteren bir değer ayarlar. |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | İşlem talimatlarının göz ardı edilip edilmeyeceğini gösteren bir değer ayarlar. |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | Önemsiz boşlukların göz ardı edilip edilmeyeceğini gösteren bir değer ayarlar. |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | [XmlReader](../xmlreader/) nesnesinin satır numarası ofsetini ayarlar. |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | [XmlReader](../xmlreader/) nesnesinin satır konumu ofsetini ayarlar. |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | Varlıkları genişletmekten kaynaklanan bir belgede izin verilen maksimum karakter sayısını gösteren bir değer ayarlar. |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | XML belgesinde izin verilen maksimum karakter sayısını gösteren bir değer ayarlar. Sıfır (0) değeri, XML belgesinin boyutu için limit olmadığını gösterir. Sıfır olmayan değer, maksimum boyutu karakter olarak belirtir. |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Atomik string karşılaştırmaları için kullanılan [XmlNameTable](../xmlnametable/)'yi ayarlar. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Belge türü tanımı (DTD) işlenmesini yasaklayıp yasaklamayacağını gösteren bir değer ayarlar. |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | Şema doğrulaması yapılırken kullanılacak XmlSchemaSet'i ayarlar. |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | Şema doğrulama ayarlarını gösteren bir değer ayarlar. Bu ayar, şemaları doğrulayan [XmlReader](../xmlreader/) nesnelerine uygulanır ([XmlReaderSettings::get_ValidationType](./get_validationtype/) değeri [ValidationType::Schema](../validationtype/)'dir). |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | Okuma sırasında [XmlReader](../xmlreader/)'nin doğrulama veya tip ataması yapıp yapmayacağını gösteren bir değer ayarlar. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Harici belgelere erişmek için kullanılan [XmlResolver](../xmlresolver/)'yi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını zayıf gösterici (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | Okuyucu doğrulama hatalarıyla karşılaştığında gerçekleşen bir olay işleyicisi ekler. |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | Okuyucu doğrulama hatalarıyla karşılaştığında gerçekleşen bir olay işleyicisini kaldırır. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
|  [XmlReaderSettings](./xmlreadersettings/)() | [XmlReaderSettings](./) sınıfının yeni bir örneğini başlatır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine ortak gösterici takma adıdır. |

## Açıklamalar

Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür örnekleri yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin.

## İlgili

* Sınıf [Object](../../system/object/)
* Ad Alanı [System::Xml](../)
* Kütüphane [Aspose.Slides](../../)
---
title: Details_XmlSchemaInferenceException
second_title: Aspose.Slides for C++ API Referansı
description: XmlSchemaInference sınıfının bir XML belgesinden şema çıkarma sırasında karşılaştığı hatalar hakkında bilgi döndürür.
type: docs
weight: 14
url: /tr/system.xml.schema/details_xmlschemainferenceexception/
---
## Details_XmlSchemaInferenceException sınıfı

[XmlSchemaInference](../xmlschemainference/) sınıfının bir XML belgesinden şema çıkarma sırasında karşılaştığı hatalar hakkında bilgi döndürür.

```cpp
class Details_XmlSchemaInferenceException : public System::Xml::Schema::Details_XmlSchemaException
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamakla birlikte, iki NaN'ın eşit kabul edildiği C# tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Özel istisna verileri içeren bir sözlüğü döndürür. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Geçerli nesne tarafından temsil edilen istisna ile ilişkilendirilen 32 bit bir tamsayı değeri (HRESULT kodu) döndürür. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | İç istisna nesnesini temsil eden bir referansı döndürür. |
| **int32_t** [get_LineNumber](../details_xmlschemaexception/get_linenumber/)() | Hatanın meydana geldiği satır numarasını döndürür. |
| **int32_t** [get_LinePosition](../details_xmlschemaexception/get_lineposition/)() | Hatanın meydana geldiği satır konumunu döndürür. |
| [String](../../system/string/) [get_Message](../details_xmlschemaexception/get_message/)() const override | Bu istisnanın hata durum açıklamasını döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_SourceSchemaObject](../details_xmlschemaexception/get_sourceschemaobject/)() | XmlSchemaException'ı oluşturan **[XmlSchemaObject](../xmlschemaobject/)**. |
| [String](../../system/string/) [get_SourceUri](../details_xmlschemaexception/get_sourceuri/)() | İstisna yaratmış şemanın Uniform Resource Identifier (URI) konumunu döndürür. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Yığın izini içeren dizeyi döndürür. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | En içteki istisna nesnesini temsil eden Exception nesnesinin bir kopyasını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini sağlar. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini gerçekleştirir. Direkt çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumları için özelleştirilmiş versiyonu. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumları için özelleştirilmiş versiyonu. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Belirli bir istisna için atanmış kodlanmış sayısal değer olan HRESULT'i ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını zayıf gösterici (shared yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Geçerli nesnenin dize temsili döndürür. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini kaldırmasını gerçekleştirir. Direkt çağırılabilir veya [LockContext](../../system/lockcontext/) gözcü nesnesi kullanılabilir. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual const char * [what](../../system/details_exception/what/)() const | [what()](../../system/details_exception/what/) metodunu uygular; bu metod [ExceptionWrapper](../../system/exceptionwrapper/) sınıfı tarafından çağrılır. Bu sınıf std::exception'tan türemese de türetilen sınıflar korumalı/özel üyeleri kullanabilir. Bu metodun uygulamasını [ExceptionWrapper](../../system/exceptionwrapper/)'a taşımak bu mantığı bozabilir. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [Ptr](./ptr/) | Bu sınıfın bir örneğine yönelik paylaşımlı işaretçi takma adıdır. |

## Ayrıca Bakınız

* Sınıf [Details_XmlSchemaException](../details_xmlschemaexception/)
* İsim Uzayı [System::Xml::Schema](../)
* Kütüphane [Aspose.Slides](../../)
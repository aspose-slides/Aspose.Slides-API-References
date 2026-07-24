---
title: HyperlinkQueries
second_title: Aspose.Slides C++ API Referansı
description: İçerilen hiperlinklere kolay erişim sağlar.
type: docs
weight: 1262
url: /tr/aspose.slides/hyperlinkqueries/
---
## HyperlinkQueries sınıfı

İçerilen hiperlinklere kolay erişim sağlar.

```cpp
class HyperlinkQueries : public Aspose::Slides::IHyperlinkQueries,
                         public Aspose::Slides::IDOMObject
```

## Metodlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipi nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer tipi nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN'nin herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'nin eşit kabul edildiği C# tarzı nokta sayısı karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN'nin herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'nin eşit kabul edildiği C# tarzı nokta sayısı karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetAnyHyperlinks](./getanyhyperlinks/)() override | null olmayan HyperlinkMouseOver içeren tüm [IHyperlinkContainer](../ihyperlinkcontainer/) alt nesnelerini alır. Verilen [IHyperlinkContainer](../ihyperlinkcontainer/) nesnesiyle hiperlinki (okuma, güncelleme veya kaldırma) yönetebilirsiniz. Bkz. [IHyperlinkContainer](../ihyperlinkcontainer/) arayüz. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hashlenmesini etkinleştirir. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetHyperlinkClicks](./gethyperlinkclicks/)() override | null olmayan HyperlinkClick içeren tüm [IHyperlinkContainer](../ihyperlinkcontainer/) alt nesnelerini alır. Verilen [IHyperlinkContainer](../ihyperlinkcontainer/) nesnesiyle hiperlinki (okuma, güncelleme veya kaldırma) yönetebilirsiniz. Bkz. [IHyperlinkContainer](../ihyperlinkcontainer/) arayüz. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IList](../../system.collections.generic/ilist/)\<[System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkContainer](../ihyperlinkcontainer/)\>\>\> [GetHyperlinkMouseOvers](./gethyperlinkmouseovers/)() override | null olmayan HyperlinkMouseOver içeren tüm [IHyperlinkContainer](../ihyperlinkcontainer/) alt nesnelerini alır. Verilen [IHyperlinkContainer](../ihyperlinkcontainer/) nesnesiyle hiperlinki (okuma, güncelleme veya kaldırma) yönetebilirsiniz. Bkz. [IHyperlinkContainer](../ihyperlinkcontainer/) arayüz. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını etkinleştirir. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş bir sürümü. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş bir sürümü. |
| void [RemoveAllHyperlinks](./removeallhyperlinks/)() override | Tüm [IHyperlinkContainer](../ihyperlinkcontainer/) alt nesnelerindeki içeriği HyperlinkClick ve HyperlinkMouseOver hiperlinklerini kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar paylaşılan referans sayacını azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını (paylaşılan yerine) zayıf bir gösterici olarak ayarlar. Kapsayıcılardaki göstergelerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin stringe dönüştürülmesini etkinleştirir. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [IHyperlinkQueries](../ihyperlinkqueries/)
* Sınıf [IDOMObject](../idomobject/)
* İsim Alanı [Aspose::Slides](../)
* Kütüphane [Aspose.Slides](../../)
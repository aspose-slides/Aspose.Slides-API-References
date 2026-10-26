---
title: Object
second_title: Aspose.Slides for C++ API Referansı
description: C# içinde System.Object sınıfı için mevcut yöntemlerin kullanılmasını sağlayan temel sınıf. Çevrilen ortamda kullanılan tüm basit olmayan sınıflar bundan türemelidir.
type: docs
weight: 1132
url: /tr/system/object/
---
## Object sınıfı

Base class that enables using methods available for [System.Object](./) class in C#. All non-trivial classes used with translated environment should inherit it.

```cpp
class Object
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual **bool** [Equals](./equals/)([ptr](./ptr/)) | C# [Object.Equals](./equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](./equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesnelerini karşılaştırır. |
| static **bool** [Equals](./equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](./equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](./fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| Detail::SmartPtrCounter * [GetCounter](./getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](./gethashcode/)() const | C# [Object.GetHashCode()](./gethashcode/) yönteminin analogudur. Özel nesnelerin karmalanmasını sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](./gettype/) çağrısının analogudur. |
| virtual **bool** [Is](./is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](./lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](./ptr/) [MemberwiseClone](./memberwiseclone/)() const | C# [Object.MemberwiseClone()](./memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
| [Object](./object/)() | Nesneyi oluşturur. Tüm iç veri yapılarını başlatır. |
| [Object](./object/)([Object](./) const\&) | Kopya oluşturucu. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](./)\& [operator=](./operator_equal/)([Object](./) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](./referenceequals/)([ptr](./ptr/) const\&, [ptr](./ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](./referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](./referenceequals/)'un string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](./referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](./referenceequals/)'in string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](./removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçişe izin verir. |
| int [SharedCount](./sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](./) * [SharedRefAdded](./sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](./sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../string/) [ToString](./tostring/)() const | C# [Object.ToString()](./tostring/) yönteminin analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | C# typeof([System.Object](./)) yapısını uygular. |
| void [Unlock](./unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](./weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](./weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](./~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Typedef'ler

| Typedef | Açıklama |
| --- | --- |
| [ptr](./ptr/) | Akıllı gösterici türü için takma addır. |

## Açıklamalar

C# [System.Object](./) sınıfında mevcut yöntemlerin yanı sıra, çevrilen kod ortamına özgü bazı kavramları da destekler. Bu, akıllı gösterici sınıfları ([System::SmartPtr](../smartptr/), [System::WeakPtr](../weakptr/), [System::DynamicWeakPtr](../dynamicweakptr/)) tarafından kullanılan referans sayımını ve bellek yönetimi, hata ayıklama vb. ile ilgili diğer hizmetleri içerir.

Her [Object](./) iki referans sayacına sahiptir: paylaşılan referans sayacı ve zayıf referans sayacı. Zayıf referans sayacı, [Object](./) içinde olmak yerine her zaman ayrı bir veri yapısında saklanır; bu, zayıf göstericilerin referans verilen nesnenin ömrünü uzatmasına izin verir. Akıllı referans sayacı, ENABLE_EXTERNAL_REFCOUNT makrosunun durumuna bağlı olarak ya nesnenin içinde ya da aynı ayrı veri yapısında saklanır. Varsayılan olarak, debug derlemelerinde etkin, release derlemelerinde devredışı bırakılır. Akıllı gösterici sayacı nesnenin içinde saklanıyorsa, zayıf göstericiler mevcut olduğunda yalnızca ayrı veri yapısı oluşturulur. Aksi takdirde, nesneyle birlikte oluşturulur.

Tüm akıllı göstericiler bu iki referans sayacını kullanır ve aynı tek mülkiyet grubuna katkıda bulunur.

[Object](./) alt sınıfı yığında oluşturulursa, ona yönelik akıllı göstericiler oluşturulamaz, aksi takdirde yığından silme sorunu oluşur.

Bu tip, değer türü olarak yığında ya da [System::MakeObject()](../makeobject/) işleviyle yığında (heap) tahsis edilebilir. Nesne tahsis edildikten sonra, bu iki kullanım senaryosunu asla karıştırmayın: [SmartPtr](../smartptr/) göstericilerinin yığında tahsis edilen nesnelere işaret etmesi kesinlikle yasaktır.

## İlgili

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)
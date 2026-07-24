---
title: HttpRequestCachePolicy
second_title: Aspose.Slides for C++ API Referansı
description: "RFC2616 HTTP önbellekleme semantiğini ifade eden HTTP önbellek politikası. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini yığına veya new operatörüyle yaratmayın; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 1
url: /tr/system.net.cache/httprequestcachepolicy/
---
## HttpRequestCachePolicy sınıfı

HTTP cache policy that expresses RFC2616 HTTP caching semantic Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class HttpRequestCachePolicy : public System::Net::Cache::RequestCachePolicy
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiklerini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesnelerini karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesnelerini karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [DateTime](../../system/datetime/) [get_CacheSyncDate](./get_cachesyncdate/)() const | Önbellekte saklanan kaynakların yeniden doğrulanması gereken zamanı alır. |
| [DateTime](../../system/datetime/) [get_InternalCacheSyncDateUtc](./get_internalcachesyncdateutc/)() const | Önbellekte saklanan kaynakların yeniden doğrulanması gereken zamanı UTC formatında alır. Yalnızca dahili kullanım için. |
| [HttpRequestCacheLevel](../httprequestcachelevel/) [get_Level](./get_level/)() const | Belirtilen HttpRequestCacheLevel değerini alır. |
| [RequestCacheLevel](../requestcachelevel/) [get_Level](../requestcachepolicy/get_level/)() | Belirtilen RequestCacheLevel değerini alır. |
| [TimeSpan](../../system/timespan/) [get_MaxAge](./get_maxage/)() const | Bir kaynak için izin verilen maksimum yaşı alır. |
| [TimeSpan](../../system/timespan/) [get_MaxStale](./get_maxstale/)() const | Bir kaynak için izin verilen maksimum bayatlık değerini alır. |
| [TimeSpan](../../system/timespan/) [get_MinFresh](./get_minfresh/)() const | Bir kaynak için izin verilen minimum yaşı alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeri. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)() | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpRequestCacheLevel](../httprequestcachelevel/)) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/)) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/)) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([DateTime](../../system/datetime/)) | Yeni bir örnek oluşturur. |
| [HttpRequestCachePolicy](./httprequestcachepolicy/)([HttpCacheAgeControl](../httpcacheagecontrol/), [TimeSpan](../../system/timespan/), [TimeSpan](../../system/timespan/), [DateTime](../../system/datetime/)) | Yeni bir örnek oluşturur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipte bir örnek olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeri. Özel tiplerin çoğaltılmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Stringler durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Belirtilen değer kadar ortak referans sayacını azaltır. |
| [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)() | Yeni bir örnek oluşturur. |
| [RequestCachePolicy](../requestcachepolicy/requestcachepolicy/)([RequestCacheLevel](../requestcachelevel/)) | Belirtilen RequestCacheLevel değeriyle yeni bir örnek oluşturur. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ortak referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Ortak referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Ortak referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeri. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [RequestCachePolicy](../requestcachepolicy/)
* Ad Alanı [System::Net::Cache](../)
* Kütüphane [Aspose.Slides](../../)
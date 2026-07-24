---
title: CacheControlHeaderValue
second_title: Aspose.Slides for C++ API Referansı
description: "‘Cache-Control’ başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 14
url: /tr/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue sınıfı


Cache-Control başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıt üzerinde veya operator new ile oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Yeni bir örnek oluşturur. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) semantiğini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# stilinde referans tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Önbellek uzantı belirteçlerinin koleksiyonunu döndürür. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | İstemcinin bir yanıtı kabul edeceği süreyi belirleyen, saniye cinsinden maksimum yaş değerini alır. |
| **bool** [get_MaxStale](./get_maxstale/)() | İstemcinin süresi dolmuş yanıtları kabul edip etmeyeceğini belirleyen değeri alır. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | İstemcinin süresi dolmuş yanıtları kabul edeceği süreyi saniye olarak belirleyen değeri alır. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Tazelik süresini belirleyen değeri alır. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Sunucunun bir önbellek girdisi bayatlandığında yeniden doğrulama gerekip gerekmeyeceğini belirleyen değeri alır. |
| **bool** [get_NoCache](./get_nocache/)() | İstemcinin önbelleğe alınmış bir yanıtı kabul edip etmeyeceğini belirleyen değeri alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | 'Cache-Control' başlığındaki 'no-cache' yönergesindeki alan adlarının koleksiyonunu alır. |
| **bool** [get_NoStore](./get_nostore/)() | Bir önbelleğin HTTP isteğinin veya yanıtının herhangi bir kısmını saklamaması gerektiğini belirleyen değeri alır. |
| **bool** [get_NoTransform](./get_notransform/)() | Bir önbellek ya da proxy'nin varlık gövdesinin herhangi bir kısmını değiştirmemesi gerektiğini belirleyen değeri alır. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | İstemcinin yalnızca önbellek girdilerini kullanması gerektiğini belirleyen değeri alır. |
| **bool** [get_Private](./get_private/)() | HTTP yanıt mesajının veya bir parçasının tek bir kullanıcı için tasarlandığını ve paylaşımlı önbellek tarafından önbelleğe alınmaması gerektiğini belirleyen değeri alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | 'Cache-Control' başlığındaki 'private' yönergesindeki alan adlarının koleksiyonunu alır. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Sunucunun paylaşımlı kullanıcı aracısı önbellekleri için bir önbellek girdisi bayatlandığında yeniden doğrulama gerekip gerekmeyeceğini belirleyen değeri alır. |
| **bool** [get_Public](./get_public/)() | Bir HTTP yanıtının herhangi bir önbellek tarafından önbelleğe alınabilip alınamayacağını belirleyen değeri alır. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Paylaşımlı önbellek için 'max-age' yönergesini veya 'Expires' başlığını geçersiz kılan, saniye cinsinden ortak maksimum yaş değerini alır. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Belirtilen indisten başlayan verilen dizeyi [CacheControlHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin bir analoğudur. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapısını etkinleştirir. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Verilen dizgeyi [CacheControlHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | İstemcinin bir yanıtı kabul edeceği süreyi belirleyen, saniye cinsinden maksimum yaş değerini ayarlar. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | İstemcinin süresi dolmuş yanıtları kabul edip etmeyeceğini belirleyen değeri ayarlar. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | İstemcinin süresi dolmuş yanıtları kabul edeceği süreyi saniye olarak belirleyen değeri ayarlar. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Tazelik süresini belirleyen değeri ayarlar. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Sunucunun bir önbellek girdisi bayatlandığında yeniden doğrulama gerekip gerekmeyeceğini belirleyen değeri ayarlar. |
| void [set_NoCache](./set_nocache/)(**bool**) | İstemcinin önbelleğe alınmış yanıtı kabul edip etmeyeceğini belirleyen değeri ayarlar. |
| void [set_NoStore](./set_nostore/)(**bool**) | Bir önbelleğin HTTP isteğinin veya yanıtının bir kısmını saklamaması gerektiğini belirleyen değeri ayarlar. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Bir önbellek veya proxy'nin varlık gövdesinin bir kısmını değiştirmemesi gerektiğini belirleyen değeri ayarlar. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | İstemcinin yalnızca önbellek girdilerini kullanması gerektiğini belirleyen değeri ayarlar. |
| void [set_Private](./set_private/)(**bool**) | HTTP yanıt mesajının veya bir parçasının tek bir kullanıcı için tasarlandığını ve paylaşımlı önbellek tarafından önbelleğe alınmaması gerektiğini belirleyen değeri ayarlar. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Sunucunun paylaşımlı kullanıcı aracısı önbellekleri için bir önbellek girdisi bayatlandığında yeniden doğrulama gerekip gerekmeyeceğini belirleyen değeri ayarlar. |
| void [set_Public](./set_public/)(**bool**) | Bir HTTP yanıtının herhangi bir önbellek tarafından önbelleğe alınabileceğini belirleyen değeri ayarlar. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Paylaşımlı önbellek için 'max-age' yönergesini veya 'Expires' başlığını geçersiz kılan, saniye cinsinden ortak maksimum yaş değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçiye (paylaşımlı yerine) ayarlar. Kapsayıcı içindeki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Verilen dizgeyi [CacheControlHeaderValue](./) sınıfının bir örneğine dönüştürmeyi dener. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## See Also

* Sınıf [ICloneable](../../system/icloneable/)
* Namespace [System::Net::Http::Headers](../)
* Library [Aspose.Slides](../../)
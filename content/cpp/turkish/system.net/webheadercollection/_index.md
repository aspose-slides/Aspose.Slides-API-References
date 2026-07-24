---
title: WebHeaderCollection
second_title: Aspose.Slides için C++ API Referansı
description: "Protokol başlıklarının koleksiyonunu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt (stack) üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin."
type: docs
weight: 482
url: /tr/system.net/webheadercollection/
---
## WebHeaderCollection sınıfı

Protokol başlıklarının koleksiyonunu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek asla yığıt (stack) üzerinde ya da new operatörüyle oluşturulmamalıdır, çünkü çalışma zamanı hataları ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisi içine alın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class WebHeaderCollection : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen başlık adı ve başlık değeri çiftini koleksiyona ekler. |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Belirtilen başlık ve başlık değeri çiftini koleksiyona ekler. |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Belirtilen başlık ve başlık değeri çiftini koleksiyona ekler. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | Koleksiyonda depolanan başlık adlarının bir koleksiyonunu döndürür. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989’a göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen iki NaN’ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| **int32_t** [get_Count](./get_count/)() const | Koleksiyondaki öge sayısını döndürür. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | Koleksiyonda depolanan başlık adlarının bir koleksiyonunu döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| [String](../../system/string/) [GetKey](./getkey/)(int) | Belirtilen indeksteki anahtarı döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | Başlık değerlerinin bir koleksiyonunu döndürür. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | Belirtilen isteğin başlığını kullanarak başlık değerini alır. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | Belirtilen cevabın başlığını kullanarak başlık değerini alır. |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Belirtilen başlık adını kullanarak başlık değerini alır. |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Belirtilen başlığın değerini ayarlar. |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Belirtilen cevabın başlığını kullanarak başlık değerini ayarlar. |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen başlık adını kullanarak başlık değerini ayarlar. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeri. |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | Belirtilen HTTP başlığının istek için ayarlanıp ayarlanamayacağını test eder. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans üzerinden karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'un dize durumları için özelleştirilmiş hali. |
| void [Remove](./remove/)([String](../../system/string/)) | Belirtilen başlık adını kullanarak başlığı kaldırır. |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | Belirtilen cevabın başlığını kaldırır. |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | Belirtilen isteğin başlığını kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | Belirtilen başlığın değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özel nesnelerin stringe dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) ifadesini uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [WebHeaderCollection](./webheadercollection/)() | Yeni bir örnek oluşturur. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Bakınız

* Sınıf [Object](../../system/object/)
* Ad alanı [System::Net](../)
* Kütüphane [Aspose.Slides](../../)
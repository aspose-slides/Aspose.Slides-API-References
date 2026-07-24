---
title: RNGCryptoServiceProvider
second_title: Aspose.Slides for C++ API Referansı
description: "CSP kavramını izleyen rastgele sayı üreteci. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu türün örneğini asla yığında veya operator new kullanarak oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 443
url: /tr/system.security.cryptography/rngcryptoserviceprovider/
---
## RNGCryptoServiceProvider sınıfı

CSP kavramını izleyen rastgele sayı üreteci. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu türün örneğini asla yığında veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın.

```cpp
class RNGCryptoServiceProvider : public System::Security::Cryptography::RandomNumberGenerator
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static [System::SharedPtr](../../system/sharedptr/)\<[RandomNumberGenerator](../randomnumbergenerator/)\> [Create](../randomnumbergenerator/create/)() | Rastgele veri üretmek için kullanılabilecek kriptografik rastgele sayı üreteci'nin varsayılan uygulamasının bir örneğini oluşturur. Uygulanmadı. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) mantığıyla karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Mevcut dizi elemanlarını rastgele baytlarla doldurur. |
| void [GetBytes](./getbytes/)(System::Details::ArrayView\<**uint8_t**\>) override | Mevcut dizi görünümü elemanlarını rastgele baytlarla doldurur. |
| virtual void [GetBytes](../randomnumbergenerator/getbytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Mevcut dizi dilimini rastgele baytlarla doldurur. |
| virtual void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::ArrayView\<**uint8_t**\>, int, int) | Mevcut dizi görünümü dilimini rastgele baytlarla doldurur. |
| void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Mevcut yığın dizisi elemanlarını rastgele baytlarla doldurur. |
| void [GetBytes](../randomnumbergenerator/getbytes/)(System::Details::StackArray\<**uint8_t**, N\>\&, int, int) | Mevcut yığın dizi dilimini rastgele baytlarla doldurur. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin karma (hash) oluşturmasını sağlar. |
| void [GetNonZeroBytes](./getnonzerobytes/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | Mevcut dizi elemanlarını sıfır olmayan rastgele baytlarla doldurur. |
| void [GetNonZeroBytes](./getnonzerobytes/)(System::Details::ArrayView\<**uint8_t**\>) override | Mevcut dizi görünümü elemanlarını sıfır olmayan rastgele baytlarla doldurur. |
| void [GetNonZeroBytes](../randomnumbergenerator/getnonzerobytes/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Mevcut yığın dizisi elemanlarını sıfır olmayan rastgele baytlarla doldurur. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcı güdülmesini sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcı güdülmesini sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
|  [RNGCryptoServiceProvider](./rngcryptoserviceprovider/)() | Yapıcı. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmayı sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analogudur. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~RNGCryptoServiceProvider](./~rngcryptoserviceprovider/)() | Yıkıcı. |
## Ayrıca Bakınız

* Sınıf [RandomNumberGenerator](../randomnumbergenerator/)
* Ad alanı [System::Security::Cryptography](../)
* Kütüphane [Aspose.Slides](../../)
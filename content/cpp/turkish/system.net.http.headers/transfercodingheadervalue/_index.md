---
title: TransferCodingHeaderValue
second_title: Aspose.Slides for C++ API Referansı
description: "'Accept-Encoding' başlığının bir değerini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin bir örneğini yığıt (stack) üzerinde veya new operatörüyle oluşturmaya çalışmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 300
url: /tr/system.net.http.headers/transfercodingheadervalue/
---
## TransferCodingHeaderValue sınıfı

‘Accept-Encoding’ başlığının değerini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin bir örneğini yığını üzerinde veya new operatörüyle oluşturmaya çalışmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class TransferCodingHeaderValue : public virtual System::ICloneable
```

## Yöntemler

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans tipindeki nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Parametreleri döndürür. |
| [String](../../system/string/) [get_Value](./get_value/)() | Bir değer döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analogudur. Özel nesnelerin hashlenmesini sağlar. |
| static **int32_t** [GetTransferCodingLength](./gettransfercodinglength/)([String](../../system/string/), **int32_t**, const [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](./)\>\>\&, [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](./)\>\&) | Belirtilen indeksden itibaren verilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm iç veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcısını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapıcısını etkinleştirir. |
| static [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Verilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize ve nullptr durumları için özelleştirilmiş hâlidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) öğesinin dize durumları için özelleştirilmiş hâlidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](./tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) yönteminin analogudur. Özel nesnelerin stringe dönüştürülmesini sağlar. |
|  [TransferCodingHeaderValue](./transfercodingheadervalue/)() | Yeni bir örnek oluşturur. |
|  [TransferCodingHeaderValue](./transfercodingheadervalue/)([String](../../system/string/)) | Yeni bir örnek oluşturur. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[TransferCodingHeaderValue](./)\>\&) | Verilen bir dizeyi [TransferCodingHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm iç veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [ICloneable](../../system/icloneable/)
* Ad alanı [System::Net::Http::Headers](../)
* Kütüphane [Aspose.Slides](../../)
---
title: MediaTypeWithQualityHeaderValue
second_title: Aspose.Slides for C++ API Referansı
description: "'Content-Type' başlığının değerinde ek bir kalite faktörü bulunan bir MIME tipini temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin bir örneğini yığının (stack) üzerinde veya new operatörüyle oluşturmayın; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisiyle sarın ve bu işaretçiyi işlevlere argüman olarak geçirmek için kullanın."
type: docs
weight: 157
url: /tr/system.net.http.headers/mediatypewithqualityheadervalue/
---
## MediaTypeWithQualityHeaderValue sınıfı


Bir 'Content-Type' başlığının değerinde ek bir kalite faktörü bulunan bir MIME tipini temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Yığını (stack) üzerinden veya new operatörüyle örnek yaratmayın; bu, çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi işlevlere argüman olarak geçirin.

```cpp
class MediaTypeWithQualityHeaderValue : public System::Net::Http::Headers::MediaTypeHeaderValue
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| **bool** [Equals](../mediatypeheadervalue/equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit değildir, NaN dahil, ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit değildir, NaN dahil, ancak iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Sadece dahili amaçlar için. |
| [String](../../system/string/) [get_CharSet](../mediatypeheadervalue/get_charset/)() | Bir karakter kümesi alır. |
| [String](../../system/string/) [get_MediaType](../mediatypeheadervalue/get_mediatype/)() | Medya türü başlığının değerini alır. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](../mediatypeheadervalue/get_parameters/)() | Medya türü başlığının değer parametrelerini döndürür. |
| [Nullable](../../system/nullable/)\<**double**\> [get_Quality](./get_quality/)() | Kalite değerini alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| **int32_t** [GetHashCode](../mediatypeheadervalue/gethashcode/)() const override | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogu. Özel nesnelerin hash'lenmesini sağlar. |
| static **int32_t** [GetMediaTypeLength](../mediatypeheadervalue/getmediatypelength/)([String](../../system/string/), **int32_t**, [HeaderFunc](../headerfunc/)\<[System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\>, [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | Belirtilen indexten geçen bir dizeyi [MediaTypeHeaderValue](../mediatypeheadervalue/) sınıfının bir örneğine dönüştürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)() | Yeni bir örnek oluşturur. |
| [MediaTypeHeaderValue](../mediatypeheadervalue/mediatypeheadervalue/)([String](../../system/string/)) | Yeni bir örnek oluşturur. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)() | Yeni bir örnek oluşturur. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/)) | Yeni bir örnek oluşturur. |
| [MediaTypeWithQualityHeaderValue](./mediatypewithqualityheadervalue/)([String](../../system/string/), **double**) | Yeni bir örnek oluşturur. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogu. Özel tiplerin klonlanmasını sağlar. |
| [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucusu. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmalarını sağlar. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Geçilen bir dizeyi [MediaTypeWithQualityHeaderValue](./) sınıfının bir örneğine dönüştürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize durumu için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| void [set_CharSet](../mediatypeheadervalue/set_charset/)([String](../../system/string/)) | Bir karakter kümesi ayarlar. |
| void [set_MediaType](../mediatypeheadervalue/set_mediatype/)([String](../../system/string/)) | Medya türü başlığının değerini ayarlar. |
| void [set_Quality](./set_quality/)([Nullable](../../system/nullable/)\<**double**\>) | Kalite değerini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçiş yapmaya izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| [String](../../system/string/) [ToString](../mediatypeheadervalue/tostring/)() const override | C# [Object.ToString()](../../system/object/tostring/) metodunun analogu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeWithQualityHeaderValue](./)\>\&) | Geçilen bir dizeyi [MediaTypeWithQualityHeaderValue](./) sınıfının bir örneğine dönüştürmeye çalışır. |
| static **bool** [TryParse](../mediatypeheadervalue/tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[MediaTypeHeaderValue](../mediatypeheadervalue/)\>\&) | Geçilen bir dizeyi [MediaTypeHeaderValue](../mediatypeheadervalue/) sınıfının bir örneğine dönüştürmeye çalışır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilidini açar. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) koruyucu nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## İlgili

* Sınıf [MediaTypeHeaderValue](../mediatypeheadervalue/)
* Ad alanı [System::Net::Http::Headers](../)
* Kütüphane [Aspose.Slides](../../)
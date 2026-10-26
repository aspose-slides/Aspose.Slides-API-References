---
title: StreamReader
second_title: Aspose.Slides for C++ API Referansı
description: "Bu sınıf, bayt akışından karakterler okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneklemeyi yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 378
url: /tr/system.io/streamreader/
---
## StreamReader sınıfı

Bayt akışından karakterler okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneklemeyi yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class StreamReader : public System::IO::TextReader
```

## Yöntemler

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | Mevcut ve temel akışları kapatır. |
| virtual void [Dispose](./dispose/)(**bool**) | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| void [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği ile karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesnelerini C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesnelerini C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit olarak kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit olarak kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Temel akışı temsil eden bir nesneye ortak bir işaretçi döndürür. |
| [EncodingPtr](../../system/encodingptr/) [get_CurrentEncoding](./get_currentencoding/)() | Şu anda kullanılan kodlamayı döndürür. |
| **bool** [get_EndOfStream](./get_endofstream/)() | Akışın sonuna ulaşılıp ulaşılmadığını gösteren bir değer döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını denetler. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, yalnızca yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| int [Peek](./peek/)() override | Akışın okuma imlecini değiştirmeden akıştan tek bir karakter okur. |
| int [Read](./read/)() override | Akıştan tek bir karakter okur. |
| int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) override | Belirtilen sayıda karakteri akıştan okur, UTF-16 kodlamasına dönüştürür ve oluşan UTF-16 karakterlerini belirtilen konumdan başlayarak belirtilen karakter dizisine yazar. |
| virtual int [ReadBlock](../textreader/readblock/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Geçerli metin okuyucudan belirtilen azami sayıda karakter okur ve veriyi belirtilen indeksten başlayarak bir tampon'a yazar. |
| [String](../../system/string/) [ReadLine](./readline/)() override | Akışı, geçerli satırın sonuna kadar karakterlerle okur. |
| [String](../../system/string/) [ReadToEnd](./readtoend/)() override | Akışı, akışın sonuna kadar karakterlerle okur. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf bir işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçirmeyi sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının güncel değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen temel akıştan UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, **bool**) | Belirtilen temel akıştan UTF-8 kodlaması ve varsayılan 1024 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 1024 bayt boyutundaki bir tamponu kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
|  [StreamReader](./streamreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Belirtilen temel akıştan belirtilen kodlamayı ve belirtilen boyuttaki bir tamponu kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&) | Belirtilen dosyadan UTF-8 kodlaması ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, **bool**) | Belirtilen dosyadan UTF-8 kodlaması ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen dosyadan belirtilen kodlamayı ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Belirtilen temel akıştan belirtilen kodlamayı ve varsayılan 4096 bayt boyutundaki bir tampon kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
|  [StreamReader](./streamreader/)(const [System::String](../../system/string/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**, int) | Belirtilen dosyadan belirtilen kodlamayı ve belirtilen boyuttaki bir tamponu kullanarak karakter okuyan [StreamReader](./) nesnesinin bir örneğini oluşturur. Bir parametre bayt sırası işaretçisi tespiti etkinleştirilip edilmeyeceğini belirler. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit çözmesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) bekçi nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |
|  [~StreamReader](./~streamreader/)() | Yıkıcı. |

## Ayrıca bakınız

* Sınıf [TextReader](../textreader/)
* İsim uzayı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
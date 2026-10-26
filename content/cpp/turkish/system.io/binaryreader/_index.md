---
title: BinaryReader
second_title: Aspose.Slides için C++ API Referansı
description: "Belirli bir kodlamada ilkel veri tiplerini ikili veri olarak okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıtta veya new operatörüyle oluşturmamalısınız, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 92
url: /tr/system.io/binaryreader/
---
## BinaryReader sınıfı

Belirli bir kodlamada ilkel veri tiplerini ikili veri olarak okuyan bir okuyucuyu temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak tahsis edilmelidir. Bu tipin örneğini yığıtta veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class BinaryReader : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen akıştan UTF-8 kodlamasını kullanarak veri okuyan [BinaryReader](./) sınıfının bir örneğini oluşturur. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | Belirtilen akıştan belirtilen kodlamayı kullanarak veri okuyan [BinaryReader](./) sınıfının bir örneğini oluşturur. |
|  [BinaryReader](./binaryreader/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&, **bool**) | Belirtilen akıştan belirtilen kodlamayı kullanarak veri okuyan [BinaryReader](./) sınıfının bir örneğini oluşturur. |
| virtual void [Close](./close/)() | Mevcut [BinaryReader](./) nesnesini ve altındaki giriş akışını kapatır. |
| void [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve alt akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# biçiminde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# biçiminde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 standardına göre NaN hiçbir değere eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C#-style kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() | Giriş akışını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analoğu. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe ait bir örnek olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analoğu. Özel tiplerin klonlanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapıları başlatılır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını etkinleştirir. |
| virtual int [PeekChar](./peekchar/)() | Giriş akışından akışın okuma imlecini değiştirmeden tek bir karakter okur. |
| virtual int [Read](./read/)() | Giriş akışından tek bir karakter okur. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Giriş akışından belirtilen sayıda baytı okur ve belirtilen bayt dizisine yazar. |
| virtual int [Read](./read/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Giriş akışından belirtilen sayıda karakteri okur, UTF-16 kodlamasına dönüştürür ve elde edilen UTF-16 karakterleri belirtilen konumdan başlayarak belirtilen karakter dizisine yazar. |
| virtual **bool** [ReadBoolean](./readboolean/)() | Giriş akışından tek bir baytı okur ve onun boolean temsilini döndürür. |
| virtual **uint8_t** [ReadByte](./readbyte/)() | Giriş akışından tek bir bayt okur. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ReadBytes](./readbytes/)(int) | Giriş akışından belirtilen sayıda baytı okur. |
| virtual char_t [ReadChar](./readchar/)() | Giriş akışından tek bir karakter okur. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [ReadChars](./readchars/)(int) | Giriş akışından belirtilen sayıda karakteri okur ve UTF-16 kodlamasında döndürür. |
| virtual [Decimal](../../system/decimal/) [ReadDecimal](./readdecimal/)() | UYGULANMADI. |
| virtual **double** [ReadDouble](./readdouble/)() | Giriş akışından 8 bayt okur ve bunları çift duyarlıklı kayan nokta değeri olarak döndürür. |
| virtual **int16_t** [ReadInt16](./readint16/)() | Giriş akışından 2 bayt okur ve bunları 16 bitlik tam sayı değeri olarak döndürür. |
| virtual int [ReadInt32](./readint32/)() | Giriş akışından 4 bayt okur ve bunları 32 bitlik tam sayı değeri olarak döndürür. |
| virtual **int64_t** [ReadInt64](./readint64/)() | Giriş akışından 8 bayt okur ve bunları 64 bitlik tam sayı değeri olarak döndürür. |
| virtual **int8_t** [ReadSByte](./readsbyte/)() | Giriş akışından tek bir bayt okur ve bunu işaretli 8 bitlik tam sayı değeri olarak döndürür. |
| virtual **float** [ReadSingle](./readsingle/)() | Giriş akışından 4 bayt okur ve bunları tek duyarlıklı kayan nokta değeri olarak döndürür. |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | Mevcut akıştan bir dize okur. Dize, uzunluk ön ekine sahiptir ve bu uzunluk, her seferinde yedi bitlik bir tam sayı olarak kodlanır. |
| virtual **uint16_t** [ReadUInt16](./readuint16/)() | Giriş akışından 2 bayt okur ve bunları işaretsiz 16 bitlik tam sayı değeri olarak döndürür. |
| virtual **uint32_t** [ReadUInt32](./readuint32/)() | Giriş akışından 4 bayt okur ve bunları işaretsiz 32 bitlik tam sayı değeri olarak döndürür. |
| virtual **uint64_t** [ReadUInt64](./readuint64/)() | Giriş akışından 8 bayt okur ve bunları işaretsiz 64 bitlik tam sayı değeri olarak döndürür. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericileri zayıf moda geçirmeye olanak tanır. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~BinaryReader](./~binaryreader/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapıları serbest bırakılır. |

## Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* İsim Uzayı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
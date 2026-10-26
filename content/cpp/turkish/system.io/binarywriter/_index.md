---
title: BinaryWriter
second_title: Aspose.Slides for C++ API Referansı
description: "Primitif tip değerlerini bir bayt akışına yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek hiçbir zaman yığıt üzerinde veya new operatörüyle oluşturulmamalıdır; aksi takdirde çalışma zamanı hataları ve/veya doğrulama hataları ortaya çıkar. Bu sınıfı her zaman System::SmartPtr göstericisine sarın ve bu göstericiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 105
url: /tr/system.io/binarywriter/
---
## BinaryWriter sınıfı

Primitive tip değerlerini bir bayt akışına yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin bir örneğini yığıt üzerinde veya new operatörüyle oluşturmayın; bu yürütme zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Her zaman bu sınıfı bir [System::SmartPtr](../../system/smartptr/) işaretçisiyle sarmalayın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class BinaryWriter : public System::IDisposable
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [BinaryWriter](./binarywriter/)(const [StreamPtr](../../system/streamptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, **bool**) | Belirtilen akışı, belirtilen kodlamayı kullanarak veri yazan [BinaryWriter](./) sınıfının bir örneğini oluşturur. |
| void [Close](./close/)() | Mevcut [BinaryWriter](./) nesnesini ve temel çıktı akışını kapatır. |
| void [Dispose](./dispose/)() override | Mevcut nesnenin kullandığı tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) anlamı kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN'in eşit kabul edildiği, ancak IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı durum. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN'in eşit kabul edildiği, ancak IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil, eşit olmadığı durum. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() | Çıktı akışını temizler. |
| [StreamPtr](../../system/streamptr/) [get_BaseStream](./get_basestream/)() | Çıktı akışını döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin analoğu. Özel nesnelerin karma değerini (hash) oluşturmayı sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analoğu. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analoğu. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitleme işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) korunma nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin analoğu. Özel türlerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte bir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans ile karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize ve nullptr durumunun özelleştirilmiş hâli. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) için dize durumunun özelleştirilmiş hâli. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| **int64_t** [Seek](./seek/)(int, [System::IO::SeekOrigin](../seekorigin/)) | Mevcut nesne tarafından temsil edilen akışın konumunu ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf gösterici (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki göstericilerin zayıf moda geçmesini sağlar. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve geri döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin analoğu. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) koruma nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı göstericiler veya ThisProtector kullanılmalıdır. |
| virtual void [Write](./write/)(**uint8_t**) | Belirtilen işaretsiz 8-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Belirtilen bayt dizisinden belirtilen alt aralığı çıktı akışına yazar. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Belirtilen karakter dizisinden belirtilen UTF-16 karakter alt aralığını çıktı akışına yazar. |
| virtual void [Write](./write/)(**bool**) | Çıktı akışına, **value** 'true' ise 0, 'false' ise 1 değerinde tek bir bayt yazar. |
| virtual void [Write](./write/)(char16_t) | Belirtilen 16-bit genişliğindeki karakter değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**int16_t**) | Belirtilen 16-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(int) | Belirtilen 32-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**int64_t**) | Belirtilen 64-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**uint16_t**) | Belirtilen işaretsiz 16-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tam sayı değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerini çıktı akışına yazar. |
| virtual void [Write](./write/)(const [Decimal](../../system/decimal/)\&) | Belirtilen [Decimal](../../system/decimal/) değerinin bayt temsiliğini çıktı akışına yazar. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Mevcut kodlamada uzunluk öneki ekli bir dizeyi çıktı akışına yazar. |
| virtual void [Write](./write/)(const char_t *) | Mevcut kodlamada uzunluk öneki ekli bir dizeyi çıktı akışına yazar. |
|  [~BinaryWriter](./~binarywriter/)() | Yıkıcı. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |

## Ayrıca Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
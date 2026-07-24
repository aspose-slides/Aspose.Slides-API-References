---
title: StringBuilder
second_title: Aspose.Slides for C++ API Referansı
description: "Parça parça string biriktirmek için tampon. Bu tip, değer türü olarak yığın ya da System::MakeObject() işlevi kullanılarak yığın dışı içinde tahsis edilebilir. Nesne tahsis edildikten sonra, bu iki kullanım durumunu karıştırmayın: yığın üzerinde tahsis edilmiş nesnelere SmartPtr işaretçileri sahip olmak kesinlikle yasaktır."
type: docs
weight: 326
url: /tr/system.text/stringbuilder/
---
## StringBuilder sınıfı

[Buffer](../../system/buffer/) string parçalarını kısım kısım biriktirmek için. Bu tip yığın üzerine değer türü olarak ya da [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak yığın dışı üzerine tahsis edilebilir. Nesne tahsis edildikten sonra, bu iki kullanım durumunu asla karıştırmayın: yığın üzerinde tahsis edilmiş nesnelere [SmartPtr](../../system/smartptr/) işaretçileri sahip olmak kesinlikle yasaktır.

```cpp
class StringBuilder : public System::Object
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Derleyiciye karakter ekler. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Derleyiciye karakterler ekler. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Derleyiciye karakter dizisi ekler. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Derleyiciye karakter dizisi dilimini ekler. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Derleyiciye dize ekler. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Derleyiciye dize dilimini ekler. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Nesnenin dize temsilini derleyiciye ekler. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Derleyicinin içeriğini derleyiciye ekler. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Derleyiciye kayan nokta değeri ekler. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Derleyiciye çift hassasiyetli kayan nokta değeri ekler. |
| [StringBuilder](./) * [Append](./append/)(int) | Derleyiciye tamsayı değeri ekler. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Derleyiciye sayısal değer ekler. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Derleyiciye enum değerinin dize temsilini ekler. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Derleyiciye biçimlendirilmiş dize ekler. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Derleyiciye biçimlendirilmiş dize ekler. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Derleyiciye yeni satır karakteri ekler. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Derleyiciye yeni satır karakteri ile takip edilen dize ekler. |
| [StringBuilder](./) * [Clear](./clear/)() | Derleyiciden tüm karakterleri kaldırır. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Derleyici verilerini mevcut dizi konumlarına kopyalar. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Bu [System.Text.StringBuilder](./) örneğinin kapasitesinin belirtilen değerden en az olması sağlanır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | [Object.Equals](../../system/object/equals/) mantığını kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmadığı halde, iki NaN'in eşit kabul edildiği C# tarzı çift hassasiyetli kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili kullanım için. |
| int [get_Capacity](./get_capacity/)() const | StringBuilder'ın mevcut kapasitesini alır. |
| int [get_Length](./get_length/)() const | Derleyicide şu anda bulunan dizenin uzunluğunu alır. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin C# analogudur. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek türünü alır. [System.Object.GetType()](../../system/object/gettype/) çağrısının C# analogudur. |
| char_t [idx_get](./idx_get/)(int) const | Belirtilen konumdaki karakteri alır. |
| void [idx_set](./idx_set/)(int, char_t) | Belirtilen konumda karakteri ayarlar. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Derleyicide sabit konuma dize ekler. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Derleyicide sabit konuma yinelenen dize ekler. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Derleyicide sabit konuma karakter ekler. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Derleyicide sabit konuma karakterler ekler. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Derleyicide sabit konuma değeri ekler. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan türün bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin C# analogudur. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve türev sınıfların kopya yapımını mümkün kılar. |
| char_t [operator[]](./operator[]/)(int) const | Belirtilen konumdaki karakteri alır. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dize ve nullptr durumu için özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin dizeler durumu için özelleştirmesi. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Derleyiciden parçayı kaldırır. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Derleyicide alt dizgeyi değiştirir. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Derleyicinin aralığındaki alt dizgeyi değiştirir. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Derleyicide karakteri değiştirir. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Derleyicinin aralığındaki karakteri değiştirir. |
| void [set_Capacity](./set_capacity/)(int) | StringBuilder'ın mevcut kapasitesini ayarlar. |
| void [set_Length](./set_length/)(int) | StringBuilder'ı belirtilen uzunluğa kırpar veya genişletir. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşılan yerine) olarak ayarlar. Kapsayıcılardaki işaretçileri zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve değerini döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [StringBuilder](./stringbuilder/)() | Yapıcı. |
|  [StringBuilder](./stringbuilder/)(int) | Yapıcı. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Yapıcı. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Yapıcı. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Yapıcı. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Derleyicide şu anda bulunan dizgeyi alır. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Derleyicide şu anda bulunan alt dizgeyi alır. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözlem nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
|  [~StringBuilder](./~stringbuilder/)() | Yıkıcı. |

## Ayrıca

* Sınıf [Object](../../system/object/)
* Ad Alanı [System::Text](../)
* Kütüphane [Aspose.Slides](../../)
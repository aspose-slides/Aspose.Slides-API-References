---
title: TextWriter
second_title: Aspose.Slides for C++ API Referansı
description: "Farklı hedeflere karakter dizileri yazan yazarları temsil eden sınıflar için temel sınıftır. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle oluşturmamalısınız, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 443
url: /tr/system.io/textwriter/
---
## TextWriter sınıfı

Karakter dizilerini farklı hedeflere yazan yazarları temsil eden sınıflar için temel sınıftır. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tür bir örneği yığıt üzerinde veya new operatörüyle yaratmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın.

```cpp
class TextWriter : public System::IDisposable
```

## Yöntemler

| Method | Description |
| --- | --- |
| virtual void [Close](./close/)() | Akışı kapatır ve edinilen kaynakları serbest bırakır. |
| void [Dispose](./dispose/)() override | Mevcut nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Nesneleri C# [Object.Equals](../../system/object/equals/) semantiği kullanarak karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# tarzında karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# tarzında karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'ın hiçbir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'ın eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [Flush](./flush/)() | Arabellek içeriğini temel akışa yazar. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Şu anda kullanılan kodlamayı döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Bir satır sonlandırıcı dizesi döndürür. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Bir satır sonlandırıcı dizesi döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun benzeridir. Özel nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeridir. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını kontrol eder. C# 'is' operatörünün benzeridir. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun benzeridir. Özel tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya yapıcı. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Aslında hiçbir şey kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya yapımını mümkün kılar. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansına göre karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesidir. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Bir satır sonlandırıcı dizesi ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kaplardaki işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) metodunun benzeridir. Özel nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın ya da [LockContext](../../system/lockcontext/) gözetmen nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçileri veya ThisProtector'ı kullanın. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Belirtilen nesnenin string temsilini akışa yazar. |
| virtual void [Write](./write/)(**bool**) | Belirtilen boolean değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(char_t) | Belirtilen karakteri akışa yazar. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(int) | Belirtilen 32-bit tam sayı değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(**int64_t**) | Belirtilen 64-bit tam sayı değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Belirtilen string'i akışa yazar. |
| virtual void [Write](./write/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tam sayı değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tam sayı değerinin string temsilini akışa yazar. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Belirtilen dizideki tüm karakterleri akışa yazar. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Belirtilen karakter dizisinden belirtilen UTF-16 alt aralığını akışa yazar. |
| virtual void [Write](./write/)(const char_t *) | Belirtilen C-string'i akışa yazar. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin string temsilini akışa yazar. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen değerleri belirtilen biçime göre biçimlendirerek akışa yazar. |
| virtual void [WriteLine](./writeline/)() | Satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Belirtilen nesnenin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**bool**) | Belirtilen boolean değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(char_t) | Belirtilen karakteri ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(int) | Belirtilen 32-bit tam sayı değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Belirtilen 64-bit tam sayı değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Belirtilen string'i ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tam sayı değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tam sayı değerinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Belirtilen dizideki tüm karakterleri ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Belirtilen karakter dizisinden belirtilen UTF-16 alt aralığını ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Belirtilen C-string'i ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin string temsilini ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen değerleri belirtilen biçime göre biçimlendirerek ve ardından satır sonlandırıcı karakterlerini akışa yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~TextWriter](./~textwriter/)() | Yıkıcı. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for a shared pointer to this class. |

## Ayrıca Bakınız

* Sınıf [IDisposable](../../system/idisposable/)
* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
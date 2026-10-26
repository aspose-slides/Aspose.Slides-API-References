---
title: StreamWriter
second_title: Aspose.Slides for C++ API Referansı
description: "Karakterleri bir bayt akışına yazan bir yazar temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tür bir örnek yığını üzerinde veya new operatörüyle oluşturulmamalıdır, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 391
url: /tr/system.io/streamwriter/
---
## StreamWriter sınıfı

Represents a writer that writes characters to a byte stream. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| void [Close](./close/)() override | Akışı kapatır ve edinilen kaynakları serbest bırakır. |
| void [Dispose](./dispose/)() override | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual void [Dispose](./dispose/)(**bool**) | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) sözdizimini kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Referans türü nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Değer türü nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değerle, NaN dahil, eşit olmamasına rağmen iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| void [Flush](./flush/)() override | Arabelleğin içeriğini temel akıma boşaltır ve ardından temel akımı boşaltır. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Her [StreamWriter::Write](./write/) yöntemi çağrıldığında [StreamWriter](./)'nin verileri temel akıma boşaltıp boşaltmayacağını belirten bir değer döndürür. |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Temel akışı temsil eden bir nesneye paylaşımlı işaretçi döndürür. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Şu anda kullanılan kodlamayı döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Satır sonlandırıcı bir dize döndürür. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Satır sonlandırıcı bir dize döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) yönteminin benzeri. Özelleştirilmiş nesnelerin hash'lenmesini sağlar. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin, targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../../system/object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) yönteminin benzeri. Özelleştirilmiş tiplerin kopyalanmasını sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referans olarak karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipindeki nesneyi nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize ve nullptr durumu için özelleştirilmiş hali. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'in dize durumları için özelleştirilmiş hali. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşımlı referans sayacını belirtilen değer kadar azaltır. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | [StreamWriter::Write](./write/) yöntemi her çağrıldığında [StreamWriter](./)'nin verileri temel akıma boşaltıp boşaltmayacağını belirten bir değer döndürür. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Satır sonlandırıcı bir dize ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 'n'ıncı şablon argümanını zayıf işaretçi (paylaşımlı yerine) olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşımlı referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşımlı referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşımlı referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Belirtilen temel akışa UTF-8 kodlaması ve varsayılan 1024 bayt boyutunda bir arabellek kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen temel akışa belirtilen kodlamayı ve varsayılan 1024 bayt boyutunda bir arabellek kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Belirtilen temel akışa belirtilen kodlamayı ve belirtilen boyutta bir arabellek kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, [StreamWriter](./) nesnesi yok edildiğinde temel akışın kapatılıp kapatılmayacağını belirler. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Belirtilen dosyaya UTF-8 kodlaması ve varsayılan 1024 bayt boyutunda bir arabellek kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Belirtilen dosyaya belirtilen kodlamayı ve varsayılan 1024 bayt boyutunda bir arabellek kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirler. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Belirtilen dosyaya belirtilen kodlamayı ve tampon boyutunu kullanarak karakter yazan [StreamWriter](./) nesnesinin bir örneğini oluşturur. Bir parametre, verilerin dosyaya eklenip eklenmeyeceğini veya dosyanın üzerine yazılıp yazılmayacağını belirler. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) yönteminin benzeri. Özelleştirilmiş nesnelerin string'e dönüştürülmesini sağlar. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() ifadesinin kilit açma işlevini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözetim nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(char_t) override | Belirtilen karakteri akıma yazar. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Belirtilen dizeyi akıma yazar. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Belirtilen nesnenin dize temsilini akıma yazar. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Belirtilen dizideki tüm karakterleri akıma yazar. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Belirtilen karakter dizisinden UTF-16 karakterlerin belirtilen alt aralığını akıma yazar. |
| void [Write](./write/)(const char_t *) override | Belirtilen C dizgesini akıma yazar. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Belirtilen nesnenin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**bool**) | Belirtilen bool değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(int) | Belirtilen 32 bit tam sayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Belirtilen 64 bit tam sayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Belirtilen işaretsiz 32 bit tam sayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Belirtilen işaretsiz 64 bit tam sayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini akıma yazar. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen formatına göre biçimlendirilmiş değerleri akıma yazar. |
| void [WriteLine](./writeline/)() override | Satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Belirtilen dizeyi ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Belirtilen nesnenin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Belirtilen dizideki tüm karakterleri ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Belirtilen karakter dizisinden UTF-16 karakterlerin belirtilen alt aralığını ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const char_t *) override | Belirtilen C dizgesini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Belirtilen nesnenin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Belirtilen bool değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Belirtilen karakteri ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Belirtilen 32 bit tam sayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Belirtilen 64 bit tam sayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Belirtilen işaretsiz 32 bit tam sayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Belirtilen işaretsiz 64 bit tam sayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen formatına göre biçimlendirilmiş değerleri ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
|  [~StreamWriter](./~streamwriter/)() | Yıkıcı. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Yıkıcı. |

## Ayrıca Bakınız

* Sınıf [TextWriter](../textwriter/)
* Ad alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
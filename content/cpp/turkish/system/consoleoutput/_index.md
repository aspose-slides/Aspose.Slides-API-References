---
title: ConsoleOutput
second_title: Aspose.Slides for C++ API Referansı
description: "Standard çıktı akışını temsil eder. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörü ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirmek için kullanın."
type: docs
weight: 209
url: /tr/system/consoleoutput/
---
## ConsoleOutput sınıf

Standart çıktı akışını temsil eder. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../makeobject/) işlevi kullanılarak ayrılmalıdır. Bu türün örneğini yığıt üzerinde veya new operatörü ile asla oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına neden olur. Bu sınıfı her zaman [System::SmartPtr](../smartptr/) işaretçisi içine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Akışı kapatır ve elde edilen kaynakları serbest bırakır. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | [Object.Equals](../object/equals/) semantiği kullanarak nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Referans tipi nesneleri C# stilinde karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Değer tipi nesneleri C# stilinde karşılaştırır. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989'a göre NaN'in herhangi bir değere, NaN dahil, eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Tamponun içeriğini temel akışa boşaltır. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Her zaman ASCII kodlamasını döndürür. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Şu anda kullanılan [IFormatProvider](../iformatprovider/) nesnesini döndürür. |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Şu anda kullanılan [IFormatProvider](../iformatprovider/) nesnesini döndürür. |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Satır sonlandırıcı bir dize döndürür. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Satır sonlandırıcı bir dize döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | [Object.GetHashCode()](../object/gethashcode/) yönteminin C# benzeri. Özel nesnelerin hashlenmesini sağlar. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../object/gettype/) çağrısının benzeri. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipin bir örneği olup olmadığını denetler. C# 'is' operatörünün benzeri. |
| void [Lock](../object/lock/)() | C# lock() ifadesinin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetleme nesnesini kullanın. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | [Object.MemberwiseClone()](../object/memberwiseclone/) yönteminin C# benzeri. Özel tiplerin klonlanmasını sağlar. |
| [Object](../object/object/)() | Nesne oluşturur. Tüm dahili veri yapılarını başlatır. |
| [Object](../object/object/)([Object](../object/) const\&) | Kopya yapıcı. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını sağlar. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Değer tipi nesneyi nullptr ile referans karşılaştırması yapar. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../object/referenceequals/)'nin string ve nullptr durumu için özelleştirmesidir. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | [Object::ReferenceEquals](../object/referenceequals/)'nin string'ler durumu için özelleştirmesidir. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Satır sonlandırıcı dize ayarlar. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | 'n'inci şablon argümanını paylaşımlı yerine zayıf işaretçi olarak ayarlar. Kapsayıcılardaki işaretçilerin zayıf moda geçişine izin verir. |
| int [SharedCount](../object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | [Object.ToString()](../object/tostring/) yönteminin C# benzeri. Özel nesnelerin dizeye dönüştürülmesini sağlar. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | C# typeof([System.Object](../object/)) yapısını uygular. |
| void [Unlock](../object/unlock/)() | C# lock() ifadesinin kilit açmasını uygular. Doğrudan çağırın veya [LockContext](../lockcontext/) gözetleme nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(**bool**) override | Belirtilen bool değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Belirtilen nesnenin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(char_t) override | Belirtilen karakter değerini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)([Decimal](../decimal/)) override | [Decimal](../decimal/) değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**double**) override | Çift duyarlıklı kayan nokta değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**int32_t**) override | 32-bit tamsayı değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**int64_t**) override | 64-bit tamsayı değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**float**) override | Tek duyarlıklı kayan nokta değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const [String](../string/)\&) override | Belirtilen dize nesnesini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**uint32_t**) override | İmzalanmamış 32-bit tamsayı değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(**uint64_t**) override | İmzalanmamış 64-bit tamsayı değerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Belirtilen karakter dizisinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Belirtilen karakter dizisinin bir aralık değerlerinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const char_t *) override | Belirtilen C dizgisini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Belirtilen [TypeInfo](../typeinfo/) nesnesinin dize temsilini, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Belirtilen 32-bit tamsayı değerinin dize temsilini akışa yazar. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Belirtilen değerleri, belirtilen biçime göre biçimlendirilmiş olarak akışa yazar. |
| void [WriteLine](./writeline/)() override | Geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Belirtilen nesnenin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**bool**) override | Belirtilen bool değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(char_t) override | Belirtilen karakter değerini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | [Decimal](../decimal/) değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**double**) override | Çift duyarlıklı kayan nokta değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(int) override | 32-bit tamsayı değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**int64_t**) override | 64-bit tamsayı değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**float**) override | Tek duyarlıklı kayan nokta değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Belirtilen dize nesnesini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**uint32_t**) override | İmzalanmamış 32-bit tamsayı değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(**uint64_t**) override | İmzalanmamış 64-bit tamsayı değerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Belirtilen karakter dizisinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Belirtilen karakter dizisinin bir aralık değerlerinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const char_t *) override | Belirtilen c-dizgisini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Belirtilen [TypeInfo](../typeinfo/) nesnesinin dize temsilini, ardından geçerli satır sonlandırıcıyı, geçerli nesne tarafından temsil edilen çıktı akışına yazar. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Belirtilen değerleri, belirtilen biçime göre biçimlendirilmiş olarak, ardından satır sonlandırıcı karakterleriyle birlikte akışa yazar. |
| virtual  [~Object](../object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Yıkıcı. |

## Ayrıca Bakınız

* Sınıf [TextWriter](../../system.io/textwriter/)
* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)
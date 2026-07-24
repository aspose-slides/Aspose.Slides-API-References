---
title: StringWriter
second_title: Aspose.Slides for C++ API Referansı
description: "Bilgiyi bir dizeye yazan bir TextWriter uygular. Bu sınıfın nesneleri yalnızca System::MakeObject() işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman System::SmartPtr işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin."
type: docs
weight: 417
url: /tr/system.io/stringwriter/
---
## StringWriter sınıfı

Bir [TextWriter](../textwriter/) uygular ve bilgiyi bir dizeye yazar. Bu sınıfın nesneleri yalnızca [System::MakeObject()](../../system/makeobject/) işlevi kullanılarak ayrılmalıdır. Bu tipin örneğini asla yığıt üzerinde veya new operatörüyle oluşturmayın, çünkü bu çalışma zamanı hatalarına ve/veya doğrulama hatalarına yol açar. Bu sınıfı her zaman [System::SmartPtr](../../system/smartptr/) işaretçisine sarın ve bu işaretçiyi fonksiyonlara argüman olarak geçirin.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Akışı kapatır ve edinilen kaynakları serbest bırakır. |
| void [Dispose](../textwriter/dispose/)() override | Geçerli nesne tarafından kullanılan tüm kaynakları serbest bırakır ve temel akışı kapatır. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) anlamı ile nesneleri karşılaştırır. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında referans türü nesneleri karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# tarzında değer türü nesneleri karşılaştırır. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# tarzı kayan nokta karşılaştırmasını taklit eder; iki NaN eşit kabul edilir, ancak IEC 60559:1989'a göre NaN hiçbir değere, NaN dahil, eşit değildir. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Yalnızca dahili amaçlar için. |
| virtual void [Flush](../textwriter/flush/)() | Arabellek içeriğini temel akışa boşaltır. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Şu anda kullanılan kodlamayı döndürür. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Şu anda kullanılan [IFormatProvider](../../system/iformatprovider/) nesnesini döndürür. |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Bir satır sonlandırıcı dizesi döndürür. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Bir satır sonlandırıcı dizesi döndürür. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Nesneyle ilişkili referans sayacı veri yapısını alır. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) metodunun analogudur. Özel nesnelerin karmasını (hash) etkinleştirir. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Şu anda kullanılan StringBuilder'ı döndürür. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Nesnenin gerçek tipini alır. C# [System.Object.GetType()](../../system/object/gettype/) çağrısının analogudur. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Nesnenin targetType tarafından tanımlanan tipe bir örnek olup olmadığını denetler. C# 'is' operatörünün analogudur. |
| void [Lock](../../system/object/lock/)() | C# lock() deyiminin kilitlemesini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) metodunun analogudur. Özel tiplerin kopyalanmasını (klonlamasını) sağlar. |
|  [Object](../../system/object/object/)() | Nesneyi oluşturur. Tüm dahili veri yapılarını başlatır. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopya kurucu. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını (copy constructing) etkinleştirir. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Atama operatörü. Gerçekte hiçbir şeyi kopyalamaz, sadece yeni nesneyi başlatır ve alt sınıfların kopya oluşturmasını etkinleştirir. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Nesneleri referansla karşılaştırır. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Değer türü nesnesini nullptr ile referans olarak karşılaştırır. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | String ve nullptr durumu için [Object::ReferenceEquals](../../system/object/referenceequals/) özelleştirmesi. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/)'nin string durumları için özelleştirmesi. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Paylaşılan referans sayacını belirtilen değer kadar azaltır. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Satır sonlandırıcı dizesini ayarlar. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'inci şablon argümanını güçlü (shared) yerine zayıf bir işaretçi olarak ayarlar. Kaplarda işaretçileri zayıf moda geçirmeye izin verir. |
| int [SharedCount](../../system/object/sharedcount/)() const | Paylaşılan referans sayacının mevcut değerini alır. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Paylaşılan referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Paylaşılan referans sayacını azaltır ve döndürür. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | [StringWriter](./)'nin yeni bir örneğini belirtilen StringBuilder ve [IFormatProvider](../../system/iformatprovider/) kullanarak oluşturur. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | [StringWriter](./)'nin yeni bir örneğini belirtilen StringBuilder ve geçerli kültürden [IFormatProvider](../../system/iformatprovider/) kullanarak oluşturur. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | [StringWriter](./)'nin yeni bir örneğini belirtilen [IFormatProvider](../../system/iformatprovider/) kullanarak oluşturur. |
|  [StringWriter](./stringwriter/)() | [StringWriter](./)'nin yeni bir örneğini geçerli kültürden [IFormatProvider](../../system/iformatprovider/) kullanarak oluşturur. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Temel dizeyi döndürür. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) yapısını uygular. |
| void [Unlock](../../system/object/unlock/)() | C# lock() deyiminin kilit açma işlemini uygular. Doğrudan çağırın veya [LockContext](../../system/lockcontext/) gözcü nesnesini kullanın. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Zayıf referans sayacını artırır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Zayıf referans sayacını azaltır. Doğrudan çağrılmamalıdır; bunun yerine akıllı işaretçiler veya ThisProtector kullanılmalıdır. |
| void [Write](./write/)(char_t) override | Belirtilen karakteri akıma yazar. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Belirtilen karakter dizisinden belirtilen karakter alt aralığını akıma yazar. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Belirtilen dizeyi akıma yazar. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Belirtilen nesnenin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**bool**) | Belirtilen boolean değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(int) | Belirtilen 32-bit tamsayı değerinin dize temsilini akımaya yazar. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Belirtilen 64-bit tamsayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tamsayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tamsayı değerinin dize temsilini akıma yazar. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Belirtilen diziden tüm karakterleri akıma yazar. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Belirtilen c-dizesini akıma yazar. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini akıma yazar. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen değerleri belirtilen biçime göre formatlayarak akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)() | Satır sonlandırıcı karakterlerini akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Belirtilen nesnenin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Belirtilen boolean değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Belirtilen karakteri ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Belirtilen [Decimal](../../system/decimal/) nesnesinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Belirtilen çift duyarlıklı kayan nokta değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Belirtilen 32-bit tamsayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Belirtilen 64-bit tamsayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Belirtilen tek duyarlıklı kayan nokta değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Belirtilen dizeyi ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Belirtilen işaretsiz 32-bit tamsayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Belirtilen işaretsiz 64-bit tamsayı değerinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Belirtilen diziden tüm karakterleri ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Belirtilen karakter dizisinden UTF-16 karakterlerinin belirtilen alt aralığını ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Belirtilen c-dizesini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Belirtilen [TypeInfo](../../system/typeinfo/) nesnesinin dize temsilini ve ardından satır sonlandırıcı karakterleri akıma yazar. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Belirtilen değerleri belirtilen biçime göre formatlayarak akıma yazar ve ardından satır sonlandırıcı karakterler ekler. |
| virtual  [~Object](../../system/object/~object/)() | Nesneyi yok eder. Tüm dahili veri yapılarını serbest bırakır. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Yıkıcı. |
## İlgili

* Sınıf [TextWriter](../textwriter/)
* Ad Alanı [System::IO](../)
* Kütüphane [Aspose.Slides](../../)
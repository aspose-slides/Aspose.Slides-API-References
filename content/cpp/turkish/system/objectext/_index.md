---
title: ObjectExt
second_title: Aspose.Slides for C++ API Referansı
description: Statik yöntemler sağlar; C# Object yöntemlerini taklit eder ve nesne olmayan C++ tipleri (dizeler, sayılar vb.) için çağrılır. Bu, örnek hizmeti olmayan statik bir tiptir. Hiçbir şekilde onun örneklerini oluşturmayın.
type: docs
weight: 1145
url: /tr/system/objectext/
---
## ObjectExt sınıfı

C# [Object](../object/) yöntemlerini taklit eden, nesne olmayan C++ tipleri (dizeler, sayılar vb.) için çağrılan statik yöntemler sağlar. Bu, örnek hizmeti olmayan statik bir tiptir. Hiçbir şekilde onun örneklerini oluşturmayın.

```cpp
class ObjectExt : public System::ObjectType
```

## Yöntemler

| Method | Açıklama |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Dizi temel değerlerini (C#'ın otomatik olarak yaptığı ancak C++'ın görünüşe göre yapmadığı) dönüştürür. |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Değer tiplerini [Object](../object/)'a dönüştürmek için kutular. Enum tipleri için uygulama. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Değer tiplerini [Object](../object/)'a dönüştürmek için kutular. Enum olmayan tipler için uygulama. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | [Nullable](../nullable/) tiplerini [Object](../object/)'a dönüştürmek için kutular. |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Dize değerlerini kutular. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | [Object](../object/) olarak yayılması için enum tiplerini kutular. |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | NULL olmayan tipler için '??' operatörünün çevirisinin uygulanması. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | NULL olabilir tipler için '??' operatörünün çevirisinin uygulanması. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | '??=' operatörünün çevirisinin uygulanması. |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | NULL olmayan tipler için '??' operatörünün çevirisinin uygulanması. RT2'nin RT1'e dönüştürülebilir olduğu durum için aşırı yükleme. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan ikame. Akıllı gösterici tipleri için aşırı yükleme. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | C# [Object.Equals](../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan ikame. Yapı tipleri için aşırı yükleme. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | C# [Object.Equals](../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan ikame. Skaler tipler için aşırı yükleme. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | C# [Object.Equals](../object/equals/) çağrıları için, C++'da herhangi bir tipte çalışan ikame. Dize karşılaştırmasıyla dize sabiti için aşırı yükleme. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil olmak üzere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı kayan nokta karşılaştırmasını taklit eder. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | IEC 60559:1989'a göre NaN'in hiçbir değerle, NaN dahil olmak üzere eşit olmamasına rağmen, iki NaN'in eşit kabul edildiği C# tarzı çift duyarlıklı kayan nokta karşılaştırmasını taklit eder. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | [GetHashCode()](./gethashcode/) çağrılarını uygular; hem [Object](../object/) alt sınıflarında hem de alakasız tiplerde çalışır. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() çevirisini uygular. Akıllı göstericiler için aşırı yükleme. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() çevirisini uygular. Yapılar için aşırı yükleme. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | typeof() çevirisini uygular. İstisnalar için aşırı yükleme. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() çevirisini uygular. İlkel tipler için aşırı yükleme. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | typeof() çevirisini uygular. [Nullable](../nullable/) tipleri için aşırı yükleme. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. İlkel tipler için aşırı yükleme. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. Enum tipleri için aşırı yükleme. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. Yapılar ve göstergeler için aşırı yükleme. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. [Nullable](../nullable/) için aşırı yükleme. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. MutlicastDelegate için aşırı yükleme. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. Yapılar ve göstergeler için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | typeof() çevirisini uygular. Dize tipi için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | 'is' operatörünün çevirisini uygular. Kutulanabilir (değer) tipler için özelleştirme, yani tam olarak oldukları tipler. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' operatörünün çevirisini uygular. 'final' sınıflar için optimize edilmiş gösterici tipleri için özelleştirme. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | 'is' operatörünün çevirisini uygular. Gösterici tipleri için özelleştirme. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' operatörünün çevirisini uygular. Değer tipleri için özelleştirme. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | 'is' operatörünün çevirisini uygular. Dönüştürülemez tipler için özelleştirme. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' operatörünün çevirisini uygular. Gösterici tipleri için özelleştirme. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | 'is' operatörünün çevirisini uygular. İstisna sarmalayıcı tipleri için özelleştirme. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' operatörünün çevirisini uygular. Null olabilen tipler için özelleştirme. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' operatörünün çevirisini uygular. == operatörü tanımlı kutulanabilir tipler için özelleştirme. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | 'is' operatörünün çevirisini uygular. == operatörü tanımlanmamış kutulanabilir tipler için özelleştirme. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | 'is' operatörünün çevirisini uygular. Arabirimlere kutulanmış değer tipleri için özelleştirme. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | 'is' operatörünün çevirisini uygular. Enum tipleri için özelleştirme. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | 'is' operatörünün çevirisini uygular. Enum tipleri ve zayıf göstergeler için özelleştirme. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | 'is' operatörünün çevirisini uygular. [Nullable](../nullable/) tipi için özelleştirme. |
| static **bool** [Is](./is/)(const char16_t *) | 'is' operatörünün çevirisini uygular. Dize sabiti için özelleştirme. |
| static **bool** [Is](./is/)(**int32_t**) | 'is' operatörünün çevirisini uygular. Tam sayı sabiti için özelleştirme. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Nesnenin kutulanmış bir değer olup olmadığını denetler. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/)'ı bilinmeyen tipe dönüştürür, hem akıllı gösterici tipini hem de kutulanmış değer durumlarını ele alır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | [Object](../object/)'ı bilinmeyen tipe dönüştürür, hem akıllı gösterici tipini hem de kutulanmış değer durumlarını ele alır. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | C# ToString metodunun herhangi bir C++ tipinde çalışması için ikame. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/)'a dönüştürdükten sonra değer tiplerini kutudan çıkarır. Enum tipleri için uygulama. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/)'a dönüştürdükten sonra değer tiplerini kutudan çıkarır. Enum olmayan ve null olmayan tipler için uygulama. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | [Object](../object/)'a dönüştürdükten sonra değer tiplerini kutudan çıkarır. Enum olmayan ve null olmayan tipler için uygulama. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Enum tiplerini tamsayıya kutudan çıkarır. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Enum tiplerini dönüştürür. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Dize değerlerini kutudan çıkarır. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Kutu içinde bulunan değerden dizeyi kutudan çıkarır. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Nesneyi null olabilen tipe kutudan çıkarır. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Bilinmeyen tip nesnesinin nullptr olup olmadığını denetler. Skaler olmayan tipler için aşırı yükleme. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Bilinmeyen tip nesnesinin nullptr olup olmadığını denetler. Skaler tipler için aşırı yükleme. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Bilinmeyen tipi [Object](../object/)'a dönüştürür, hem akıllı gösterici tipini hem de değer tipini ele alır. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Bilinmeyen tipi [Object](../object/)'a dönüştürür, hem akıllı gösterici tipini hem de değer tipini ele alır. |
## Bakınız

* Sınıf [ObjectType](../objecttype/)
* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)
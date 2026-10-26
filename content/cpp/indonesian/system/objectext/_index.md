---
title: ObjectExt
second_title: Aspose.Slides untuk C++ Referensi API
description: Menyediakan metode statis yang meniru metode Object C# yang dipanggil untuk tipe C++ non-Object (string, angka, dll.). Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.
type: docs
weight: 1145
url: /id/system/objectext/
---
## ObjectExt kelas


Provides static methods that emulate C# [Object](../object/) methods called for non-Object C++ types (strings, numbers, etc.). This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class ObjectExt : public System::ObjectType
```

## Metode

| Method | Description |
| --- | --- |
| static std::enable_if<(std::is_fundamental\<To\>::value), std::array\<To, sizeof...(From)>\>::type [ArrayInitializerCast](./arrayinitializercast/)(From ...) | Mengonversi nilai fundamental array (yang C# lakukan secara implisit tetapi C++ tampaknya tidak melakukannya). |
| static std::enable_if\<std::is_enum\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Membungkus tipe nilai untuk konversi ke [Object](../object/). Implementasi untuk tipe enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Membungkus tipe nilai untuk konversi ke [Object](../object/). Implementasi untuk tipe non-enum. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[System::Object](../object/)\>\>::type [Box](./box/)(const T\&) | Membungkus tipe [Nullable](../nullable/) untuk konversi ke [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[Object](../object/)\> [Box](./box/)(const [String](../string/)\&) | Membungkus nilai string. |
| static [SmartPtr](../smartptr/)\<[System::BoxedValueBase](../boxedvaluebase/)\> [BoxEnum](./boxenum/)(T) | Membungkus tipe enum untuk dipropagasikan sebagai [Object](../object/). |
| static [SmartPtr](../smartptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CastToIList](./casttoilist/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) |  |
| static auto [Coalesce](./coalesce/)(T0, T1) | Implementasi terjemahan operator '??' untuk tipe yang tidak dapat null. |
| static T0 [Coalesce](./coalesce/)([System::Nullable](../nullable/)\<T0\>, T1) | Implementasi terjemahan operator '??' untuk tipe yang dapat null. |
| static auto [CoalesceAssign](./coalesceassign/)(T0\&, T1) | Implementasi terjemahan operator '??=' . |
| static std::conditional\<std::is_convertible\<RT2, RT1\>::value, RT1, RT2\>::type [CoalesceInternal](./coalesceinternal/)(RT1, F) | Implementasi terjemahan operator '??' untuk tipe yang tidak dapat null. Overload untuk kasus jika RT2 dapat dikonversi ke RT1. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) |  |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Pengganti untuk pemanggilan C# [Object.Equals](../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe smart pointer. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(T, const T2\&) | Pengganti untuk pemanggilan C# [Object.Equals](../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe struktur. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value, **bool**\>::type [Equals](./equals/)(const T\&, const T2\&) | Pengganti untuk pemanggilan C# [Object.Equals](../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe skalar. |
| static **bool** [Equals](./equals/)(const char_t(&), [String](../string/)) | Pengganti untuk pemanggilan C# [Object.Equals](../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk literal string dengan perbandingan string. |
| static **bool** [Equals](./equals/)(const **float**\&, const **float**\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static **bool** [Equals](./equals/)(const **double**\&, const **double**\&) | Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static std::enable_if\<[System::IsSmartPtr](../issmartptr/)\<T\>::value, [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>\>::type [ExplicitCastToObject](./explicitcasttoobject/)(const T\&) |  |
| static int [GetHashCode](./gethashcode/)(const T\&) | Mengimplementasikan pemanggilan [GetHashCode()](./gethashcode/); berfungsi pada subclass [Object](../object/) serta tipe yang tidak terkait. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk smart pointer. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk struktur. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk pengecualian. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe primitif. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)(const T) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk tipe primitif. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk tipe enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk struktur dan pointer. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk struktur dan pointer. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)(const [String](../string/)\&) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](../objecttype/gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value, **bool**\>::type [Is](./is/)(const T\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibungkus (nilai) yang secara tepat adalah mereka. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe pointer yang dioptimalkan untuk kelas 'final'. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value\&&\!std::is_final\<T\>::value\&&\![System::IsBoxable](../isboxable/)\<T\>::value\&&[System::IsSmartPtr](../issmartptr/)\<U\>::value, **bool**\>::type [Is](./is/)(const U\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe pointer. |
| static std::enable_if\<std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe nilai. |
| static std::enable_if<\!std::is_convertible\<T, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [Object](../object/)\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe yang tidak dapat dikonversi. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe pointer. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, **bool**\>::type [Is](./is/)(const [ExceptionWrapper](../exceptionwrapper/)\<U\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe pembungkus pengecualian. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat null. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibungkus dengan operator == yang didefinisikan. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibungkus tanpa operator == yang didefinisikan. |
| static std::enable_if\<[System::IsBoxable](../isboxable/)\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_enum\<T\>::value\&&\!std::is_same\<V, [Object](../object/)\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<V\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi tipe nilai yang dibungkus ke antarmuka. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [SmartPtr](../smartptr/)\<U\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe enum. |
| static std::enable_if\<std::is_enum\<T\>::value, **bool**\>::type [Is](./is/)(const [WeakPtr](../weakptr/)\<U\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe enum versus weak pointer. |
| static **bool** [Is](./is/)(const [Nullable](../nullable/)\<U\>\&) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk tipe [Nullable](../nullable/). |
| static **bool** [Is](./is/)(const char16_t *) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk literal string. |
| static **bool** [Is](./is/)(**int32_t**) | Mengimplementasikan terjemahan operator 'is'. Spesialisasi untuk literal integer. |
| static **bool** [IsBoxedValue](./isboxedvalue/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Memeriksa apakah objek adalah nilai yang dibungkus. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Mengonversi [Object](../object/) ke tipe tidak diketahui, menangani baik tipe smart pointer maupun situasi nilai yang dibungkus. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, T\>::type [ObjectToUnknown](./objecttounknown/)([SmartPtr](../smartptr/)\<[Object](../object/)\>) | Mengonversi [Object](../object/) ke tipe tidak diketahui, menangani baik tipe smart pointer maupun situasi nilai yang dibungkus. |
| static [String](../string/) [ToString](./tostring/)(const char_t *) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static [String](../string/) [ToString](./tostring/)(const [Nullable](../nullable/)\<T\>\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if\<std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value||std::is_pointer\<T\>::value||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&std::is_scalar\<T\>::value\&&\!std::is_enum\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(const T\&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_scalar\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value\&&\!std::is_reference\<T\>::value, [String](../string/)\>::type [ToString](./tostring/)(T\&&) | Pengganti untuk metode C# ToString agar berfungsi pada tipe C++ apa pun. |
| static std::enable_if\<std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Membuka nilai tipe setelah konversi ke [Object](../object/). Implementasi untuk tipe enum. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Membuka nilai tipe setelah konversi ke [Object](../object/). Implementasi untuk tipe bukan enum & non-nullable. |
| static std::enable_if<\!std::is_enum\<T\>::value\&&\!detail::has_operator_equal\<T\>::value, T\>::type [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Membuka nilai tipe setelah konversi ke [Object](../object/). Implementasi untuk tipe bukan enum & non-nullable. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::numeric_limits\<T\>::is_integer, T\>::type [Unbox](./unbox/)(E) | Membuka tipe enum menjadi integer. |
| static std::enable_if\<std::is_enum\<E\>::value\&&std::is_enum\<T\>::value, T\>::type [Unbox](./unbox/)(E) | Mengonversi tipe enum. |
| static [String](../string/) [Unbox](./unbox/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Membuka nilai string. |
| static [String](../string/) [UnboxStringSafe](./unboxstringsafe/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&) | Membuka string dari nilai yang dibungkus. |
| static [Nullable](../nullable/)\<T\> [UnboxToNullable](./unboxtonullable/)(const [SmartPtr](../smartptr/)\<[Object](../object/)\>\&, **bool**) | Membuka objek ke tipe yang dapat null. |
| static std::enable_if<\!std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Memeriksa apakah objek tipe tidak diketahui adalah nullptr. Overload untuk tipe non-scalar. |
| static std::enable_if\<std::is_scalar\<T\>::value, **bool**\>::type [UnknownIsNull](./unknownisnull/)(T) | Memeriksa apakah objek tipe tidak diketahui adalah nullptr. Overload untuk tipe scalar. |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(T) | Mengonversi tipe tidak diketahui ke [Object](../object/), menangani baik tipe smart pointer maupun tipe nilai. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, [System::SmartPtr](../smartptr/)\<[Object](../object/)\>\>::type [UnknownToObject](./unknowntoobject/)(const T\&) | Mengonversi tipe tidak diketahui ke [Object](../object/), menangani baik tipe smart pointer maupun tipe nilai. |

## Lihat Juga

* Kelas [ObjectType](../objecttype/)
* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)
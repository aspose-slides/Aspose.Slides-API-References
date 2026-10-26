---
title: ObjectType
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan metode statis yang mengimplementasikan pengambil tipe objek. Ini adalah tipe statis tanpa layanan instansi. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.
type: docs
weight: 1158
url: /id/system/objecttype/
---
## ObjectType kelas

Menyediakan metode statis yang mengimplementasikan pengambil tipe objek. Ini adalah tipe statis tanpa layanan instance. Anda tidak boleh pernah membuat instance darinya dengan cara apa pun.

```cpp
class ObjectType
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk penunjuk pintar. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk struktur. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Mengimplementasikan terjemahan typeof(). Overload untuk pengecualian. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe primitif. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe [Nullable](../nullable/). |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk tipe primitif. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk tipe enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk struktur dan penunjuk. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk MutlicastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk struktur dan penunjuk. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Mengimplementasikan terjemahan typeof(). Overload untuk tipe string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Mengimplementasikan terjemahan typeof(). Overload untuk **uint8_t**. |

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)
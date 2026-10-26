---
title: ObjectType
second_title: Aspose.Slides C++ API Referansı
description: Nesne türü alıcılarını uygulayan statik yöntemler sağlar. Bu, örnek hizmeti olmayan bir statik türdür. Hiçbir şekilde onun örneklerini oluşturmamalısınız.
type: docs
weight: 1158
url: /tr/system/objecttype/
---
## ObjectType sınıfı

Nesne türü alıcılarını uygulayan statik yöntemler sağlar. Bu, örnek hizmeti olmayan bir statik türdür. Hiçbir şekilde onun örneklerini oluşturmayınız.

```cpp
class ObjectType
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() çevirisini uygular. Akıllı işaretçiler için aşırı yükleme. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() çevirisini uygular. Yapılar için aşırı yükleme. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | typeof() çevirisini uygular. İstisnalar için aşırı yükleme. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() çevirisini uygular. İlkel türler için aşırı yükleme. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | typeof() çevirisini uygular. [Nullable](../nullable/) türleri için aşırı yükleme. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. İlkel türler için aşırı yükleme. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. enum türleri için aşırı yükleme. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. Yapılar ve işaretçiler için aşırı yükleme. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. [Nullable](../nullable/) için aşırı yükleme. |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. MutlicastDelegate için aşırı yükleme. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | typeof() çevirisini uygular. Yapılar ve işaretçiler için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | typeof() çevirisini uygular. string türü için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | typeof() çevirisini uygular. **uint8_t** için aşırı yükleme. |

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)
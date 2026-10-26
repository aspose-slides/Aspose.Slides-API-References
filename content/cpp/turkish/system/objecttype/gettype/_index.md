---
title: GetType()
second_title: Aspose.Slides for C++ API Referansı
description: typeof() çevirisini uygular. Akıllı işaretçiler için aşırı yükleme.
type: docs
weight: 1
url: /tr/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) yöntemi

typeof() çevirisini uygular. Akıllı işaretçiler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İşaretçi nesne tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) [TypeInfo](../../typeinfo/) elde etmek için. |

### Dönüş Değeri

Geçilen nesnenin son sınıfını tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType(const T\&) yöntemi

typeof() çevirisini uygular. Yapılar için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Yapı tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) [TypeInfo](../../typeinfo/) elde etmek için. |

### Dönüş Değeri

Geçilen nesnenin son sınıfını tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType(const T\&) yöntemi

typeof() çevirisini uygular. İstisnalar için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İstisna tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) [TypeInfo](../../typeinfo/) elde etmek için. |

### Dönüş Değeri

Geçilen nesnenin son sınıfını tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType(const T) yöntemi

typeof() çevirisini uygular. İlkel tipler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T | IGNORED |

### Dönüş Değeri

Geçilen nesnenin tipini tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType(const T) yöntemi

typeof() çevirisini uygular. [Nullable](../../nullable/) tipleri için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Nullable](../../nullable/) tipi. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | const T | IGNORED |

### Dönüş Değeri

Geçilen nesnenin tipini tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. İlkel tipler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Dönüş Değeri

Belirtilen tipi tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. Enum tipleri için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Dönüş Değeri

Belirtilen tipi tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. Yapılar ve işaretçiler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Dönüş Değeri

Belirtilen yapıyı tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. [Nullable](../../nullable/) için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | [Nullable](../../nullable/) tipi. |

### Dönüş Değeri

Belirtilen yapıyı tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. MutlicastDelegate için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | MutlicastDelegate tipi. |

### Dönüş Değeri

Belirtilen yapıyı tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. Yapılar ve işaretçiler için aşırı yükleme.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Dönüş Değeri

Belirtilen yapıyı tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans; eğer [SmartPtr](../../smartptr/) istendiğinde işaret edilen tip döner.

## ObjectType::GetType(const String\&) yöntemi

typeof() çevirisini uygular. Dize tipi için aşırı yükleme.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | İlkel tip. |

### Dönüş Değeri

[String](../../string/) tipini tanımlayan [TypeInfo](../../typeinfo/) yapısına sabit referans.

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. **uint8_t** için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. char16_t için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. **int32_t** için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. **int64_t** için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. bool için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() yöntemi

typeof() çevirisini uygular. [Void](../../void/) için aşırı yükleme.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## İlgili

* Sınıf [ObjectType](../)
* Sınıf [TypeInfo](../../typeinfo/)
* Sınıf [String](../../string/)
* Yapı [IsSmartPtr](../../issmartptr/)
* Yapı [IsExceptionWrapper](../../isexceptionwrapper/)
* Yapı [IsNullable](../../isnullable/)
* Yapı [IsBoxable](../../isboxable/)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)
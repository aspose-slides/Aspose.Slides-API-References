---
title: GetType()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerapkan terjemahan typeof(). Overload untuk pointer pintar.
type: docs
weight: 1
url: /id/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) metode

Menerapkan terjemahan typeof(). Overload untuk pointer pintar.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Pointer object type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) untuk mendapatkan [TypeInfo](../../typeinfo/) untuk. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan kelas akhir dari objek yang diberikan.

## ObjectType::GetType(const T\&) metode

Menerapkan terjemahan typeof(). Overload untuk struktur.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Structure type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) untuk mendapatkan [TypeInfo](../../typeinfo/) untuk. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan kelas akhir dari objek yang diberikan.

## ObjectType::GetType(const T\&) metode

Menerapkan terjemahan typeof(). Overload untuk exception.

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Exception type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) untuk mendapatkan [TypeInfo](../../typeinfo/) untuk. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan kelas akhir dari objek yang diberikan.

## ObjectType::GetType(const T) metode

Menerapkan terjemahan typeof(). Overload untuk tipe primitif.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T | IGNORED |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan tipe objek yang diberikan.

## ObjectType::GetType(const T) metode

Menerapkan terjemahan typeof(). Overload untuk tipe [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T | IGNORED |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan tipe objek yang diberikan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk tipe primitif.

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan tipe yang ditentukan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk tipe enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan tipe yang ditentukan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk struktur dan pointer.

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan struktur yang ditentukan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk [Nullable](../../nullable/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan struktur yang ditentukan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk MutlicastDelegate.

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | MutlicastDelegate type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan struktur yang ditentukan.

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk struktur dan pointer.

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan struktur yang ditentukan atau tipe pointee jika dipanggil untuk [SmartPtr](../../smartptr/).

## ObjectType::GetType(const String\&) metode

Menerapkan terjemahan typeof(). Overload untuk tipe string.

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Primitive type. |

### Nilai Kembalian

Referensi konstan ke struktur [TypeInfo](../../typeinfo/) yang menggambarkan tipe [String](../../string/).

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk **uint8_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk char16_t.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk **int32_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk **int64_t**.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk bool.

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() metode

Menerapkan terjemahan typeof(). Overload untuk [Void](../../void/).

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## Lihat Juga

* Kelas [ObjectType](../)
* Kelas [TypeInfo](../../typeinfo/)
* Kelas [String](../../string/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Struktur [IsBoxable](../../isboxable/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
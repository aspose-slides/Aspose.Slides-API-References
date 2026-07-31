---
title: Is()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibox (nilai) secara tepat.
type: docs
weight: 92
url: /id/system/objectext/is/
---
## ObjectExt::Is(const T\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibox (nilai) secara tepat.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) untuk menguji operator 'is'. Diabaikan. |

### Nilai Kembalian

Always true

## ObjectExt::Is(const U\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe pointer yang dioptimalkan untuk kelas 'final'.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const U\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe pointer.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe nilai.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang tidak dapat dikonversi.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

Always returns false as types are unconvertible.

## ObjectExt::Is(const SmartPtr\<U\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe pointer.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe pembungkus pengecualian.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat bernilai null.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibox dengan operator == terdefinisi.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe yang dapat dibox tanpa operator == terdefinisi.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<V\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi nilai tipe yang dibox ke antarmuka.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |
| V | Type of the pointed object. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<U\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe enum.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const WeakPtr\<U\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe enum vs pointer lemah.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) untuk menguji operator 'is'. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Nullable\<U\>\&) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk tipe [Nullable](../../nullable/).

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) tipe. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const char16_t *) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk literal string.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## ObjectExt::Is(int32_t) metode

Menerapkan terjemahan operator 'is'. Spesialisasi untuk literal integer.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | integer literal. |

### Nilai Kembalian

True if 'is' returns true, false otherwise.

## Lihat Juga

* Kelas [ObjectExt](../)
* Kelas [Object](../../object/)
* Kelas [SmartPtr](../../smartptr/)
* Kelas [ExceptionWrapper](../../exceptionwrapper/)
* Kelas [WeakPtr](../../weakptr/)
* Kelas [Nullable](../../nullable/)
* Struktur [IsBoxable](../../isboxable/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsNullable](../../isnullable/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)
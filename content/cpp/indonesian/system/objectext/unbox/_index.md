---
title: Unbox()
second_title: Referensi API Aspose.Slides untuk C++
description: Membongkar tipe nilai setelah dikonversi ke Object. Implementasi untuk tipe enum.
type: docs
weight: 53
url: /id/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metode


Membongkar tipe nilai setelah dikonversi ke [Object](../../object/). Implementasi untuk tipe enum.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) tipe. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk dibongkar. |

### Nilai Kembalian

[Enum](../../enum/) nilai.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metode


Membongkar tipe nilai setelah dikonversi ke [Object](../../object/). Implementasi untuk tipe non-enum dan non-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe nilai. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk dibongkar. |

### Nilai Kembalian

Nilai yang telah dibongkar.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metode


Membongkar tipe nilai setelah dikonversi ke [Object](../../object/). Implementasi untuk tipe non-enum dan non-nullable.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe nilai. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk dibongkar. |

### Nilai Kembalian

Nilai yang telah dibongkar.

## ObjectExt::Unbox(E) metode


Membongkar tipe enum menjadi integer.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe integer tujuan. |
| E | Tipe enum sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Nilai untuk dibongkar. |

### Nilai Kembalian

Representasi integer dari enum.

## ObjectExt::Unbox(E) metode


Mengonversi tipe enum.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| T | Tipe enum tujuan. |
| E | Tipe enum sumber. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Nilai untuk dibongkar. |

### Nilai Kembalian

Nilai enum yang dikonversi.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) metode


Membongkar nilai string.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) untuk dibongkar |

### Nilai Kembalian

Representasi [String](../../string/) dari string yang dibungkus, dapat bernilai null jika string yang dibungkus null.

## Lihat Juga

* Kelas [SmartPtr](../../smartptr/)
* Kelas [Object](../../object/)
* Kelas [ObjectExt](../)
* Kelas [String](../../string/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
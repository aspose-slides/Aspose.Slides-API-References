---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: 
type: docs
weight: 14
url: /id/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) metode




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## ObjectExt::Equals(const T\&, const T2\&) metode


Pengganti untuk panggilan C# [Object.Equals](../../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe pointer pintar.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek pertama. |
| T2 | Tipe objek kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Objek pertama. |
| another | const T2\& | Objek kedua. |

### Nilai Kembalian

True jika objek dianggap sama, false jika tidak.

## ObjectExt::Equals(T, const T2\&) metode


Pengganti untuk panggilan C# [Object.Equals](../../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe struktur.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek pertama. |
| T2 | Tipe objek kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | T | Objek pertama. |
| another | const T2\& | Objek kedua. |

### Nilai Kembalian

True jika objek dianggap sama, false jika tidak.

## ObjectExt::Equals(const T\&, const T2\&) metode


Pengganti untuk panggilan C# [Object.Equals](../../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk tipe skalar.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek pertama. |
| T2 | Tipe objek kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const T\& | Objek pertama. |
| another | const T2\& | Objek kedua. |

### Nilai Kembalian

True jika objek dianggap sama, false jika tidak.

## ObjectExt::Equals(const char_t(&), String) metode


Pengganti untuk panggilan C# [Object.Equals](../../object/equals/) yang bekerja untuk tipe apa pun di C++. Overload untuk literal string dengan perbandingan string.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| N | [String](../../string/) ukuran literal. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Nilai Kembalian

True jika string cocok, false jika tidak.

## ObjectExt::Equals(const float\&, const float\&) metode


Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const **float**\& | nilai titik mengambang LHS. |
| another | const **float**\& | nilai titik mengambang RHS. |

### Nilai Kembalian

True jika **obj** dan **another** keduanya NaN atau sama, false jika tidak.

## ObjectExt::Equals(const double\&, const double\&) metode


Meniru perbandingan titik mengambang gaya C# di mana dua NaN dianggap sama meskipun menurut IEC 60559:1989 NaN tidak sama dengan nilai apa pun, termasuk NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | const **double**\& | nilai titik mengambang LHS. |
| another | const **double**\& | nilai titik mengambang RHS. |

### Nilai Kembalian

True jika **obj** dan **another** keduanya NaN atau sama, false jika tidak.

## Lihat Juga

* Kelas [ObjectExt](../)
* Kelas [String](../../string/)
* Struktur [IsExceptionWrapper](../../isexceptionwrapper/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
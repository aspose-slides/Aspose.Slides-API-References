---
title: ReferenceEquals()
second_title: Aspose.Slides untuk Referensi API C++
description: "Spesialisasi Object::ReferenceEquals untuk kasus string dan nullptr."
type: docs
weight: 261
url: /id/system/object/referenceequals/
---
## Object::ReferenceEquals(String const\&, std::nullptr_t) method

Spesialisasi [Object::ReferenceEquals](./) untuk kasus string dan nullptr.

```cpp
bool System::Object::ReferenceEquals(String const &str, std::nullptr_t)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../string/) const\& | [String](../../string/) untuk dibandingkan dengan nullptr. |

### Nilai Kembali

true if string is null, false otherwise.

## Object::ReferenceEquals(String const\&, String const\&) method

Spesialisasi [Object::ReferenceEquals](./) untuk kasus string.

```cpp
bool System::Object::ReferenceEquals(String const &str1, String const &str2)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str1 | [String](../../string/) const\& | String pertama untuk dibandingkan. |
| str2 | [String](../../string/) const\& | String kedua untuk dibandingkan. |

### Nilai Kembali

true if strings match, false otherwise.

## Object::ReferenceEquals(ptr const\&, ptr const\&) method

Membandingkan objek berdasarkan referensi.

```cpp
static bool System::Object::ReferenceEquals(ptr const &objA, ptr const &objB)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | [ptr](../ptr/) const\& | Penunjuk pertama untuk dibandingkan. |
| objB | [ptr](../ptr/) const\& | Penunjuk kedua untuk dibandingkan. |

### Nilai Kembali

True if pointers match and false otherwise.

## Object::ReferenceEquals(T const\&, T const\&) method

Membandingkan objek berdasarkan referensi.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, T const &objB)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | T const\& | Objek pertama untuk dibandingkan. |
| objB | T const\& | Objek kedua untuk dibandingkan. |

### Nilai Kembali

True if object addresses match and false otherwise.

## Object::ReferenceEquals(T const\&, std::nullptr_t) method

Membandingkan referensi objek tipe nilai dengan nullptr.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, bool>::type System::Object::ReferenceEquals(T const &objA, std::nullptr_t)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe objek untuk dibandingkan. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| objA | T const\& | Objek pertama untuk dibandingkan. |

### Nilai Kembali

Selalu mengembalikan false karena tipe nilai tidak dapat bernilai null.

## Lihat Juga

* Typedef [ptr](../ptr/)
* Kelas [String](../../string/)
* Kelas [Object](../)
* Struktur [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
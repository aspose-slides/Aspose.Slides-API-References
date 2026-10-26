---
title: IsDefined()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah nilai yang ditentukan merupakan anggota tipe enumerasi E.
type: docs
weight: 27
url: /id/system/enum/isdefined/
---
## Enum::IsDefined(E) metode

Menentukan apakah nilai yang ditentukan merupakan anggota tipe enumerasi **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(E value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | E | Nilai yang akan diperiksa |

### Nilai Kembalian

True if **value** is a member of enumeration **E**, otherwise - false

## Enum::IsDefined(T) metode

Menentukan apakah nilai yang ditentukan merupakan anggota tipe enumerasi **T**.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, UnderlyingType>::value, bool>::type System::Enum<E, Guard>::IsDefined(T value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | T | Nilai yang akan diperiksa |

### Nilai Kembalian

True if **value** is a member of enumeration **T**, otherwise - false

## Enum::IsDefined(const String\&) metode

Menentukan apakah nilai dengan nama yang ditentukan berada di antara anggota enum **E**.

```cpp
static bool System::Enum<E, Guard>::IsDefined(const String &name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../string/)\& | Nama yang akan diperiksa |

### Nilai Kembalian

True jika terdapat anggota enum **E** dengan nama yang ditentukan.

## Lihat Juga

* Typedef [UnderlyingType](../underlyingtype/)
* Kelas [String](../../string/)
* Struktur [Enum](../)
* Namespace [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
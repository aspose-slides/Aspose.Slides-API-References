---
title: IsHighSurrogate()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan merupakan unit kode surrogate tinggi UTF-16.
type: docs
weight: 40
url: /id/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) metode

Menentukan apakah karakter pada indeks yang ditentukan dalam string yang ditentukan merupakan unit kode surrogate tinggi UTF-16.

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | Sebuah string |
| index | int | Indeks dalam string yang ditentukan untuk karakter yang diuji |

### Nilai Kembali

True jika karakter pada indeks yang ditentukan merupakan unit kode surrogate tinggi UTF-16, jika tidak - false

## Char::IsHighSurrogate(const char_t *, int) metode

Menentukan apakah karakter pada indeks yang ditentukan dalam buffer karakter yang ditentukan merupakan surrogate tinggi.

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const char_t * | Penunjuk ke awal buffer karakter |
| idx | int | Indeks berbasis nol dalam buffer yang ditentukan untuk karakter yang diuji |

### Nilai Kembali

True jika karakter pada indeks yang ditentukan merupakan surrogate tinggi, jika tidak - false

## Char::IsHighSurrogate(char_t) metode

Menentukan apakah karakter yang ditentukan merupakan surrogate tinggi.

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Karakter yang diuji |

### Nilai Kembali

True jika karakter yang ditentukan merupakan surrogate tinggi, jika tidak - false

## Lihat Juga

* Kelas [String](../../string/)
* Kelas [Char](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)
---
title: IsSurrogatePair()
second_title: Aspose.Slides untuk Referensi API C++
description: Menentukan apakah dua karakter yang ditentukan membentuk pasangan surrogate UTF-16.
type: docs
weight: 27
url: /id/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) metode

Menentukan apakah dua karakter yang ditentukan membentuk pasangan surrogate UTF-16.

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| highSurrogate | char_t | Karakter yang diuji sebagai surrogate tinggi |
| lowSurrogate | char_t | Karakter yang diuji sebagai surrogate rendah |

### Nilai Kembali

True jika karakter yang ditentukan membentuk pasangan surrogate, jika tidak - false

## Char::IsSurrogatePair(const String\&, int) metode

Menentukan apakah dua karakter berurutan dalam buffer karakter yang ditentukan merupakan pasangan surrogate.

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../string/)\& | Sebuah string |
| index | int | Indeks berbasis nol dalam buffer yang ditentukan di mana urutan karakter yang diuji dimulai |

### Nilai Kembali

True jika karakter yang ditentukan membentuk pasangan surrogate, jika tidak - false

## Lihat Juga

* Kelas [Char](../)
* Kelas [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
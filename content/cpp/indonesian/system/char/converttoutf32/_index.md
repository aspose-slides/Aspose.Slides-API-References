---
title: ConvertToUtf32()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi pasangan surrogate UTF-16 yang ditentukan menjadi unit kode UTF-32.
type: docs
weight: 287
url: /id/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) metode

Mengonversi pasangan surrogate UTF-16 yang ditentukan menjadi unit kode UTF-32.

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| highSurrogate | char_t | Surrogate tinggi dari pasangan surrogate UTF-16 yang akan dikonversi |
| lowSurrogate | char_t | Surrogate rendah dari pasangan surrogate UTF-16 yang akan dikonversi |

### Nilai Kembalian

Unit kode UTF-32 hasil konversi

## Char::ConvertToUtf32(const String\&, int) metode

Mengonversi nilai karakter atau pasangan surrogate yang dienkode UTF-16 pada posisi tertentu dalam string menjadi unit kode UTF-32.

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../string/)\& | String yang berisi karakter atau pasangan surrogate |
| index | int | Posisi indeks karakter atau pasangan surrogate dalam string yang ditentukan |

### Nilai Kembalian

Unit kode UTF-32 hasil konversi

## Lihat Juga

* Class [Char](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
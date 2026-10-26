---
title: IndexOfAny()
second_title: Referensi API Aspose.Slides untuk C++
description: Pencarian karakter maju.
type: docs
weight: 638
url: /id/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const metode

Pencarian karakter maju.

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Karakter yang dicari. |
| startIndex | int | [Index](../../index/) untuk memulai pencarian pada. |

### Nilai Kembali

[Index](../../index/) posisi karakter pertama sejak startIndex atau -1 jika tidak ditemukan.

## String::IndexOfAny(const String\&, int) const metode

Secara berurutan mencari semua karakter dari str dalam objek ini. Jika karakter pertama ditemukan, posisinya dikembalikan, jika tidak, mencari karakter kedua dan seterusnya.

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) karakter yang dicari. Urutan karakter penting. |
| startIndex | int | Posisi untuk memulai pencarian. |

### Nilai Kembali

[Index](../../index/) karakter pertama yang ditemukan atau -1 jika tidak ada yang ditemukan.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const metode

Mencari salah satu karakter yang diberikan di seluruh string. Membandingkan karakter pertama string dengan semua karakter dalam anyOf, kemudian membandingkan yang kedua, dan seterusnya. Mengembalikan indeks dari karakter pertama yang cocok dengan salah satu karakter target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter yang dicari. Urutan tidak penting. |

### Nilai Kembali

[Index](../../index/) karakter pertama yang cocok atau -1 jika tidak ditemukan.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metode

Mencari salah satu karakter yang diberikan melalui substring. Membandingkan karakter pertama string dengan semua karakter dalam anyOf, kemudian membandingkan yang kedua, dan seterusnya. Mengembalikan indeks dari karakter pertama yang cocok dengan salah satu karakter target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter yang dicari. Urutan tidak penting. |
| startindex | **int32_t** | [Index](../../index/) untuk memulai pencarian dari. |

### Nilai Kembali

[Index](../../index/) karakter pertama yang cocok atau -1 jika tidak ditemukan.

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metode

Mencari salah satu karakter yang diberikan melalui substring. Membandingkan karakter pertama string dengan semua karakter dalam anyOf, kemudian membandingkan yang kedua, dan seterusnya. Mengembalikan indeks dari karakter pertama yang cocok dengan salah satu karakter target.

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter yang dicari. Urutan tidak penting. |
| startindex | **int32_t** | [Index](../../index/) untuk memulai pencarian dari. |
| count | **int32_t** | Jumlah karakter yang akan diperiksa. |

### Nilai Kembali

[Index](../../index/) karakter pertama yang cocok atau -1 jika tidak ditemukan.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
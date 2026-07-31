---
title: LastIndexOfAny()
second_title: Aspose.Slides untuk Referensi API C++
description: Mencari salah satu karakter yang diberikan melalui seluruh string secara terbalik. Membandingkan karakter terakhir string dengan semua karakter dalam anyOf, kemudian membandingkan yang sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan.
type: docs
weight: 664
url: /id/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const metode

Mencari salah satu karakter yang diberikan dalam seluruh string secara terbalik. Membandingkan karakter terakhir string dengan semua karakter dalam anyOf, kemudian membandingkan yang sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter untuk dicari. Urutan tidak penting. |

### Nilai Kembalian

[Index](../../index/) karakter yang cocok terakhir atau -1 jika tidak ditemukan.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const metode

Mencari salah satu karakter yang diberikan dalam substring secara terbalik. Membandingkan karakter terakhir string dengan semua karakter dalam anyOf, kemudian membandingkan yang sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter untuk dicari. Urutan tidak penting. |
| startindex | **int32_t** | [Index](../../index/) untuk memulai pencarian dari. |

### Nilai Kembalian

[Index](../../index/) karakter yang cocok terakhir atau -1 jika tidak ditemukan.

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const metode

Mencari salah satu karakter yang diberikan dalam substring secara terbalik. Membandingkan karakter terakhir string dengan semua karakter dalam anyOf, kemudian membandingkan yang sebelumnya, dan seterusnya. Mengembalikan indeks kecocokan pertama yang ditemukan.

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter untuk dicari. Urutan tidak penting. |
| startindex | **int32_t** | [Index](../../index/) untuk memulai pencarian dari. |
| count | **int32_t** | Jumlah karakter yang akan diperiksa. |

### Nilai Kembalian

[Index](../../index/) karakter yang cocok terakhir atau -1 jika tidak ditemukan.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Kelas [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Pencarian substring ke depan.
type: docs
weight: 625
url: /id/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const metode


Pencarian substring ke depan.

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang dicari. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembali

[Index](../../index/) dari substring pertama yang ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan 0.

## String::IndexOf(char_t, int) const metode


Pencarian karakter ke depan.

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Karakter yang dicari. |
| startIndex | int | [Index](../../index/) untuk memulai pencarian pada. |

### Nilai Kembali

[Index](../../index/) dari posisi karakter pertama sejak startIndex atau -1 jika tidak ditemukan.

## String::IndexOf(char_t, int, int) const metode


Pencarian karakter ke depan dalam substring.

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| c | char_t | Karakter yang dicari. |
| startIndex | int | [Index](../../index/) untuk memulai pencarian pada. |
| count | int | Jumlah karakter yang akan diperiksa. |

### Nilai Kembali

[Index](../../index/) dari posisi karakter pertama sejak startIndex atau -1 jika tidak ditemukan.

## String::IndexOf(const String\&, int) const metode


Pencarian substring ke depan.

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |

### Nilai Kembali

[Index](../../index/) dari substring pertama yang ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan startIndex.

## String::IndexOf(const String\&, int, System::StringComparison) const metode


Pencarian substring ke depan.

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembali

[Index](../../index/) dari substring pertama yang ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan startIndex.

## String::IndexOf(const String\&, int, int, System::StringComparison) const metode


Pencarian substring ke depan.

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../)\& | Substring yang dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |
| count | int | jumlah karakter yang akan diperiksa. |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembali

[Index](../../index/) dari substring pertama yang ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan startIndex.

## String::IndexOf(const String\&, int, int) const metode


Pencarian substring ke depan.

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |
| count | int | jumlah karakter yang akan diperiksa. |

### Nilai Kembali

[Index](../../index/) dari substring pertama yang ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan startIndex.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
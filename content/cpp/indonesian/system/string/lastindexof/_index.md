---
title: LastIndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Pencarian mundur substring.
type: docs
weight: 651
url: /id/system/string/lastindexof/
---
## String::LastIndexOf(const String\&, int) const metode

Pencarian mundur substring.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex=INT32_MAX) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang akan dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |

### Nilai Kembalian

[Index](../../index/) dari substring yang terakhir ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan panjang string.

## String::LastIndexOf(const String\&, System::StringComparison) const metode

Pencarian mundur substring.

```cpp
int System::String::LastIndexOf(const String &str, System::StringComparison comparison_type) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang akan dicari. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembalian

[Index](../../index/) dari substring yang terakhir ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan panjang string.

## String::LastIndexOf(const String\&, int, System::StringComparison) const metode

Pencarian mundur substring.

```cpp
int System::String::LastIndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | Substring yang akan dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembalian

[Index](../../index/) dari substring yang terakhir ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan panjang string.

## String::LastIndexOf(const String\&, int, int, StringComparison) const metode

Pencarian mundur substring.

```cpp
int System::String::LastIndexOf(const String &value, int startIndex, int count, StringComparison comparisonType) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../)\& | Substring yang akan dicari. |
| startIndex | int | Posisi dalam string sumber untuk memulai pencarian. |
| count | int | Jumlah karakter yang akan dicari. |
| comparisonType | [StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembalian

[Index](../../index/) dari substring yang terakhir ditemukan atau -1 jika tidak ditemukan. Untuk string pencarian kosong, selalu mengembalikan startIndex+count.

## String::LastIndexOf(char_t) const metode

Pencarian mundur karakter.

```cpp
int System::String::LastIndexOf(char_t value) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Karakter yang dicari. |

### Nilai Kembalian

[Index](../../index/) dari posisi karakter terakhir atau -1 jika tidak ditemukan.

## String::LastIndexOf(char_t, int32_t) const metode

Pencarian mundur karakter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Karakter yang dicari. |
| startIndex | **int32_t** | [Index](../../index/) untuk memulai pencarian pada. |

### Nilai Kembalian

[Index](../../index/) dari posisi karakter terakhir sejak startIndex atau -1 jika tidak ditemukan.

## String::LastIndexOf(char_t, int32_t, int32_t) const metode

Pencarian mundur karakter.

```cpp
int System::String::LastIndexOf(char_t value, int32_t startIndex, int32_t count) const
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Karakter yang dicari. |
| startIndex | **int32_t** | [Index](../../index/) untuk memulai pencarian pada. |
| count | **int32_t** | Jumlah karakter yang akan dicari |
 
### Nilai Kembalian

[Index](../../index/) dari posisi karakter terakhir sejak startIndex atau -1 jika tidak ditemukan.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Kelas [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
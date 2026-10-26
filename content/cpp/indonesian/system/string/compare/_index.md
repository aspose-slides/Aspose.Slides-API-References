---
title: Compare()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua substring dengan kurang-sama-lebih.
type: docs
weight: 820
url: /id/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) metode


Membandingkan dua substring dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| indexA | int | Awal substring string pertama. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| indexB | int | Awal substring string kedua. |
| length | int | Jumlah karakter yang akan dibandingkan. |
| ignoreCase | **bool** | Menentukan apakah perbandingan tidak memperhatikan huruf besar/kecil. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metode


Membandingkan dua substring dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| indexA | int | Awal substring string pertama. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| indexB | int | Awal substring string kedua. |
| length | int | Jumlah karakter yang akan dibandingkan. |
| ignoreCase | **bool** | Menentukan apakah perbandingan tidak memperhatikan huruf besar/kecil. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan untuk perbandingan. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## String::Compare(const String\&, const String\&, System::StringComparison) metode


Membandingkan dua string dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) metode


Membandingkan dua string dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| indexA | int | Awal substring string pertama. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| indexB | int | Awal substring string kedua. |
| length | int | Jumlah karakter yang akan dibandingkan. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) mode. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## String::Compare(const String\&, const String\&, bool) metode


Membandingkan dua string dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| ignoreCase | **bool** | Menentukan apakah perbandingan tidak memperhatikan huruf besar/kecil. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) metode


Membandingkan dua string dengan kurang-sama-lebih.

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| ignoreCase | **bool** | Menentukan apakah perbandingan tidak memperhatikan huruf besar/kecil. |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Budaya yang digunakan untuk perbandingan. |

### Nilai Kembalian

Nilai negatif jika substring pertama lebih kecil dari yang kedua, nol jika keduanya sama, nilai positif jika tidak.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)
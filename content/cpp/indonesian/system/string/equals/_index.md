---
title: Equals()
second_title: Referensi API Aspose.Slides untuk C++
description: Perbandingan kesetaraan string. Beberapa mode yang disediakan oleh enumerasi StringComparison didukung.
type: docs
weight: 391
url: /id/system/string/equals/
---
## String::Equals(const String\&, System::StringComparison) const method


[String](../) perbandingan kesetaraan. Beberapa mode yang disediakan oleh enumerasi StringComparison didukung.

```cpp
bool System::String::Equals(const String &str, System::StringComparison comparison_type) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) untuk dibandingkan dengan yang saat ini. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | mode [Comparison](../../comparison/) (lihat [System::StringComparison](../../stringcomparison/) untuk detail). |

### Nilai Kembalian

true jika string cocok menggunakan jenis perbandingan yang dipilih, false jika tidak.

## String::Equals(const String\&) const method


[String](../) perbandingan kesetaraan. Menggunakan mode perbandingan [System::StringComparison::Ordinal](../../stringcomparison/).

```cpp
bool System::String::Equals(const String &str) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) untuk dibandingkan dengan yang saat ini. |

### Nilai Kembalian

true jika string cocok, false jika tidak.

## String::Equals(const String\&, const String\&) method


Membandingkan dua string secara setara menggunakan mode perbandingan Ordial.

```cpp
static bool System::String::Equals(const String &strA, const String &strB)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |

### Nilai Kembalian

true jika string cocok, false jika tidak.

## String::Equals(const String\&, const String\&, System::StringComparison) method


Membandingkan dua string secara setara.

```cpp
static bool System::String::Equals(const String &strA, const String &strB, System::StringComparison comparison_type)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| comparison_type | [System::StringComparison](../../stringcomparison/) | mode [Comparison](../../comparison/). |

### Nilai Kembalian

true jika string cocok, false jika tidak.

## Lihat Juga

* Enum [StringComparison](../../stringcomparison/)
* Kelas [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
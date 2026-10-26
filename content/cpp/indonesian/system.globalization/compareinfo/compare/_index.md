---
title: Compare()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan string. Tidak diimplementasikan.
type: docs
weight: 66
url: /id/system.globalization/compareinfo/compare/
---
## CompareInfo::Compare(const String\&, const String\&) const metode


Membandingkan string. Tidak diimplementasikan.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, const String &string2) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String LHS. |
| string2 | const [String](../../../system/string/)\& | String RHS. |

### Nilai Kembali

Nilai negatif jika string LHS mendahului RHS, nol jika cocok, nilai positif sebaliknya.

## CompareInfo::Compare(const String\&, const String\&, CompareOptions) const metode


Membandingkan string. Hanya mode Ordinal dan OrdinalIgnoreCase yang didukung.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &a, const String &b, CompareOptions options) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| a | const [String](../../../system/string/)\& | String LHS. |
| b | const [String](../../../system/string/)\& | String RHS. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) tipe perbandingan. |

### Nilai Kembali

Nilai negatif jika string LHS mendahului RHS, nol jika cocok, nilai positif sebaliknya.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int) const metode


Membandingkan bagian dari satu string dengan bagian string kedua. Tidak diimplementasikan.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String pertama. |
| offset1 | int | Indeks mulai karakter dalam **string1**. |
| length1 | int | Jumlah karakter dalam **string1** untuk dibandingkan. |
| string2 | const [String](../../../system/string/)\& | String kedua. |
| offset2 | int | Indeks mulai karakter dalam **string2**. |
| length2 | int | Jumlah karakter dalam **string2** untuk dibandingkan. |

### Nilai Kembali

Nilai negatif jika bagian string pertama mendahului bagian string kedua, nol jika cocok, nilai positif sebaliknya.

## CompareInfo::Compare(const String\&, int, const String\&, int, CompareOptions) const metode


Membandingkan bagian akhir dari satu string dengan bagian akhir string kedua menggunakan metode perbandingan string. Tidak diimplementasikan.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2, CompareOptions options) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String pertama. |
| offset1 | int | Indeks mulai karakter dalam **string1**. |
| string2 | const [String](../../../system/string/)\& | String kedua. |
| offset2 | int | Indeks mulai karakter dalam **string2**. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opsi perbandingan. |

### Nilai Kembali

Nilai negatif jika bagian string pertama mendahului bagian string kedua, nol jika cocok, nilai positif sebaliknya.

## CompareInfo::Compare(const String\&, int, const String\&, int) const metode


Membandingkan bagian akhir dari satu string dengan bagian akhir string kedua. Tidak diimplementasikan.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, const String &string2, int offset2) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String pertama. |
| offset1 | int | Indeks mulai karakter dalam **string1**. |
| string2 | const [String](../../../system/string/)\& | String kedua. |
| offset2 | int | Indeks mulai karakter dalam **string2**. |

### Nilai Kembali

Nilai negatif jika bagian string pertama mendahului bagian string kedua, nol jika cocok, nilai positif sebaliknya.

## CompareInfo::Compare(const String\&, int, int, const String\&, int, int, CompareOptions) const metode


Membandingkan bagian dari satu string dengan bagian string kedua menggunakan metode perbandingan string. Tidak diimplementasikan.

```cpp
virtual int System::Globalization::CompareInfo::Compare(const String &string1, int offset1, int length1, const String &string2, int offset2, int length2, CompareOptions options) const
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| string1 | const [String](../../../system/string/)\& | String pertama. |
| offset1 | int | Indeks mulai karakter dalam **string1**. |
| length1 | int | Jumlah karakter dalam **string1** untuk dibandingkan. |
| string2 | const [String](../../../system/string/)\& | String kedua. |
| offset2 | int | Indeks mulai karakter dalam **string2**. |
| length2 | int | Jumlah karakter dalam **string2** untuk dibandingkan. |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) opsi perbandingan. |

### Nilai Kembali

Nilai negatif jika bagian string pertama mendahului bagian string kedua, nol jika cocok, nilai positif sebaliknya.

## Lihat Juga

* Enum [CompareOptions](../../compareoptions/)
* Kelas [String](../../../system/string/)
* Kelas [CompareInfo](../)
* Ruang Nama [System::Globalization](../../)
* Perpustakaan [Aspose.Slides](../../../)
---
title: CompareOrdinal()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua string dengan nilai kurang-sama-lebih menggunakan mode ordinal.
type: docs
weight: 833
url: /id/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) metode

Membandingkan dua string menggunakan mode ordinal.

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |

### Nilai Kembali

Nilai negatif jika substring pertama kurang dari yang kedua, nol jika cocok, nilai positif bila tidak.

## String::CompareOrdinal(const String\&, int, const String\&, int, int) metode

Membandingkan dua string menggunakan mode ordinal.

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| strA | const [String](../)\& | String pertama untuk dibandingkan. |
| indexA | int | Awal substring string pertama. |
| strB | const [String](../)\& | String kedua untuk dibandingkan. |
| indexB | int | Awal substring string kedua. |
| length | int | Jumlah karakter yang dibandingkan. |

### Nilai Kembali

Nilai negatif jika substring pertama kurang dari yang kedua, nol jika cocok, nilai positif bila tidak.

## Lihat Juga

* Kelas [String](../)
* Ruang Nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)
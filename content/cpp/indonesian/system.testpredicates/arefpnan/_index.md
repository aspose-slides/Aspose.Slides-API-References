---
title: AreFPNaN()
second_title: Referensi API Aspose.Slides untuk C++
description: Rincian namespace
type: docs
weight: 1
url: /id/system.testpredicates/arefpnan/
---
## System::TestPredicates::AreFPNaN(T1, T2) fungsi


namespace [Details](../../system.testpredicates.details/)

```cpp
template<typename T1,typename T2> std::enable_if<std::numeric_limits<T1>::has_quiet_NaN &&std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe titik mengambang pertama. |
| T2 | Tipe titik mengambang kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | T1 | Nilai titik mengambang pertama. |
| rhs | T2 | Nilai titik mengambang kedua. |

### Nilai Kembali

True jika kedua **lhs** dan **rhs** adalah nilai floating point, false jika tidak.
## Catatan


Memeriksa bahwa dua nilai titik mengambang keduanya NaN. Menangani situasi ketika NaN non-signalling didukung. 
## System::TestPredicates::AreFPNaN(T1, T2) fungsi


Memeriksa bahwa dua nilai titik mengambang keduanya NaN. Menangani situasi ketika NaN non-signalling tidak didukung.

```cpp
template<typename T1,typename T2> std::enable_if<!std::numeric_limits<T1>::has_quiet_NaN||!std::numeric_limits<T2>::has_quiet_NaN, bool>::type System::TestPredicates::AreFPNaN(T1 lhs, T2 rhs)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T1 | Tipe titik mengambang pertama. |
| T2 | Tipe titik mengambang kedua. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| lhs | T1 | Nilai titik mengambang pertama. |
| rhs | T2 | Nilai titik mengambang kedua. |

### Nilai Kembali

Selalu mengembalikan false karena nilai NaN tidak didukung.

## Lihat Juga

* Ruang Nama [System::TestPredicates](../)
* Pustaka [Aspose.Slides](../../)
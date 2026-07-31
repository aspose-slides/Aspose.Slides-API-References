---
title: Compare()
second_title: Referensi API Aspose.Slides untuk C++
description: Membandingkan dua nilai.
type: docs
weight: 2731
url: /id/system/compare/
---
## System::Compare(const TA\&, const TB\&) fungsi

Membandingkan dua nilai.

```cpp
template<typename TA,typename TB> std::enable_if_t<!std::is_floating_point<TA>::value &&!std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TA | Tipe dari comparand pertama |
| TB | Tipe dari comparand kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const TA\& | Comparand pertama |
| b | const TB\& | Comparand kedua |

### Nilai Kembalian

- 1 jika **a** lebih kecil daripada **b**; 0 jika nilai-nilai tersebut sama; 1 jika **a** lebih besar daripada **b**

## System::Compare(const TA\&, const TB\&) fungsi

Membandingkan dua nilai floating point.

```cpp
template<typename TA,typename TB> std::enable_if_t<std::is_floating_point<TA>::value &&std::is_floating_point<TB>::value, int> System::Compare(const TA &a, const TB &b)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| TA | Tipe dari comparand pertama |
| TB | Tipe dari comparand kedua |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a | const TA\& | Comparand pertama |
| b | const TB\& | Comparand kedua |

### Nilai Kembalian

- 1 jika **a** lebih kecil daripada **b**; 0 jika nilai-nilai tersebut sama; 1 jika **a** lebih besar daripada **b**

## Lihat Juga

* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)
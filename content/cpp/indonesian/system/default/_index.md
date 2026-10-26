---
title: Default()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mengembalikan referensi ke satu instance yang dibangun secara default dari tipe pengecualian.
type: docs
weight: 2224
url: /id/system/default/
---
## System::Default() fungsi

Mengembalikan referensi ke satu instance yang dibangun secara default dari tipe pengecualian.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang instance-nya dikembalikan |

## System::Default() fungsi

Mengembalikan referensi ke satu instance yang dibangun secara default dari tipe non-pengecualian.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe yang instance-nya dikembalikan |

## Lihat Juga

* Struktur [IsExceptionWrapper](../isexceptionwrapper/)
* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)
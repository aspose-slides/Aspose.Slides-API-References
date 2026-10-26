---
title: Exchange()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menukar nilai pada variabel: menyimpan nilai baru dan mengembalikan nilai variabel tepat sebelum disimpan."
type: docs
weight: 66
url: /id/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) metode

Menukar nilai pada variabel: menyimpan nilai baru dan mengembalikan nilai variabel tepat sebelum disimpan.

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe variabel. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location1 | T\& | Referensi variabel yang akan diubah. |
| value | T | Nilai yang akan disimpan. |

### Nilai Kembali

Nilai variabel tepat sebelum diubah.

## Interlocked::Exchange(T\&, T) metode

Menukar nilai pada variabel: menyimpan nilai baru dan mengembalikan nilai variabel tepat sebelum disimpan. Tidak diimplementasikan.

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe variabel. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| location1 | T\& | Referensi variabel yang akan diubah. |
| value | T | Nilai yang akan disimpan. |

### Nilai Kembali

Nilai variabel tepat sebelum diubah.

## Lihat Juga

* Kelas [Interlocked](../)
* Ruang nama [System::Threading](../../)
* Library [Aspose.Slides](../../../)
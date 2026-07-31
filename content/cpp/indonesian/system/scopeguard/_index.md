---
title: ScopeGuard
second_title: Referensi API Aspose.Slides untuk C++
description: Kelas layanan yang menyediakan layanan untuk menjalankan objek fungsi tertentu ketika sebuah instance kelas keluar dari ruang lingkup.
type: docs
weight: 1886
url: /id/system/scopeguard/
---
## ScopeGuard struct

Kelas layanan yang menyediakan layanan untuk menjalankan objek fungsi tertentu ketika sebuah instance kelas keluar dari ruang lingkup.

```cpp
template<typename F>class ScopeGuard
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| F | Tipe objek fungsi yang dipanggil oleh instance kelas ScopedGuard |

## Metode

| Metode | Deskripsi |
| --- | --- |
| void [Disable](./disable/)() | Menonaktifkan pemanggilan guard. |
| [ScopeGuard](./scopeguard/)(F) | Membuat sebuah instance yang disiapkan untuk memanggil objek fungsi yang ditentukan. |
| [~ScopeGuard](./~scopeguard/)() | Memanggil objek fungsi yang diberikan ke konstruktor. |

## Lihat Juga

* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)
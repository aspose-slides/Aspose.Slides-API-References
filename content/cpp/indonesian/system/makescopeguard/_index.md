---
title: MakeScopeGuard()
second_title: Referensi API Aspose.Slides untuk C++
description: Fungsi pabrik yang membuat instance kelas ScopedGuard.
type: docs
weight: 2809
url: /id/system/makescopeguard/
---
## System::MakeScopeGuard(F) fungsi

Fungsi pabrik yang membuat instance kelas ScopedGuard.

```cpp
template<typename F> ScopeGuard<F> System::MakeScopeGuard(F f)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| The | tipe objek fungsi yang akan dipanggil oleh objek ScopedGuard yang dibuat |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| f | F | Objek fungsi yang akan diteruskan ke konstruktor kelas ScopedGuard. |

### Nilai Kembalian

Sebuah instance baru dari kelas ScopedGuard

## Lihat Juga

* Struct [ScopeGuard](../scopeguard/)
* Ruang Nama [System](../)
* Pustaka [Aspose.Slides](../../)
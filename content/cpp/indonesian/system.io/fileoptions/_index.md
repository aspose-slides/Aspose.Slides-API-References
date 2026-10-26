---
title: FileOptions
second_title: Referensi API Aspose.Slides untuk C++
description: Mewakili opsi lanjutan untuk membuat objek FileStream.
type: docs
weight: 521
url: /id/system.io/fileoptions/
---
## FileOptions enum

Mewakili opsi lanjutan untuk membuat objek [FileStream](../filestream/).

```cpp
enum class FileOptions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Tidak ada opsi tambahan. |
| Encrypted | 16384 | File terenkripsi. BELUM DIIMPLEMENTASIKAN. |
| DeleteOnClose | 67108864 | File harus dihapus secara otomatis ketika tidak lagi digunakan. |
| SequentialScan | 134217728 | File harus diakses secara berurutan. |
| RandomAccess | 268435456 | File diakses secara acak. |
| Asynchronous | 1073741824 | File dapat digunakan untuk operasi I/O asinkron. |
| WriteThrough | n/a | Semua penulisan harus langsung ke disk melewati cache menengah. |

## Lihat Juga

* Namespace [System::IO](../)
* Perpustakaan [Aspose.Slides](../../)
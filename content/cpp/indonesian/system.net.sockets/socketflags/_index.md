---
title: SocketFlags
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan nilai konstan untuk pesan socket.
type: docs
weight: 222
url: /id/system.net.sockets/socketflags/
---
## SocketFlags enum

Menyediakan nilai konstan untuk pesan socket.

```cpp
enum class SocketFlags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Tidak ada flag yang digunakan untuk panggilan ini. |
| OutOfBand | 1 | Data out-of-band sedang diproses. |
| Peek | 2 | Intip pesan yang masuk. |
| DontRoute | 4 | Kirim pesan tanpa menggunakan tabel routing. |
| Truncated | 256 | Pesan terlalu besar untuk muat ke dalam buffer yang ditentukan. Pesan tersebut telah dipotong. |
| ControlDataTruncated | 512 | Data kontrol lebih besar dari 64 KB dan tidak muat ke dalam buffer internal. Data tersebut telah dipotong. |
| Broadcast | 1024 | Paket siaran. |
| Multicast | 2048 | Paket multicast. |
| Partial | 32768 | Pesan yang dikirim atau diterima sebagian. |

## Lihat Juga

* Ruang Nama [System::Net::Sockets](../)
* Perpustakaan [Aspose.Slides](../../)
---
title: CipherMode
second_title: Referensi API Aspose.Slides untuk C++
description: Mode blok cipher.
type: docs
weight: 885
url: /id/system.security.cryptography/ciphermode/
---
## CipherMode enum

Mode blok cipher.

```cpp
enum class CipherMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| CBC | 1 | Cipher block chaining yang menggabungkan blok saat ini dengan blok sebelumnya untuk meningkatkan enkripsi. |
| ECB | 2 | Mode electronic codebook tanpa pengaruh antar blok; menghasilkan enkripsi yang lebih lemah. |
| OFB | 3 | Mode output feedback yang menangani blok input besar dalam potongan kecil. |
| CFB | 4 | Mode cipher feedback yang menangani blok input besar dalam potongan kecil. Aturan pengacakan berbeda dari OFB. |
| CTS | 5 | Mode cipher text stealing, berperilaku seperti CBC untuk semua kecuali dua blok terakhir teks. |

## Lihat Juga

* Ruang Nama [System::Security::Cryptography](../)
* Perpustakaan [Aspose.Slides](../../)